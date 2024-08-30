1. What is the syntax for class and ID selectors?
> ```css
> .class-name {
>     rule: value;
> }
> #id-name {
>     rule: value;
> }
> ```
2. How would you apply a single rule to two different selectors?
selector1, selector2 {
> ```css
> selector1, selector2 {
>   rule: value;
> }
> ```
3. Given an element that has an id of title and a class of primary, how would you use both attributes for a single rule?
> ```css
> #title.primary {
>     rule: value;
> }
> ```
4. What does the descendant combinator do?
> It selects only over the children of an already selected element
5. What are the names of the three ways to add CSS to HTML?
> - Inline
> - Internal
> - External
6. What are the main differences between the three ways of adding CSS to HTML?

> | Inline | Internal | External |
> |--------|----------|----------|
> | The CSS goes inside the opening tag | The CSS is wrapped around a `<style>` tag on the `<head>` part of the html file | It is linked |
> | It only affects the html element it is on | It only affects the html file it is on | It can affect any part of any html file |


