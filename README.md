#Front-end Job Interview Questions

This file contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)

#### Fun Questions:

##### All

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Do you have any pet projects? What kind?

#### General Questions:

##### All

* If you have 5 different stylesheets, how would you best integrate them into the site?
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
* What did you learn yesterday/this week?
* What excites or interests you about coding?
* If you jumped on a project and they used tabs and you used spaces, what would you do?

#### HTML Questions:

##### All

* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?

#### CSS Questions:

##### Jr

* List as many values for the display property that you can remember.

##### Mid

* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* What's the difference between inline and inline-block?
* What's the difference between a relative, fixed, absolute and statically positioned element?

##### Sr

* Any familiarity with styling SVG?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?

##### All

* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with Flexbox? What do you think? Why?
* What is "responsive design?"

#### JS Questions:

##### Jr

* What is a closure, and how/why would you use one?
* What's a typical use case for anonymous functions?
* Explain "hoisting".
* Why is extending built in JavaScript objects not a good idea?
* What is the Ternary operator and can you show me an example of a good use case for it?
* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

##### Mid

* How do you go about testing your JavaScript?
* Explain `Function.prototype.bind`.
* Describe event bubbling.
* What is the difference between `==` and `===`?
* What is `"use strict";`? what are the advantages and disadvantages to using it?
* What is the extent of your experience with Promises?

##### Sr

* Explain event delegation

##### All

* Explain how prototypal inheritance works
* Explain how `this` works in JavaScript
* What's the difference between `.call` and `.apply`?
* What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  * How would you go about checking for any of these states?

#### Network Questions:

##### All

* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.

#### Coding Questions:

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the value of `window.foo`?*
```javascript
(window.foo || (window.foo = "bar"));
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What might be the cause of a subtle bug in this code?*
```javascript
if (foo) {
  console.log('The child is ' + foo + ' years old.');
} else {
  console.log('Age of the child is unknown.');
}
```

#### Contributors:

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
