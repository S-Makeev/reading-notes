# Readings: In memory storage

- What is a ‘call’?

Call is a command that tells a computer to execute a function.

- How many ‘calls’ can happen at once?

It depends on namy factors, but in modern languages and hardware we can handle multiple calls. 

- What does LIFO mean?

Last in first out - this is the order in which data is being pushed into stack.

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

 ` function firstFunction(){
`  console.log("Hello from firstFunction");
`}
`
`function secondFunction(){
`  firstFunction();
`  console.log("The end from secondFunction");
`}
`
`secondFunction(); `

- at causes a Stack Overflow?

Whenever callstack exceeds available memory that's been alocated to it. 


- What is a ‘reference error’?
- 
 This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

- What is a ‘syntax error’?

This occurs when you have something that cannot be parsed in terms of syntax

- What is a ‘range error’?

Happens when we try to manipulate an object with a certain lengths but give it incorrect lenght.

- What is a ‘type error’?

This type of errors happens when the type we are trying to use or access are incompatible

- What is a breakpoint?

It's a debugging tool to stop execution of code on a specific line.

- What does the word ‘debugger’ do in your code?

It's a tool that helps with finding and fixing bugs. 
