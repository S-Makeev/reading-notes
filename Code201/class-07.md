# Read: Class 07


**-Explain why we need domain modeling.**

We need domain modeling to solve problems, as it's the process that involved creating a models that include various entities, attributes, behaviours and contraints that a specific problem would have. Domain model that's communicated clearly and precisely, helps understanding, maintaing and solving code related problkems.


**-Why should tables not be used for page layouts?**

We shouldn't use tables as they reduce accessibility for visually impaired users. It creates to many tags, so maintaining and adjusting such design would be extremely difficult. Finally, they are not responsive, so they adjust only by the size of their content.

**-List and describe 3 different semantic HTML elements used in an HTML `<table>`.**

'<td>' creates a  container inside tables' cell. '<tr>' element creates subsequent rows for us to place content in. '<th>'element defines the header row, which is always going to be rendered as a top row.
  
  
**-What is a constructor and what are some advantages to using it?**

Constructor is a collection of object literals and methods, that could be called somewhere in the code. It makes the process of creating various entities with similar properties much easier and helps reducing the code base, and that makes it more managable to maintain. 

  
**-How does the term this differ when used in an object literal versus when used in a constructor?**
  
`this` in object literals referes to properties that are within the object, while `this` in a constructor also refers to objects that are going to be created by default and passed into constructor from the ouside.
  
  
**- Explain prototypes and inheritance via an analogy from your previous work experience**
  
Whenever I had a client who'd sign up for a product, I could've used a form that would serve as template that's going to automatically gather their unique data only, such as name, address, product they are buying etc, instead of typing this information manually all over again for each instance of a new client. 
