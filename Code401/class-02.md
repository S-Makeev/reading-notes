# Readings: Testing and Modules

**What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?**

The main principles of TDD include the initial design of the tests that could help with the later design of the code. Inside the tests themselves, we have the Arrange, Act and Assert principle. The next step is the Cycle which is divided into 3 steps: write a test to fail, write a feature 

 

**Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code**
It's a special global  variable, which if declared within a module, can be used as a filter to contain some of the information exclusive to said module.

It's used in situation whenever a module is being exported and some of the original information (function calls, for example) is not needed in a file to which a module is being exported to. 

 

**Describe the concept of recursion in Python.**
Recursion is when a function call itself N number of times in order to reach a desired output. It's important to always keep in mind that condition that stops recursion must be present. 

 

**What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.**
Module's content is being accessed with import statement. Essentially, a module could be just a file that contains some functionality that can be borrowed from.

Package is a collection of modules where each module is hierarchal structured that helps to avoid collision between global variable names. 
