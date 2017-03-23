* What's the difference between a variable that is: `null`, `undefined` or undeclared?

##### Null
Null is a variable that is defined to have a null value<br/>

var nullVariable = null; // null<br/>
typeof nullVariabl; // "object"<br/>

##### Undefined
A variable that does not have a value assigned to it or not defined.</br>
Note: If you call a variable/function that has not yet been created, the parser will give you a not defined error</br>

var undefinedVariable; // undefined<br/>
typeof undefinedVariable; // "undefined"<br/>

##### Undeclared
A variable is undeclared when you don't declare it with keywords such as var, let, or const. This will cause it to be created on the global object or window.<br/>

undeclaredVariable = 1; // 1<br/>