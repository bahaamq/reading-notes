
## Review, Research, and Discussion

 **Q. Name 3 advantages to Test Driven Development**
- it's a class that designed to be instanciated one time only, so you can't create multi instances of it.

 **Q. Explain how the Singleton pattern can be used with Node modules, specifically with classes.
lets imagine that we have a class called logger that's it's used to log messages using logIt method but with time stamp always .. and this class has an array which saves all messages , cool assume that we are having multiple modules(food,clothes,main) each module import/ require this logger class and create an istance of it , assume that these three modules is built by classes 
lets start with food is a module that has a class food that's constructor take one argument which is food name , and this class use logger class to logger class with the logIt method the food name but with time stamp . logIt also push the message n our case food name to an array that's inisialitized in the constructor called all message , good same all steps with clothes module ,,,, then the  main class required all the three modules and create an instance of each of them ((food,clothes,logger) , as we know the food and clothes is already requiring logger (module )and instinciate an object ,, so this main class decided to log all the messages in the array messages in logs class you remember that was pushed every new message that comes from different modules in our cas food , clothes oops the array is empty ,,, okay wait but food class and clothes both sent it data and we can log the data for each one of them ,, yes that's it we can log it for each one of them by using them since each one of them has it's own instance of class , so wehn we tried to log the all messages array from Main.js the output is empty because the instance logger is belong to main only ! , and for sure we didn't push anything to it thats why ,,,,,,, a solution for this problem can be done by using singleton design pattern , which is basically a pattern that only accepts one instance , no matter how much modules are there it's a shared instance for all new instanciation , so how we can implement it in javascript or one of the way/approaches that we can do to make this possible ? 
see the link above that has explained this with a good example of how to implement it.
https://medium.com/@maheshkumawat_83392/node-js-design-patterns-singleton-pattern-series-1-1e0ab71e3edf




## Definitions
**Router Middleware** : Middleware that's instance of express.Router() 
var router = express.Router()
that can be loaded by using instance name.use in our case **router  router.use() or router.METHOD() by
 so it's as same as application level middleware but to achieve modularity 

https://expressjs.com/en/guide/using-middleware.html#middleware.router

*CRUD / REST MATCHES:*
-   HTTP GET - SELECT/Request
-   HTTP PUT - UPDATE
-   HTTP POST - INSERT/Create
-   HTTP  PATCH

**Mocking is a process used in unit testing when the unit being tested has external dependencies. The purpose of mocking is to isolate and focus on the code being tested and not on the behavior or state of external dependencies. In mocking, the dependencies are replaced by closely controlled replacements objects that simulate the behavior of the real ones. There are three main possible types of replacement objects - fakes, stubs and mocks.* i think an example of it would be a post request that it's main function to add data to database , in mocking you don't really add this data to the connected DB in your application but with something that simulate the 'job of DB*


## Preview
-  Q.  Which 3 things had you heard about previously and now have better clarity on? 
Middlewares , mock testing , design patterns
 -   Q. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Middlewares , mock testing , design patterns. Authentication
Having the ability to answer such a question like this one 
If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it

-- security and Authentication topics will be added asap

Additional Resources : 

https://www.telerik.com/products/mocking/unit-testing.aspx
https://www.youtube.com/watch?v=hUE_j6q0LTQ
