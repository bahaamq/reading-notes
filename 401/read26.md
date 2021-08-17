-   Why is the Context API useful?
    
Context API is a (kind of) new feature added in version 16.3 of React that allows one to share state across the entire app (or part of it) lightly and with ease. regardless the level 

 Can a component outside of a provider get its context?    
I think no , just let the provider be the parent class and all components will have access to whatever value you send via it
    
 What are some common use cases for using the Context API?
 logout(update the authinticate to not authinticate) 
    
 Describe “Context Hell”
 still can't imagine it but maybe many providers depend on each other making a big nested providers
    

## Document the following Vocabulary Terms

-   **global state**   a state that can be accessed and updated from any where
    regardless the levelity thing 
-   **global context**    a way to state managment by having global access to the state
  
-   **provider**  accepts a value that will be passed to its children. All children components will re-render when the value changes.
    
-   **consumer** -   The Consumer component allows a React component to subscribe to the context changes. The component makes the data available using a render prop.
    

## Preparation Materials

### What is role based access control?

Role-based access control (RBAC) : the different levels of roles , the different level of what you can see , example the administrator has access to things normal user dont .

### React Cookies

-   “Cookies are the data stored in the form of key-value pairs that are used to store information about the user on their computer by the websites that the users browse and use it to verify them”.
    
To set or remove the cookies, we are using a third-party dependency of react-cookie
   
