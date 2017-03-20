# Explain how prototypal inheritance works

Prototypical inheritance is used when you want two objects to have all the same properties but you want to save memory or avoid code duplication.

To achieve this, you can make one object behave as if it has all the same properties of the other object, by delegating it's failed property lookup to the other object at lookup time.

## Example: 
var gold = {a:1, b: 2};<br/>
//gold.a === 1<br/>
//gold.b === 2<br/>

var blue = extend({}, gold);<br/>
blue.b = 3;<br/>
//blue.b === 3<br/>
//blue.a === 1<br/>
//blue.c === undefined