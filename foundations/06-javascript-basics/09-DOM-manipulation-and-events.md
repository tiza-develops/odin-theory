1. What is the DOM?
> The Document Object Map is the tree that contains all of the **finally rendered** html in a page. So unlike html, which represents what will go in, the DOM contains what will actually be displayed.
2. How do you target the nodes you want to work with?
> If you want to select a single node:
> ```javascript
>     let selector = document.querySelector(<css selector>);
> ```

> However, if you want to select multiple nodes:
> ```javascript
>     let selector = document.querySelectorAll(<css selector>);
> ```
> Will return only a list, **not** the actual nodes. So you will have to: use:
> ```javascript
>     const elements = document.querySelectorAll("<css selector>");
>     elements.forEach(element => {
>         // do something
>     });
> ```
3. How do you create an element in the DOM?
> ```javascript
>     const newThing = document.create("<element html tag>");
> ```
4. How do you add an element to the DOM?
> ```javascript
>     const newThing = document.create("<element html tag>");
>     document.appendChild(newThing)
> ```

5. How do you remove an element from the DOM?
> ```javascript
>     parentNode.removeChild(child)
> ```
6. How can you alter an element in the DOM?
> ```javascript
>     element.style.<cssPropertyWithCapitalNames> = "value";
> ```
7. When adding text to a DOM element, should you use textContent or innerHTML? Why?
> `textContent`, because with `innerHTML` you could inject HTML, creating a horrible data breach
8. Where should you include your JavaScript tag in your HTML file when working with DOM nodes?
> Preferably at the end, so it has access to all of the nodes
9. How do “events” and “listeners” work?
> Events are actions that occur on your webpage, such as mouse-clicks or key-presses. Listeners are bits of javascript that know when such an event happens
10. What are three ways to use events in your code?
> - Add it as inline functions on the html
> ```html
>     <button onclick="alert('Hello World')">Click Me</button>
> ```
> - Set as properties (remember that nodes in js are treated as objects so we can "append" properties on demand
> ```html
>     <!-- the HTML file -->
>     <button id="btn">Click Me</button>
> ```
> ```javascript
>     // the JavaScript file
>     const btn = document.querySelector("#btn");
>     btn.onclick = () => alert("Hello World");
> ```
> - Attach event listeners through the `addEventListener` built-in function
> ```html
>     <!-- the HTML file -->
>     <button id="btn">Click Me Too</button>
> ```
> ```javascript
>     // the JavaScript file
>     const btn = document.querySelector("#btn");
>     btn.addEventListener("<event>", () => {
>         //do something;
>     });
> ```
11. Why are event listeners the preferred way to handle events?
> Because it simplifies the task when we are dealing with multiple nodes (see question 2)
12. What are the benefits of using named functions in your listeners?
> You don't get lost and you can reuse them
13. How do you attach listeners to groups of nodes?
> ```javascript
>     const elements = document.querySelectorAll('.your-selector');
> 
>     elements.forEach(element => {
>       element.addEventListener('event-type', yourEventHandler);
>     });
> ```
14. What is the difference between the return values of querySelector and querySelectorAll?
> `querySelector` returns a node object, while `querySelectorAll` returns a nodelist, which doesn't really behaves as a javascript array
15. What does a “NodeList” contain?
> References to the matches of the selector
16. Explain the difference between “capture” and “bubbling”.

> | Bubbling | Capturing |
> |----------|-----------|
> | When an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestors. | the event goes down to the element |
