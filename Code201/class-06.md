# Reading

**-How would you describe an object to a non-technical friend you grew up with?**

An object is a kind of entity, that has certain parameters and characteristics. For example, a car is an object, that has parameters, such as color, make, model. It has wheels, doors and so on. 

**-What are some advantages to creating object literals?**

The main advantage is the ability to wrap some logic or multiple properties into one object, which makes code much more flexible, maintainable and helps avoiding "spaghetti code".


**-How do objects differ from arrays?**

Arrays can be accessed by index, while object can be accessed by strings or symbols. Also, order in the array is indexed, while order inside the object is flexible.

**-Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**

If an object property name is held in a variable,then we must use bracket notation.


**-Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?**

`This` keyword referes to the current object the code is being written inside, so in this code, `this` refers to name and age properties. 
The main advantage is that when we have multiple object literals, it helps to use the same method on every created object.


```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```
**-What is DOM?**

>The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page. A web page is a document that can be either displayed in the browser window or as the HTML source. In both cases, it is the same document but the Document Object Model (DOM) representation allows it to be manipulated. As an object-oriented representation of the web page, it can be modified with a scripting language such as JavaScript.

**-Briefly describe the relationship between the DOM and JavaScript.**

