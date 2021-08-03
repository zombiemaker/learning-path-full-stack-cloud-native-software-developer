# ECMAScript 6 Features

## Symbols

Can use ES6 symbols as object property names.

```
let p = {x: 10, y: 20, z: 30}

const symColor = Symbol('color')
p[symColor] = 'red'

const symMsg = Symbol('msg')
p[symMsg] = 'Hi!

console.log(p.x, p.y, p.z)  // 10 20 30
console.log(p[x]), p[y], p[z])  // 10 20 30
console.log(p[symColor]) // red
console.log(p[symMsg]) // Hi!
```

Every symbol object is unique

```
const sym1 = Symbol('mySymbol')
const sym2 = Symbol('mySymbol') // This is different from sym1

console.log(sym1 == sym2)  // false
console.log(sym1 === sym2)  // false
```

This means that you can use symbols to dynamically add more properties to an object and guarantee not to overwrite a previous property with the same literal name.

```
const sym1 = Symbol('msg')
myObj[sym1] = 'Hi!'

// ...
// some other area of the program

const sym2 = Symbol('msg') // This is different from sym1
obj[sym2] = 'Bye!'

console.log(obj[sym1])  // Hi!
console.log(obj[sym2])  // Bye!
```



```
let p = {
    x: 10,                      // string property name
    [Symbol('color')]: 'red     // symbol property name
}

Object.getOwnPropertySymbols(p)
```

## ES6 Classes

Use ES6 modules and symbols for property names to implement private properties 


module1.js
```
const _fn = Symbol('fn')
const _ln = Symbol('ln')

export class Person {
    constructor(fn, ln){
        this[_fn] = fn
        this[_ln] = ln        
    }
}
```

module2.js
```
import {Person} from './module1'

let p = new Person('Bob', 'Jones')
p._fn = 'Ed'  // Does not work
p._ln = 'Smith'  // Does not work
```


## Testing if an object has a function

```
Object.prototype.can = function(methodName)
{
     return ((typeof this[methodName]) == "function");
};

if (someObject.can("quack"))
{
    someObject.quack();
}
```