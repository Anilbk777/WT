# ASSIGNMENT-6

# EXPLAIN EVENT BUBBLING AND CAPTURE WITH EXAMPLES
## Event Bubbling
Event bubbling directs an event to its intended target, and works like this: When an object (like a button) is clicked, an event is directed to the object. If an
event handler is set for the object, the event handler is triggered. Then the event bubbles up (like a bubble in water) to the objects parent.</br></br>
For example if we make a spam tag inside which their is a div tag and inside a div tag their is a button then in bubbling if we click on button then first button (child)
will be clicked then div will be clicked then span will be clicked.


## Event Capture
Event capturing is one of two ways to do event propagation in the HTML DOM. In event capturing, an event propagates from the outermost element to the target element.
It is the opposite of event bubbling, where events propagate outwards from the target to the outer elements.</br></br>
For example if we make a spam tag inside which their is a div tag and inside a div tag their is a button then in bubbling if we click on button then first span 
will be clicked then div will be clicked then button will be clicked.
