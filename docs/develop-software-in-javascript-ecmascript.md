# Develop Software In JavaScript / ECMAScript

## Different JavaScript Execution Environments

### JavaScript / ECMAScript Runtime Engines

* Google V8
* Mozilla SpiderMonkey
* Microsoft Chakra
* Apple JavaScriptCore
  * https://developer.apple.com/documentation/javascriptcore

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