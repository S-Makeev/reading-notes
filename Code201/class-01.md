### Reading assignments 


- Compose a short poem describing how HTTP sends data between computers.

  HTTP - "Hypertext Transfer Protocol" structures requests and responses of our requests over the net, while TCP - "Transmission Control Protocol" manages data transportation and establishes communication between a client and a server. 
When we access a specific address from a browser, HTTP commands to open a TCP channel with that server, through which our browser will send a HTTP request to send that website back to our browser. 

- Describe how HTML, CSS, and JS files are “parsed” in the browser.

  Browser parses HTML first, where it looks for any elements (<link>) that point to external CSS and (<script>) JS elements.
  When such elements are found, the client sends its request back to the server to retrieve <link> and <script> elements and    then parses them. Then, from the information that was parsed - client creates an outlay for HTML, CSS and JS content, then compiles and executes JS. Finally, the client builds the DOM (Document Object Model) and applies styles from CSSOM (CSS Object Model) and executes JS. At this point - the visual representation of a page is applied with its functionality and content. 
  
