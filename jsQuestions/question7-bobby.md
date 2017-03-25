* What is a closure, and how/why would you use one?

A `closure` is an inner function that has access to the outer (enclosing) function’s variables—scope chain. The closure has three scope chains: it has access to its own `local` scope (variables defined between its curly brackets), it has access to the `outer function’s` variables, and it has access to the 'global' variables.

The inner function has access not only to the outer function’s variables, but also to the outer function’s parameters. Note that the inner function cannot call the outer function’s arguments object, however, even though it can call the outer function’s parameters directly.

You create a closure by adding a function inside another function.

##### Example:

const showName = (firstName, lastName) => {<br/>
&nbsp;&nbsp;&nbsp;&nbsp;	var nameIntro = 'My name is';<br/>
&nbsp;&nbsp;&nbsp;&nbsp;	const makeFullName = () => ``${nameIntro} ${firstName} ${lastName}``;<br/>
&nbsp;&nbsp;&nbsp;&nbsp;	return makeFullName();<br/>
}<br/>

showName('Bobby', 'Phan'); //My name is Bobby Phan