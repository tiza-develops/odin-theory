1. What is the difference between objects and arrays?
> There are three key differences: 
> - They are valued by pairs, unlike arrays, which are ordered by numbers starting in 0
> - The values inside are intepreted as properties, so instead of `array[0` we can do `object.property`
> - You can create your own methods for your objects!
2. How do you access object properties?
> See the second bullet point of the previous answer
3. How do primitives and object types differ when you assign them to other variables, or pass them into functions?
> Again, two differences, one practical and one technical
> - Primitive values can **only** store single values, object can store multiple values of different types
> - When we assign a variable to an object, it contains a reference, not a copy of the value
4. What is Array.prototype.map() useful for?
> To create a new array with changes to *all* elements, derived from another array
5. What is Array.prototype.filter() useful for?
> Create a new array with only elements that pass a test implemented in a function
6. What is Array.prototype.reduce() useful for?
> Its a function that returns a **single** value from the entire array, you can, for instance sum all of the numbers of an array or do all sorts of crazy things
