* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?

#### function Person(){}

This is function declaration where you can define what a function is.


#### var person = Person()

Here, this statement is invoking the function Person and setting the variable `person` to whatever the invocation returns.


#### var person = new Person()

The new operator creates an instance of a user-defined object type or of one of the built-in object types that has a constructor function.


##### Example:

function createCar(make) { <br/>
	&nbsp;&nbsp;&nbsp; this.make = make; <br/>
	&nbsp;&nbsp;&nbsp; return 'The make of this car is ' + this.make; <br/>
} <br/>


var invocation = createCar('toyota');  // 'The make of this car is toyota' <br/>
var instance = new createCar('toyota');  // createCar { make: 'toyota' }