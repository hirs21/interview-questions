* What's a typical use case for anonymous functions?

Anonymous functions are used for the reasons of: a) Code brevity. It often makes sense to use anonymous functions calls in `callbacks and event handlers`; b) `Scope management`. Anonymous functions can be used to create temporary/private scope; c) Anonymous function are often handy in `closures and recursions`.


##### Examples:

var anonFunction1 = function() {
&nbsp;&nbsp;&nbsp;  return 'this is an anonymous function assigned to a variable';
}


var object = {
&nbsp;&nbsp;&nbsp;   anonFunction2: function(){
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;        return 'this is an anonymous function inside an object';
&nbsp;&nbsp;&nbsp;    }
};
