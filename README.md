# HiR 21 Front-end Interview Question Repository

Try to answer one question per day and make a PR with your answer.

## Guidelines for this repo

1. Fork this repo to your personal Github account.
2. Choose a question to answer.
3. Make an answer file for the question you answered in the corresponding folder/naming convention: *** generalQuestions/question1-kevin.md ***
  * In this example, Kevin has answered question1 from the General Questions list
4. Answer the question in your newly created file.
5. Edit the README (this file) to link to that answer under the corresponding question.
6. Push your changes to your fork.
7. Make a Pull Request from your fork to this repo.
8. That's it! Let's crush those interviews!

* Remember to follow common Github commit message conventions!

# Front-end Job Interview Questions

This file contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Testing Questions](#testing-questions)
  1. [Performance Questions](#performance-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)

#### General Questions:

1. What did you learn yesterday/this week?
  * [Kevin](generalQuestions/question1-kevin.md)
2. What excites or interests you about coding?
3. What is a recent technical challenge you experienced and how did you solve it?
4. What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
5. Talk about your preferred development environment.
6. Which version control systems are you familiar with?
7. Can you describe your workflow when you create a web page?
8. If you have 5 different stylesheets, how would you best integrate them into the site?
9. Can you describe the difference between progressive enhancement and graceful degradation?
10. How would you optimize a website's assets/resources?
11. How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
12. Name 3 ways to decrease page load (perceived or actual load time).
13. If you jumped on a project and they used tabs and you used spaces, what would you do?
14. Describe how you would create a simple slideshow page.
15. If you could master one technology this year, what would it be?
16. Explain the importance of standards and standards bodies.
17. What is Flash of Unstyled Content? How do you avoid FOUC?
18. Explain what ARIA and screenreaders are, and how to make a website accessible.
19. Explain some of the pros and cons for CSS animations versus JavaScript animations.
20. What does CORS stand for and what issue does it address?

#### HTML Questions:

1. What does a `doctype` do?
  * [Cory](htmlQuestions/question1-cory.md)
  * [Renata](htmlQuestions/question1-renata.md)
2. What's the difference between full standards mode, almost standards mode and quirks mode?
  * [Cory](htmlQuestions/question2-cory.md)
  * [Renata](htmlQuestions/question2-renata.md)
3. What's the difference between HTML and XHTML?
  * [Cory](htmlQuestions/question3-cory.md)
  * [Renata](htmlQuestions/question3-renata.md)
4. Are there any problems with serving pages as `application/xhtml+xml`?
  * [Cory](htmlQuestions/question4-cory.md)
5. How do you serve a page with content in multiple languages?
  * [Cory](htmlQuestions/question5-cory.md)
6. What kind of things must you be wary of when design or developing for multilingual sites?
7. What are `data-` attributes good for?
8. Consider HTML5 as an open web platform. What are the building blocks of HTML5?
9. Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
10. Describe the difference between `<script>`, `<script async>` and `<script defer>`.
11. Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
12. What is progressive rendering?
13. Have you used different HTML templating languages before?

#### CSS Questions:

1. What is the difference between classes and IDs in CSS?
  * [Cory](cssQuestions/question1-cory.md)
2. What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  * [Cory](cssQuestions/question2-cory.md)
3. Describe Floats and how they work.
  * [Cory](cssQuestions/question3-cory.md)
4. Describe z-index and how stacking context is formed.
5. Describe BFC(Block Formatting Context) and how it works.
6. What are the various clearing techniques and which is appropriate for what context?
7. Explain CSS sprites, and how you would implement them on a page or site.
8. What are your favourite image replacement techniques and which do you use when?
9. How would you approach fixing browser-specific styling issues?
10. How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
11. What are the different ways to visually hide content (and make it available only for screen readers)?
12. Have you ever used a grid system, and if so, what do you prefer?
13. Have you used or implemented media queries or mobile specific layouts/CSS?
14. Are you familiar with styling SVG?
15. How do you optimize your webpages for print?
16. What are some of the "gotchas" for writing efficient CSS?
17. What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
18. How would you implement a web design comp that uses non-standard fonts?
19. Explain how a browser determines what elements match a CSS selector.
20. Describe pseudo-elements and discuss what they are used for.
21. Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
22. What does ```* { box-sizing: border-box; }``` do? What are its advantages?
23. List as many values for the display property that you can remember.
24. What's the difference between inline and inline-block?
25. What's the difference between a relative, fixed, absolute and statically positioned element?
26. The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
27. What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
28. Have you played around with the new CSS Flexbox or Grid specs?
29. How is responsive design different from adaptive design?
30. Have you ever worked with retina graphics? If so, when and what techniques did you use?
31. Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?

#### JS Questions:

1. Explain event delegation
  * [Bobby](jsQuestions/question1-bobby.md)
2. Explain how `this` works in JavaScript
  * [Kevin](jsQuestions/question2-kevin.md)
3. Explain how prototypal inheritance works
4. What do you think of AMD vs CommonJS?
5. Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?
  * [Cory](jsQuestions/question5-cory.md)
6. What's the difference between a variable that is: `null`, `undefined` or undeclared?
  * How would you go about checking for any of these states?
7. What is a closure, and how/why would you use one?
8. What's a typical use case for anonymous functions?
9. How do you organize your code? (module pattern, classical inheritance?)
10. What's the difference between host objects and native objects?
11. Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
12. What's the difference between `.call` and `.apply`?
13. Explain `Function.prototype.bind`.
14. When would you use `document.write()`?
15. What's the difference between feature detection, feature inference, and using the UA string?
16. Explain Ajax in as much detail as possible.
17. What are the advantages and disadvantages of using Ajax?
18. Explain how JSONP works (and how it's not really Ajax).
19. Have you ever used JavaScript templating?
  * If so, what libraries have you used?
20. Explain "hoisting".
21. Describe event bubbling.
22. What's the difference between an "attribute" and a "property"?
23. Why is extending built-in JavaScript objects not a good idea?
24. Difference between document load event and document DOMContentLoaded event?
25. What is the difference between `==` and `===`?
26. Explain the same-origin policy with regards to JavaScript.
27. Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
  * [Cory](jsQuestions/question27-cory.md)
28. Why is it called a Ternary expression, what does the word "Ternary" indicate?
29. What is `"use strict";`? what are the advantages and disadvantages to using it?
30. Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
31. Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
32. Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
33. Explain what a single page app is and how to make one SEO-friendly.
34. What is the extent of your experience with Promises and/or their polyfills?
35. What are the pros and cons of using Promises instead of callbacks?
36. What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
37. What tools and techniques do you use debugging JavaScript code?
38. What language constructions do you use for iterating over object properties and array items?
39. Explain the difference between mutable and immutable objects.
  * What is an example of an immutable object in JavaScript?
  * What are the pros and cons of immutability?
  * How can you achieve immutability in your own code?
40. Explain the difference between synchronous and asynchronous functions.
41. What is event loop?
  * What is the difference between call stack and task queue?
42. Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`

#### Testing Questions:

1. What are some advantages/disadvantages to testing your code?
1. What tools would you use to test your code's functionality?
1. What is the difference between a unit test and a functional/integration test?
1. What is the purpose of a code style linting tool?

#### Performance Questions:

1. What tools would you use to find a performance bug in your code?
1. What are some ways you may improve your website's scrolling performance?
1. Explain the difference between layout, painting and compositing.

#### Network Questions:

1. Traditionally, why has it been better to serve site assets from multiple domains?
2. Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
3. What are the differences between Long-Polling, Websockets and Server-Sent Events?
4. Explain the following request and response headers:
  * Diff. between Expires, Date, Age and If-Modified-...
  * Do Not Track
  * Cache-Control
  * Transfer-Encoding
  * ETag
  * X-Frame-Options
5. What are HTTP methods? List all HTTP methods that you know, and explain them.

#### Coding Questions:

1. *Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

2. *Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

3. *Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

4. *Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```

5. *Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

6. *Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

7. *Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

8. *Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

#### Fun Questions:

1. What's a cool project that you've recently worked on?
1. What are some things you like about the developer tools you use?
1. Who inspires you in the front-end community?
1. Do you have any pet projects? What kind?
1. What's your favorite feature of Internet Explorer?
1. How do you like your coffee?


#### Contributors:

HiR 21: For continued learning and software engineering mastery during our 3-month residency. [@kjng](https://github.com/kjng) [@wolnewitz](https://github.com/wolnewitz)

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
