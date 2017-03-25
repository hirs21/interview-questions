* What's the difference between a variable that is: `null`, `undefined` or undeclared?

##### Null
Null is a variable that is defined to have a null value<br/>

var nullVariable = null; // null<br/>
typeof nullVariable; // "object"<br/>

##### Undefined
A variable that does not have a value assigned to it or not defined.</br>
Note: If you call a variable/function that has not yet been created, the parser will give you a not defined error</br>

var undefinedVariable; // undefined<br/>
typeof undefinedVariable; // "undefined"<br/>

##### Undeclared
A variable is undeclared when you don't declare it with keywords such as var, let, or const. This will cause it to be created on the global object or window.<br/>

undeclaredVariable = 1; // 1<br/>
typeof undeclaredVariable; // undefined</br>

###### Preventing use of undeclared variables
One way to prevent use of undeclared variables is to use strict mode<br/>

###### Why Strict Mode?
* Strict mode makes it easier to write "secure" JavaScript.
* Strict mode changes previously accepted "bad syntax" into real errors.
* As an example, in normal JavaScript, mistyping a variable name creates a new global variable. In strict mode, this will throw an error, making it impossible to accidentally create a global variable.
* In normal JavaScript, a developer will not receive any error feedback assigning values to non-writable properties.
* In strict mode, any assignment to a non-writable property, a getter-only property, a non-existing property, a non-existing variable, or a non-existing object, will throw an error.

'use strict'
undeclaredVariable = 1; // Throws error (ReferenceError: undeclared is not defined)
