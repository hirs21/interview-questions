* Explain how `this` works in JavaScript

The `this` variable is set up by the JavaScript engine in the creation of the execution context. It allows shortcut access to an object depending on how the function is invoked. In the browser, `this` in the global scope is the `window` object.

As mentioned before, the `this` binding depends on how the function was called. For functions that are methods on an object, called in an example such as `myObj.myFunc()`, the JavaScript engine will set up the `this` variable to be `myObj`.

There are many gotchas when the `this` variable is assigned something unexpected and two common ways of dealing with this is to use `bind` or `apply` as well as creating a variable outside of the function to be invoked with the assignment of the desired `this` to the context. This is a handy way to use a closure.
