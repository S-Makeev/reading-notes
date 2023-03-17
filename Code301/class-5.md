## Readings: Putting it all together

- What is the single responsibility principle and how does it apply to components?

It means that one piece of code should be responsible for once thing. In this case, a component should be responsible for showing one element.

- What does it mean to build a ‘static’ version of your application?

Static means that it's not responsive - there's no way for a user to interact with information (CRUD).

- Once you have a static application, what do you need to add?

We need to identify the minimal representation of UI state.

- What are the three questions you can ask to determine if something is state?

`Does it remain unchanged over time? If so, it isn’t state.
Is it passed in from a parent via props? If so, it isn’t state.
Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!`

- How can you identify where state needs to live?

`Often, you can put the state directly into their common parent.
You can also put the state into some component above their common parent.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.`

- What is a “higher-order function”?

`Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.`

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

it explicitly returns a variable with value grater than passed `n`.

- Explain how either map or reduce operates, with regards to higher-order functions.

Reduce is a high order function that reduces a collection of data to a single element. It continually calls itself with the result from previous reduction untill it goes through the whole element and then returns single value.
