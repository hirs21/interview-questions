* Explain `Function.prototype.bind`

Bind creates a new function that will have this set to the first parameter passed to bind().

Here's an example that shows how to use bind to pass a member method around that has the correct this:


var Button = function(content) {<br/>
&nbsp;&nbsp;&nbsp;&nbsp; this.content = content;<br/>
};<br/>

Button.prototype.click = function() {<br/>
&nbsp;&nbsp;&nbsp;&nbsp; console.log(this.content + ' clicked');<br/>
}<br/>

var myButton = new Button('OK');<br/>
myButton.click();<br/>

var looseClick = myButton.click;<br/>
looseClick(); // not bound, 'this' is not myButton - it is the global object<br/>

var boundClick = myButton.click.bind(myButton);<br/>
boundClick(); // bound, 'this' is myButton<br/>