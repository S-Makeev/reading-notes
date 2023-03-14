## Readings: State and Props

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render happens before the ‘componentDidMount’.

- What is the very first thing to happen in the lifecycle of React?

The first thing that's happening is Mounting with the call of the constructor. 

 - Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

constructor, render, componendDidMount, React Updates, ComponentWIllUnmount

- What does componentDidMount do?

It's used to setup access to the DOM with event listeners, API calls etc.

-What types of things can you pass in the props?

Since it works like a function, we'll pass data, callbackfunctions, we can also pass events or css styles.

- What is the big difference between props and state?

State is handled inside the component and can be updated inside of it, while props are hanlded outside and must be updated from the outside. 

- When do we re-render our application?

When we change the state - it's going to re-render that part of the application. 

- What are some examples of things that we could store in state?

We can store user input, information inside forms, that need to be updated dynamically.

