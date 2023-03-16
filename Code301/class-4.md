## Readings: React and Forms

- What is a ‘Controlled Component’?

An input form element whose value is controlled by React in that makes React state a single place of truth is called a “controlled component”. 

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

It's generally better to get the updated state right away, as we can check whether the responce is valid and of expected type. 

- How do we target what the user is entering if we have an event handler on an input field?

we can use: `handleChange(event) {
    this.setState({value: event.target.value});
  }`
  event.target.value specifically, so that we are tracking the updated input. 
