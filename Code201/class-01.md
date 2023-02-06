### Reading assignments 
  <hr/>


**- Compose a short poem describing how HTTP sends data between computers.**

  HTTP - "Hypertext Transfer Protocol" structures requests and responses of our requests over the net, while TCP - "Transmission Control Protocol" manages data transportation and establishes communication between a client and a server. 
When we access a specific address from a browser, HTTP commands to open a TCP channel with that server, through which our browser will send a HTTP request to send that website back to our browser.


**- Describe how HTML, CSS, and JS files are “parsed” in the browser.**

  Browser parses HTML first, where it looks for any elements (<link>) that point to external CSS and (<script>) JS elements.
When such elements are found, the client sends its request back to the server to retrieve <link> and <script> elements and    then parses them. Then, from the information that was parsed - client creates an outlay for HTML, CSS and JS content, then    compiles and executes JS. Finally, the client builds the DOM (Document Object Model) and applies styles from CSSOM (CSS Object Model) and executes JS. At this point - the visual representation of a page is applied with its functionality and content.   
  
  
**- How can you find images to add to a Website?**
  
  We can use google licensed images, make a custom request to an artist or
  draw them ourselves by using software for drawing.
  
  
**- How do you create a String vs a Number in JavaScript?**
  
  In order to create a variable, we need to declare a keyword "let" and then give it a name and then, with the "=" symbol assign either a number or a string of characters in double quotation marks. 
  
  
**-  What is a Variable and why are they important in JavaScript?**
  
  Variable is an entry point and a dynamical placeholder for information, that's been captured my computer memory. Without varibales, we'd have no infomration to manipulate.

  
**- What is an HTML attribute?**
  
  Attributes are special marks that don't appear visually, but they refer those marked blocks of information to an element that will alter specified properties of said blocks. 
  
  
**- Describe the Anatomy of an HTML element.**
  
  Element includes an opening tag with some attributes, enclosed text content, and a closing tag.
  
  
**- What is the Difference between "article" and "section" element tags?**
  
  The "article" tag is used to highlight main and/or independent piece of information, while the "section" tag is used to wrap related groups of content. 

  
**- What Elements does a “typical” website include?**
  
  Most common elements of a website are: Links, Paragrapgs, Headings, Lists, Tables, Regions, Images, Buttons.
  
  
**- How does metadata influence Search Engine Optimization?**
  
  Metadata directly influences overall discoverability of a website, as well as how high your website will appear in relevant search. 
  
  
**-How is the "meta" HTML tag used when specifying metadata?**
  
  In most cases, it's used with the "name" (specifies the type of element and type of information) and "content"(specifies actual meta content) attributes.
  
  
  
**- What is the first step to designing a Website?**
  
  To do the project ideation. (What do I want to accomplish, how a website will help reach this goal, what's needed to reach the goal).
  
  
**-  What is the most important question to answer when designing a Website?**
  
  What do I want to accomplish.
  
  
**-  Why should you use an "h1" element over a "span" element to display a top level heading?**
  
  We should use it thus it carries semantic meaning, while "span" only makes it look like top heading and has no value for SEO.
  
  
**- What are the benefits of using semantic tags in our HTML?**
 
  <ul>
<li> Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
    
<li>Screen readers can use it as a signpost to help visually impaired users navigate a page
<li>Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
<li>Suggests to the developer the type of data that will be populated 
<li>Semantic naming mirrors proper custom element/component naming.
 <ul/>
  
 **Source**:https://developer.mozilla.org/en-US/docs/Glossary/Semantics/
  
  
**- Describe 2 things that require JavaScript in the Browser?**
  
  Both HTML and CSS depend upon JavaScript to make an interactive webpage, so that it can be dynamically modified/accessed by a user.
  
  
**- How can you add JavaScript to an HTML document?**
  
  Refer to: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#how_do_you_add_javascript_to_your_page
  
<hr/>

 ## Things I want to know more about
  
  I'd like to know more about TCP protocols and information flow
