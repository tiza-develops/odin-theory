1. What are the eight data types in JavaScript?
> ```javascript
>     let number = 5.14;
>     let bigint = 2**54;
>     let string = "string";
>     let boolean = true; //or false
>     let null = null; //only this possible value
>     let undefined; //doesn't have a type
>     const symbol = Symbol("foo");
>     let object = {"multiple", "values"};
> ```
2. Which data type is NOT primitive?
> `object`
3. What is the relationship between null and undefined?
> Both assign an empty byte to the variable
4. What is the difference between single, double, and backtick quotes for strings?
> Single and double quotes are the same; while bactick quotes allow to embed javascript and templating over multiple lines
5. What is the term for joining strings together?
> Concatenation
6. Which type of quote lets you embed variables/expressions in a string?
> Backtick
7. How do you embed variables/expressions in a string?
```javascript
    let name = "nick";
    let greeting = `Hello ${name}`;
```
8. How do you use escape characters in a string?
```javascript
    > `"text\(escaped sequence\)"`
```
9. What is the difference between the slice/substring string methods?
> The difference is that start and end values less than 0 are treated as 0 in `substring()`
10. What are the three logical operators, and what do they stand for?
> `||` OR, `&&` AND, `!` NOT
11. What are the comparison operators?
> `<` less than, `>` bigger than 
> `>=` bigger or equal than `<=` less or equal than
> `!==` not the same
12. What are truthy and falsy values?
> Types that get converted to `true` or `false` respectively
13. What are the falsy values in JavaScript?
> `0`, `null`, `undefined` and `NaN`
14. What are conditionals?
> Statements that evaluate the truth value of an expression and execute (or not) a piece of code accordingly
15. What is the syntax for an if/else conditional?
> ```javascript
>     for (condition) {
>         code;
>     } else {
>         code;
>     }
> ```
16. What is the syntax for a switch statement?
> ```javascript
>     switch (expression) {
>       case choice1:
>         // run this code
>         break;
> 
>       case choice2:
>         // run this code instead
>         break;
> 
>       // include as many cases as you like
> 
>       default:
>         // actually, just run this code
>         break;
>     }
> ```
17. What is the syntax for a ternary operator?
> ```javascript
>     condition ? run this code : run this code instead
> ```
18. What is nesting?
> Putting a loop or conditional inside of another
