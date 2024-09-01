1. From inside to outside, what is the order of box-model properties?
> Padding, border, margin
2. What does the box-sizing CSS property do?
> To change the box model of the selected element
3. What is the difference between the standard and alternative box model?
> The standard applies dimensions to an object and on top of that adds the desired dimensions of padding and border. Under the alternative model, they are factored in
4. Would you use margin or padding to create more space between 2 elements?
> Margin
5. Would you use margin or padding to create more space between the contents of an element and its border?
> Padding
6. Would you use margin or padding if you wanted two elements to overlap each other?
> Margin
7. How do you set the alternative box model for all of your elements?
> ```css
> * {
>   box-sizing: border-box
> }
> ```
8. How do you center an element horizontally?
> ```css
> selector {
>   margin: 0 auto;
> }
> ```
