* What's the difference between `.call` and `.apply`?

The difference between call and apply is that `call` requires parameters be listed explicitly while `apply` lets you invoke the function with arguments as an array.<br/>

A useful mneumonic is A is for array and C is for comma.


##### Example:

theFunction.apply(valueForThis, arrayOfArgs)<br/>

theFunction.call(valueForThis, arg1, arg2, ...)