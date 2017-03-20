* Explain how prototypal inheritance works

Prototypical inheritance is used when you want two objects to have all the same properties but you want to save memory or avoid code duplication.

To achieve this, you can make one object behave as if it has all the same properties of the other object, by delegating it's failed property lookup to the other object at lookup time.

Example: 
	var gold = {a:1, b: 2}; 
		//gold.a === 1
		//gold.b === 2
	var blue = extend({}, gold);
	blue.b = 3;
		//blue.b === 3
		//blue.a === 1
		//blue.c === undefined