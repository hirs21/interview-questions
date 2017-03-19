*Explain event delegation

Event delegation allows you to add event listeners to the parent element rather than specific nodes. For example,
if we didn't have event delegation and we wanted to add an event listener to <li> elements in a <ul>, we would have
to add an event listener on every single <li> element which could be costly in terms of slowing down our application
by having too many unneccesary click events. What we could do instead is use event delegation and put a click event
on the parent element, the <ul>, and listen for click events in <li> elements instead. This reminded me of how you
can select nested classes and ids in CSS (I believe it's called combinators?). This way you only have to create
one event listener.

jQuery ex:
  $thisElement.on('click', 'li', function() {
    console.log('click on li elements within thisElement');
  });