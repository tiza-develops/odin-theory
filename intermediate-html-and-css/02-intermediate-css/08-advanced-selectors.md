# Title
1. What is the difference between the child combinator and the descendant combinator?

The descendant combinator will search through all of the HTML tree and select all of the childs, grandchilds, etc that pass the test

2. How does the syntax of pseudo-classes and pseudo-elements differ?

Pseudo-class selectors are prefixed with a single colon and are a different way to target elements that already exist in HTML. Pseudo-elements are prefixed with two colons and are used to target elements that don’t normally exist in the markup. 

3. Do pseudo-classes exist somewhere in HTML? Do pseudo-elements?

 No

4. Name two ways you could select every second child of an element, starting with the first.

```css
    {container} a:nth-child(2)
```
or
```css
    {container} {type}:nth-of-type(2)
```
5. What is the difference between div:first-child and div:last-child? What will each select?

Let's imagine we have this html:

```html
    <div>
        <li>a child</li>
        <li>some child</li>
        <li>last child</li>
    </div>
```
`div:first-child`will select `<li>a child</li>` while `div:last-child` will select `<li>last child</li>`

6. What selector would you use to style a button a user is currently hovering over? How about one that is currently being clicked on?

`:hover` and `:actiive` respectively

7. How could you select all input elements with a type of text?

`input[type=text]`

8. How could you select all classes that begin with thunder?

`[class^= thunder]`
