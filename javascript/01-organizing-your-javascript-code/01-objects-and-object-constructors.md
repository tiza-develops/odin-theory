1. How do you write an object constructor and instantiate the object?
> To create an object constructor:
> ```javascript
>     function newObject(property1, property2) {
>         this.property1 = property1;
>         this.property2 = property2;
> ```
> and to create a new object from this constructor is as simple as:
> ```javascript
>     const object = new newObject("property1", "property2");
> ```
2. What is a prototype and how can it be used?
> It is another object that the original object inherits from, and has access to all of its prototype’s methods and properties
3. What is prototypal inheritance?
> A way to reuse methods of another (previously created object) into  a new one.
4. What are the basic do’s and don’t’s of prototypal inheritance?
> You should do this:
> ```javascript
>     Object.setPrototypeOf(parentObject.prototype, childObject.prototype);
> ```
> But never this:
> ```javascript
>     parentObject.prototype = childObject.prototype;
> ```
5. How does `this` behave in different situations?
- In the global context:
    - It just references the open window of a browser
- In functions:
    - In a traditional function invocation, the `this` keyword 
    - We have already seen how it works on methods
- With arrow functions:
    - It inherits the previous scope by the function
