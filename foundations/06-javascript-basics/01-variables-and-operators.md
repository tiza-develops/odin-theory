1. Name the three ways to declare a variable
> ```javascript
>     const varName = "foo";
>     let varName = "bar";
>     var name = "eggs";
> ```
2. Which of the three variable declarations should you avoid and why?
>   `var name = "eggs";`, since it's deprecated
3. What rules should you follow when naming variables?
> It must only contain letters, numbers and the characters `$` and `_`
4. What happens when you add numbers and strings together?
> Everything is treated as a string
5. How does the Modulo (%), or Remainder, operator work?
> It prints the remainder of x/y by long division. So 5%4=1
6. Explain the difference between == and ===.
> `==` forces both values being compared to be the same type, so it performs conversion. While `===` is lazy, comparing value and type
7. When would you receive a NaN result?
> If you try to force an operation on at least one value that is not an integer
8. How do you increment and decrement a number?
> ```javascript
>     let variableIncrement = 0;
>     variableIncrement++;
>     let variableDecrement = 0;
>     variableDecrement--;
> ```
9. Explain the difference between prefixing and postfixing increment/decrement operators.
> The prefix form returns the new value while the postfix form returns the old value (prior to increment/decrement).
10. What is operator precedence and how is it handled in JS?
> It is the order on which (without further specificity or parentheses) operations are done by javascript. And the exact table can be seen in [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_precedence#table)
11. How do you access developer tools and the console?
> `Options > Inspect > Console`
12. How do you log information to the console?
> `Options > Inspect > Console` and type `console.log()` on it
13. What does unary plus operator do to string representations of integers? eg. +”10”
> Nothing
