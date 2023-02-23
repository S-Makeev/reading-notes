# Readings

**-Why would a developer use local storage for a web application?**
The HTTP is stateless, therefore if an application is closed, all inteface data will be reset. To combat that, we need to use local storage on users' computer.  

**-What information should not be stored in local storage?**
We should never store any security-related or sensitive information about user. 

**-Local storage can store what type of data? How would you convert it to that type before storing?**
It can only work with string data type, so in order to be able to store data locally, we need to use methods JSON.stringify() and JSON.parse().


