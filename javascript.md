# Explain event delegation

Event delegation refers to the process of using event propagation (bubbling) to handle events at a higher level in the DOM than the element on which the event originated. It allows us to attach a single event listener for elements that exist now or in the future.

# What’s a typical use case for anonymous functions?

Since Anonymous Functions are function expressions rather than the regular function declaration which are statements. Function expressions are more flexible. We can assign functions to variables, object properties, pass them as arguments to other functions, and even write a simple one line code enclosed in an anonymous functions.
Example:

var squaredArray = inputArray.map(function(x) { return x \ x; });

With ES6 syntax this becomes even more concise.

var squaredArray = inputArray.map(x => x \_ x);

Another typical example would be an anonymous function used by popular frameworks used as IIFE (Immediate Invoked Function Expression).

(function() { })();

# What’s the difference between a variable that is: null, undefined or undeclared? How would you go about checking for any of these states?

Undefined is a variable that has been declared but no value exists and is a type of itself ‘undefined’.

Null variables exist and have the value of null assigned to them.

We use ‘console.log();’ and ‘type of’ to check if a variable is undefined or null.

Undeclared variables don’t even exist. A variable is undeclared when it does not use the var keyword. It gets created on the global object (that is, the window), thus it operates in a different space as the declared variables. This will not work in strict mode,it will throw an error.
