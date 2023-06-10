Live at https://amrittttt.github.io/Task2codeclause/

--  Use of Dollar Sign($) in JS

1. Using the $ in the jQuery Library
One of the most well-known uses of the dollar sign in JavaScript is with the jQuery library.

In jQuery, the dollar sign is used as a shorthand alias for the jQuery object. jQuery is a powerful JavaScript library that simplifies DOM manipulation and provides a wide range of utility functions for web development.

For example, you may see code like this:

// Using the $ alias to select elements with jQuery
$('#myElement').addClass('active');
In this example, $ is used as a shorthand for the jQuery object, which allows you to select an element with the ID myElement and add the CSS class active to it.

2. Using the $ in Template Literals
In addition to these use cases, the dollar sign is also used in template literals. This was introduced in ECMAScript 6 (ES6) for more convenient string interpolation and multiline strings in JavaScript.

Template literals are enclosed in backticks (`) instead of single or double quotes. They allow you to embed expressions directly within the string using placeholders, denoted by ${expression}. The dollar sign followed by curly braces ${} is used to evaluate and embed expressions dynamically in template literals.

const name = 'John Doe';
const age = 20;

// Using template literals for string interpolation
console.log(`My name is ${name} and I'm ${age} years old.`);
In this example, the expressions ${name} and ${age} are evaluated and replaced with their corresponding values in the resulting string. This allows for easy and readable string concatenation with variables.

$ is just a shortcut for jQuery. The idea is that everything is done with the one global symbol (since the global namespaces is ridiculously crowded), jQuery, but you can use $ (because it's shorter) if you like:

// These are the same barring your using noConflict (more below)
var divs = $("div");       // Find all divs
var divs = jQuery("div");  // Also find all divs, because
console.log($ === jQuery); // "true"

