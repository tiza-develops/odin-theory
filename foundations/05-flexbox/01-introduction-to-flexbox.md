1. What’s the difference between a flex container and a flex item?
> Flex containers dispose a layout on top of its children
> Flex items are forced onto a layout by its parents
2. How do you create a flex item?
> There are two ways: 
> ```html
> <div>some parent
>     <p>some children</p>
> </div>
> ```
> and in css:
> ```css
> div {
>     display: flex;
> }
> ```
> and the children will automatically be a flex item
> 
> However, if the elements don't have such a hierarchic relationship we can do this:
> ```css
> container {
>     display: flex;
> }
> item {
>     flex: 1;
> }
> ```
