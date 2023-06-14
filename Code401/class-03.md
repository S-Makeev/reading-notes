# FileIO & Exceptions

**What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?**

Whenever a program's lifecycle doesn't end and it retains allocated resources, this is called memory leak. With statement helps with control or cleanup of allocated resources.
It creates a runtime context which allows to run a group of statements under the control of a context manager. 


**Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.**


read() method reads the entire file, while readline() prints the number of characters and lines that were passed into it. Essentialy readline(10) will produce 10 lines of text where each line is going to be no longer than 10 characters. 


**Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? 
Provide a simple example.**

Exception handling is saparation of error handling code from the base code. Exceptions are errors that happen during execution, but syntactically correct.
‘try’, ‘except’, and ‘finally:

**try**: This is where we expect an error might happen. try is followed by one or multiple expect or finally blocks. If exception happens, then the execution is passed right into the except block, ignoring everything else.

**except**: this is where the specific exception is being handled. If an exception matches the anticipated error, its code is executed. If not, the execution will move on to try clause or the program will be terminated.

**finally**: This is an optional block that activates regardless of exception. It's executed after except clause. It's used mostly for cleanups. (closing files and releasing resources)

      try:
      result = 1 * 0
      except zeroMultiplication:
      print("Error: Useless operation")
      finally:
      print("Finally clause")  
