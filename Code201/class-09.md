# Readings: Forms and JS Events

**-Why are forms so important in web development?**

Forms are extremely important in web dev, as they provide main window of communication between the user and the website.

**-When designing a form, what are some key things to keep in mind when it comes to user experience?**

It's always good to consider what information we absolutely need, in order to minimize the number of requests for user's input.
It's also a good practise to control possible input and set up warnings, so that user won't be able to input wrong data.

**-List 5 form elements and explain their importance.**
>The 'form' element formally defines a form and attributes that determine the form's behavior.
The 'fieldset' element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes. 
The 'label' element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms  
Many assistive technologies will use the 'legend' element as if it is a part of the label of each control inside the corresponding 'fieldset' element.   
'Input' element is used with 'label' element and is used to bond it with the inpud by id.

**-How would you describe events to a non-technical friend?**

Imagine a security camera that sends a signal if it captures motion, for exaple. That signal will be send to a computer which has a list of actions it can take based of a signal. It will either call 911, close all door in a building etc.

**-When using the addEventListener() method, what 2 arguments will you need to provide?**
We'll need to provide 'specific type of event we need to react to and a method that's going to be executed.

**-Describe the event object. Why is the target within the event object useful?**

>inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.

**-What is the difference between event bubbling and event capturing?**

>Event Bubbling − Whenever an event happens on an element, the event handlers will first run on it and then on its parent and finally all the way up to its other ancestors. Event Capturing − It is the reverse of the event bubbling and here the event starts from the parent element and then to its child element

