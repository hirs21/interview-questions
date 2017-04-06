Explain "hoisting".

In Javascript, variable declarations are "hoisted" to the top of the current scope. Variable assignments, however, are not.

Remember: when you declare a variable in JavaScript (using "var"), that variable declaration is "hoisted" to the top of the current scope—meaning the top of the current function or the top of the script if the variable isn't in a function.

Hoisting can cause unexpected behavior, so a good way to keep things clear is to always declare your variables at the top of the scope.