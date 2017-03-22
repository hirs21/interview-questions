* Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  This will throw a syntax error, because this is a function definition so javascript does not understand how to call the function
* What needs to be changed to properly make it an IIFE?
  You need to wrap the whole thing in parens like this `(foo(){}())` or `(foo(){})()` so that the interpreter knows that it is an expression.
