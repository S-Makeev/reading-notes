# Readings: Functional Programming

- What is functional programming?
  
It's is an approach to software development that uses pure functions to create maintainable software.
 
  
- What is a pure function and how do we know if something is a pure function?
  
  
A function can be called pure if it returns the same output given the same input every time you call it, doesn't consume or modify other resources internally, and doesn't change its inputs.  
  
  
- What are the benefits of a pure function?

  Because it doesn't modify the global state, it uses less memory and wors faster than regular functions.
  
- What is immutability?
  
  When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
  
  `pure functions + immutable data = referential transparency`

-What is a module?


Separate js file to store code with its own functionality

- What does the word ‘require’ do?

Reads a JavaScript file, executes it, and then proceeds to return the export object

- How do we bring another module into the file the we are working in?

We need to import that module, therefore we'll be using `require` keyword.

- What do we have to do to make a module available?

We neeed to specity through `module.exports =` what part of the module we need to have available.





