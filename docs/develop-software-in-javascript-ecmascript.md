# Develop Software In JavaScript / ECMAScript

## Basics

* ECMAScript 6 (ES6)
  * [Learn Javascript (O'Reilly Video)](https://learning.oreilly.com/videos/learn-javascript/9780136752899)
  * [The Modern JavaScript Bootcamp (2019) (Andrew Mead)](https://learning.oreilly.com/videos/the-modern-javascript/9781838983734/)
  * [Modern JavaScript for the Impatient (Cay S. Horstmann)](https://learning.oreilly.com/videos/modern-javascript-for/9780135812778)
  * [JavaScript Bible - JavaScript and ES6 Bootcamp 2019 (Bogdan Stashchulk)](https://learning.oreilly.com/videos/javascript-bible/9781839211782)

## Advanced

* ECMAScript 2019
  * [Modern Web Development (Dimitris Loukas)](https://learning.oreilly.com/videos/javascript-essentials-for/9781838982676)
  * [ECMAScript 2019 New Features (Sachin Bhatnagar)](https://learning.oreilly.com/videos/ecmascript-2019-new/9781838641825)
  * [Mastering JavaScript Functional Programming - Second Edition (Federico Kereki)](https://learning.oreilly.com/library/view/mastering-javascript-functional/9781839213069/)
* JavaScript module systems
  * [ECMAScript Modules In ES6+](https://www.ecma-international.org/ecma-262/#sec-modules)
  * [CommonJS in Node.js](https://requirejs.org/docs/commonjs.html)
  * [Asynchronous Module Definition (AMD)](https://github.com/amdjs/amdjs-api/blob/master/AMD.md)
  * [Universal Module Definition (UMD)](https://github.com/umdjs/umd)
* JavaScript package manager systems
  * [Node Package Manager (npm)](https://www.npmjs.com/)
  * [Yarn](https://yarnpkg.com/)

## Resources

* ECMAScript Language Specifications
  * [ECMAScript 6 / ECMAScript 2015 Language Specification](http://www.ecma-international.org/ecma-262/6.0/)
  * [ECMAScript 7 / ECMAScript 2016 Language Specification](https://www.ecma-international.org/ecma-262/7.0/)
  * [ECMAScript 8 / ECMAScript 2017 Language Specification](https://www.ecma-international.org/ecma-262/8.0/)
  * [ECMAScript 9 / ECMAScript 2018 Language Specification](https://ecma-international.org/ecma-262/9.0/)
  * [ECMAScript 10 / ECMAScript 2019 Language Specification](https://www.ecma-international.org/ecma-262/10.0/)
  * [ECMAScript 2020 Language Specification](https://www.ecma-international.org/ecma-262/)
* JavaScript Runtime Execution Engines / Virtual Machines
  * [Google JavaScript V8 Engine](https://v8.dev/)
  * [Mozilla SpiderMonkey Engine](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey)
  * [Microsoft Chakra Engine](https://github.com/microsoft/ChakraCore )
  * [Apple JavaScriptCore](https://developer.apple.com/documentation/javascriptcore)
  * [JerryScript](https://jerryscript.net/)
  * [GraalVM JavaScript](https://github.com/graalvm/graaljs)
  * [Comparison Of JavaScript Engine](https://en.wikipedia.org/wiki/Comparison_of_JavaScript_engines)
  * [ECMAScript Feature Support](https://kangax.github.io/compat-table/es6/)
* JavaScript Runtime Platforms
  * [Node.js (V8)](https://nodejs.org)
  * [Deno JavaScript Runtime (V8)](https://deno.land/)
  * [Google Chrome (V8)](https://www.google.com/chrome/)
  * [Moziller Firefox (SpiderMonkey)](https://www.mozilla.org/en-US/firefox/)
  * [Microsoft Edge (Chakra)](https://www.microsoft.com/en-us/edge)
  * [Apple Safari (JavaScriptCore)](https://www.apple.com/safari/)
  * [Oracle GraalVM](https://www.graalvm.org/)
* JavaScript Organizations
  * [OpenJS Foundation](https://openjsf.org/)



## Different JavaScript Execution Environments

### JavaScript / ECMAScript Runtime Engines / Virtual Machines

* Google V8
* Mozilla SpiderMonkey
* Microsoft Chakra
* Apple JavaScriptCore
* JerryScript

### Web Browser Context

* Processes response objects
* JavaScript process is executed in a sandbox with restricted access to computer system resources
* JavaScript objects available in web browsers
  * window
  * document
  * localStorage
  * console
  * JSON
  * global (refers to window object)
* JavaScript module systems
  * ECMAScript Modules
* JavaScript package manager systems


### Node.js Context

* Processes request objects
* JavaScript process is executed with full user-level computer system access
* JavaScript objects availabe in Node.js
  * CommonJS objects
    * require
    * exports
    * module.exports
    * _filename
    * _dirname
  * global
* JavaScript module systems
  * CommonJS
  * ECMAScript Modules
* JavaScript package manager systems
  * npm
  * Yarn