
## Review, Research, and Discussion

 ** Q. Name 3 advantages to Test Driven Development**
- Code flexibility and easier maintenance based on researches
- when you are writing test , indiurectly you will imagine how to write your code to pass tests
- as there is a test for each unit and it's clear for which function it belongs , maybe it makes your code more easier to understand and faster so someone can see the expectation of this function  then understand the function faster,
 - Self documenting_ tests
**Q. In what case would you need to use  `beforeEach()`  or  `afterEach()`  in a test suite?**
- *beforeeach* ,, if we imagine a simple calculater that has(-,+,/,*) do each process ,it's a good way to use beforeeach in every operation so making sure that functions are working, rather than say the system is down at the end

- *aftereach* ,, set up preconditions and clean up after your tests (reset)


**Q. What is one downside of Test Driven Development**
If we focus  on actions and work not results example it could be a slow process. 
**Q.ES6 classes vs es5 classes(constructor function)**
_classes are just syntactical sugar over ES5 code._
especially in inheritance as "With classes, we get no inheritance by default and we get a pure object assigned to the inner  `__proto__`  property of the object’s prototype.

**Q.WHY REST?**
#### No State
As we will see in the next section (Principles of REST), one of the core principles of REST is that it's stateless on the server-side. Therefore each request will be processed independently from the previous ones.

#### Faster Data Interchange Format
RESTful APIs typically use JSON as the data interchange format. JSON is much more compact and smaller in size compared to XML. It can also be parsed faster than XML. ([source](http://ijcsn.org/IJCSN-2014/3-4/JSON-vs-XML-A-Comparative-Performance-Analysis-of-Data-Exchange-Formats.pdf))



## Definitions
**Functional programming** (often abbreviated FP) is the process of building software by composing **pure functions**, avoiding **shared state,**  **mutable data,** and **side-effects**. Functional programming is **declarative** rather than **imperative**, and application state flows through pure functions. Contrast with object oriented programming, where application state is usually shared and colocated with methods in objects

**OOP** : software engineering model that contain data (attr), and fileds(methods) of it's self
**class**: is a container of attrs,fileds , used to by objects to get benifi of these things.
**Super**: JS keyword used in classes to call the constructor of the parent class 
**this**:`this`  points to a particular object. Now, which is that object is depends on how a function which includes 'this' keyword is being called.
**TDD**: write tests get error, code based on expected test not passed all tests , fix bugs pass all tests , refactor code.
**Jest:** JS testing framework
**CI:** "Continuous delivery" makes sure the software checked in on the mainline is always in a state that can be deployed to users and "continuous deployment" makes the deployment process fully automated.
**REST**: architectural style of API

**Data Model** Data modelling is the process used to structure how data is stored, as well as modelling relationships within the data. example non relational db and relational .

## Preview
SQL is a programming language thats structure  
SQL is a relational db that structured with tables that has a schema *fields ,**columns.**. records*rows* .. all records should follow the schema even if it's value is null...Relation between tables can be 1 to 1 one to many . Many to manyWe have collections rather than tables in no SQL .. inside these collection there are documents as same as records in SQL .. you don't have to follow the schema structure in nosql.. there are no relations in nosql in general where you can add all data you need in one place.. example like SQL has relation between two tables think of it as adding these relation in the two tables in a document that has collection which has everything  
Horizontal scaling is difficult in SQL however both hortizantl and vertical are possible in nosql

*Resources*
[https://www.codica.com/blog/test-driven-development-benefits/](https://www.codica.com/blog/test-driven-development-benefits/)  
[https://mochajs.org/](https://mochajs.org/)
https://medium.com/developers-arena/javascript-classes-inheritance-and-prototype-chaining-es5-and-es6-way-4b8e9416702b
https://www.freecodecamp.org/news/benefits-of-rest/
https://www.freecodecamp.org/news/benefits-of-rest/
https://en.wikipedia.org/
https://www.tutorialsteacher.com/javascript/this-keyword-in-javascript