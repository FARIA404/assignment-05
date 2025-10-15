 1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

 Ans: getElementById() selects only one item from the HTML document only by using one unique ID name.
 getElementsByClassName() selects multiple items from the HTML document which shares the same name. 
 querySelector() selects the first element that matches in CSS.
querySelectorAll() selects all the element that matches in CSS 


2. How do you **create and insert a new element into the DOM**?

In DOM a new element is created by  using "document.createElement(). And on the other hand using "appendChild()" we can insert new elelments.


3. What is **Event Bubbling** and how does it work?

Event Bubbling is when an event happens on an element. Such as "Click". 
Event Bubbbling is handled by the element first and then it is handled by the parent element. 

4. What is **Event Delegation** in JavaScript? Why is it useful?

Event Delegation in JavaScript  is a system where a single event listener is added to a parent element.
It is useful because this avoids adding listeners to multiple child elements only by adding in parent element.

5. What is the difference between **preventDefault() and stopPropagation()** methods?

preventDefault() can be used to stop the browser's default action for an event.
On the other hand stopPropagation() is used to stop the event from bubbling to the parent element.