* What is `"use strict";`? what are the advantages and disadvantages to using it?

Putting `use strict;` at the top of your code or function causes your JavaScript to be evaluated in `strict mode`. Strict mode throws more errors and disables some features in order to make your code more robust, readable, and accurate.

#### Advantages:
* Strict mode makes it easier to write "secure" JavaScript.
* Strict mode changes previously accepted "bad syntax" into real errors.
* As an example, in normal JavaScript, mistyping a variable name creates a new global variable. In strict mode, this will throw an error, making it impossible to accidentally create a global variable.
* In normal JavaScript, a developer will not receive any error feedback assigning values to non-writable properties.
* In strict mode, any assignment to a non-writable property, a getter-only property, a non-existing property, a non-existing variable, or a non-existing object, will throw an error

#### Disadvantages:
* Mixed strict and normal modes could cause problems. If a developer used a library that was in strict mode but the developer was used to working in normal mode, they might call some actions on the library that wouldn't work as expected
* Strict mode stops you from doing certain things. Although it is generally thought you shouldn't do these things in the first place, some developers don't like constraint and want to use all features of a language.