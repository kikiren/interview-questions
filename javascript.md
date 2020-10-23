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
