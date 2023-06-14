# FileIO & Exceptions

**What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?**

Whenever a program's lifecycle doesn't end and it retains allocated resources, this is called memory leak. With statement helps with control or cleanup of allocated resources.
It creates a runtime context which allows to run a group of statements under the control of a context manager. 


**Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.**


read() method reads the entire file, while readline() prints the number of characters and lines that were passed into it. Essentialy readline(10) will produce 10 lines of text where each line is going to be no longer than 10 characters. 


**Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? 
Provide a simple example.**


