## Readings: Passing Functions as Props

- What does .map() return?

It returns a new array with the result.

- If I want to loop through an array and display each value in JSX, how do I do that in React?

We can use map() method with a key prop and return a list of new elements 

- Each list item needs a unique **key**.

- What is the purpose of a key?

It serves as an ID for items, in order to track when they are changed, removed, addded.

- What is the spread operator?

`The spread (...) syntax allows an iterable, such as an array or string, to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected`

- List 4 things that the spread operator can do

It can concatinate an array, copy an array, merge objects, pass an argument. 

- Give an example of using the spread operator to combine two arrays.

We can combine two arrays this way: [...newArr, ...oldArr];

- Give an example of using the spread operator to add a new item to an array.

To add a new item, we can use [...oldArr, ...newItem];

- Give an example of using the spread operator to combine two objects into one.

To combine two objects, we can simply: [...obj1, ... obj2];








