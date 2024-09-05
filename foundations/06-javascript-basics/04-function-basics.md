1. What are functions useful for?
> To avoid repeating oneself from writing the same code over and over again, thus reducing errors, bugs and making life easier
2. How do you invoke a function?
> ```javascript
>     function greeting() {
>         console.log("Hello World");
>     }
>     greeting();
>     function add(a,b) {
>         return a + b;
>     }
>     add(8,4);
> ```
3. What are anonymous functions?
> Functions that don't declare their name
4. What is function scope?
> The level of access to variables and values of a function
5. What are return values?
> The "thing" that functions give out when they have functions with arguments
6. What are arrow functions?
> A abbreviated way of writing javascript functions for instance:
> Instead of writing:
> > ```javascript
> >     function sum(a,b) {
> >         return a + b;
> >     }
> > ```
> You can write:
> > ```javascript
> >     sum = (a,b) => a + b;
> > ```
