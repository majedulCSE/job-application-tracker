### Answers to Questions

### Questions 1. What is the difference between getElementById, getElementByClassName, and querySelector / querySelectorAll?
### Answer 1:
"getElementById" select one element by ID. 
"getElementByClassName" selects multiple elements by class and returns a live HTML collection. 
"querySelector" selects the first element using a CSS selector.
"querySelectorAll" select all matching elements using CSS selector.

### Questions 2. How do You create and insert a new element into the DOM?
#### Answer 2:
Create a new element with "document.createElement()", set its content or attributes, then insert it into the DOM using "appendChild()" or "insertBefore()".

### Questions 3. What is the Event Bubbling? And how does it work?
#### Answer 3:
Event bubbling is when an event starts on the target element and then moves upward through its parent elements in the DOM.

### Questions 4. What is Event Delegation in JavaScript? Why is it useful?
### Answer 4:
Event delegation uses a single event listener on a parent element to handle events from child elements, improving performance and supporting dynamic content.

### Questions 5. What is difference between preventDefault() and stopPropagation() methods?
### Answer 5:
"preventDefault()" stops the browser’s default action, while "stopPropagation()" stops the event from propagating through the DOM.
