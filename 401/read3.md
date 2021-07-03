
**Name 3 real world use cases where you’d want to change the request with custom middleware**

*express.json() to add body property to request object.
User authentication.
error handler that runs as a middleware before each req to check if there is an error of specific typr to catch it.*

  

**True or false: The route handler is middleware?**

*True*.
 
**In what ways can a middleware function end the process and send data to the browser?**

*calling next with a string ex next('failed'), if there is error handler middleware it will run or it will go to catch if there is a try,catch .*
  

**At what point in the request lifecycle can you “inject” middleware?**

*after getting the route and before http callback functoion*



  

**What can cause express to error with “Request headers sent twice, cannot start a second response”**

*sending two or more responses to the same request
send a header after some of the body has already been written*

**Definitions**

**Middleware** : is a function that has access to req,res objects , that's called before sending request to do stuff , it has next function which is a callback that go to the next middleware if there is or to the main function if there is not next middle ware ,, the next function accepts no arguments if everything worked as expected other wise it accepts a string.

**Req object** : is an object that used to get info from user so that it knows what to send to server tp be processed with it ,, ex send params,query string and the http request method thatis used and the

**Res Object:** it contains what server response to the request


**Application middleware** : a middle ware that runs before each http request


**Routing middleware:** Middleware that's instance of express.Router()

var router = express.Router()
that can be loaded by using instance name.use in our case **router router.use() or router.METHOD() by

so it's as same as application level middleware but to achieve modularity


**Test Driven Development**
a type of unit tes that it's approach is to Write your test all fails start impleminting code , some cases fails other passes re fix your code all test passes refactor your code.

 
**Behavioral testing** : is a test that focus on requirements not implementaion so it only test if the output is as expected when you add input

  
  **Preview**

**Which 3 things had you heard about previously and now have better clarity on?**

Behavioural testing

Test Driven Development

Middleware



**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

Behavioural testing

Test Driven Development

Middleware

  
  

**What are you most excited about trying to implement or see how it works?**

Test Driven Development

Behavioural testing

Test Driven Development


*Es6 classes:is a container of attrs,fileds , used to by objects to get benifi of these things.it can be inherited , creating multi instance of it*

  

**Static methods :**

Methods that can't be called by instance but only class name

The constructor method is a special method for creating and initializing an object created

  

*A constructor can use the super keyword to call the constructor of the super class.*

  
  

**Routing** :You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests

  

Refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routin

Route handlers

*You can provide multiple callback functions that behave like middleware to handle a request. bu using next('route) example of multi callbacks*

  

    app.get('/example/b', function (req, res, next) {
    
    console.log('the response will be sent by the next function ...')
    
    next()
    
    }, function (req, res) {
    
    res.send('Hello from B!')
    
    })
