# What is CSS selector specificity and how does it work?

If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out. Think of specificity as a score/rank that determines which style declarations are ultimately applied to an element.

For emample, the universal selector (\*) has low specificity, while ID selectors are highly specific!

# What’s the difference between “resetting” and “normalizing” CSS? Which would you choose, and why?

CSS resets aim to remove all built-in browser styling. Standard elements like H1-6, p, strong, em, et cetera end up looking exactly alike, having no decoration at all. You're then supposed to add all decoration yourself.
Normalize CSS aims to make built-in browser styling consistent across browsers. Elements like H1-6 will appear bold, larger et cetera in a consistent way across browsers. You're then supposed to add only the difference in decoration your design needs.
If your design a) follows common conventions for typography et cetera, and b) Normalize.css works for your target audience, then using Normalize.CSS instead of a CSS reset will make your own CSS smaller and faster to write.
