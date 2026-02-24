1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

ans:
* getElementById selects a single element by its unique ID.
* getElementsByClassName selects all elements with a specific class.
* querySelector select a first element that matches a css selector.
* querySelectorAll selects all ekements matching a css selector .


2. How do you create and insert a new element into the DOM?
ans
* Create a new element using document.createElment.Set its content or attributes.Insert it into the DOM using appendChiild or insertBefore.


3. What is Event Bubbling? And how does it work?

ans:
* Event Bubbling is when you click a child element , the event also goes up to its parents.Like- child-parent-grandparent automatically unless i stop it 


4. What is Event Delegation in JavaScript? Why is it useful?

ans:
* Event Delegateion means puttting one event listener on a parent to handle events for all its children.It is useful because it saves memory and one listener controls many children



5. What is the difference between preventDefault() and stopPropagation() methods?

ans:
* preventDefault() stops the browser's default action 
* stopPropagation() stops the event from going up to parent elements