* Explain `Function.prototype.bind`

Bind creates a new function that will have this set to the first parameter passed to bind().

Here's an example that shows how to use bind to pass a member method around that has the correct this:


#### Example
```
var Button = function(content) {
   this.content = content;
};

Button.prototype.click = function() {
   console.log(this.content + ' clicked');
}

var myButton = new Button('OK');
myButton.click(); // prints out 'OK clicked'

var looseClick = myButton.click;
looseClick(); // prints out 'undefined clicked'

var boundClick = myButton.click.bind(myButton);
boundClick(); // prints out 'OK clicked'
```