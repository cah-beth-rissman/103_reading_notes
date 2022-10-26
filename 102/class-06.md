# Class 06 Notes

## Dynamic Web Pages with JavaScript

### 3 major parts of JavaScript

1. The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.

2. The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.

3. The server API (or just API) provided by Node.js or one of the other server-side systems.

### More about JS

+ Any text editor can be used
+ Add a line item to HTML file to include the external Js file
> In order to do that we add the <script> opening and </script> closing tags. Between the two we write our JavaScript code.

### Input Output

+ alert("Hello World");
+ document.write("<h1>Hello World</h1>");
+ console.log("Hello World");

### Prompt

+ var name = prompt("Your name:", "");
+ var name = prompt("Please correct your e-mail address:", "foo@bar.co");

### Confirm

+ if (confirm("Shall I print Hello World?")) {
    document.write("Hello World");
} else {
    document.write("OK, I won't print it.");

### Functions

+ 'function' keyword followed by the name of the new function
+ Then list the parameters in parentheses and then a block of expressions in curly braces 
+ Functions are declared but only executed once called or invoked
+ Functions can declare a value and assign the value to a name variable
