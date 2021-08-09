
### Review
## Why do we not need more .html pages in a multi-page React app?

having  a scenario where we needed to provide a different entry point (which differed significantly from the original app) to warrant a separate SPA but had enough shared code too to make setting up a separate project redundant.

https://sapandiwakar.in/multiple-html-pages-with-create-react-app-app/

## If we wanted a component to show up on every page, where would we put it and why?

-  I think Outside the  `<BrowserRouter/>` ,  as it's not going to be linked with any specific route if we have multi routes in the project ...

## What does routing do with the components that were rendered when a new route is requested

Users click a link, the URL changes, views change and for all they know they’ve moved on to another page — except they haven’t. React Router is a key tool for giving your SPA the feel of a multi-page application while maintaining the quick rendering of React’s virtual DOM.
https://www.freecodecamp.org/news/imagine-react-router-as-your-switchboard-operator-f4f1ac22188c/

## What does props.children contain?
the data between the open and closing tag when you call a child component from parent component


*this.setState(): used when we make a class component* 
*useState()**  Functional Component* 

*this.setState(): used for updating a state 
*useState()** used for initialize the value of a state  * 

*setState(): since it's a class youwill access it's element using this object

useState()** since it's built with React hooks it allows to be used as a functional component without the need for making a class.


### Document
-   **State Hook**  The useState() is a Hook that allows you to have state variables in functional components ,* 

Mounting : rendering  the Dom 
Unmounting : Clean up the dom 

//Notes about virtual DOM
** in react foer each object in the dom there is a virtual object in the virtual Dom 
**When you render a JSX element, every single virtual DOM object gets updated.
**Once the virtual DOM has updated, then React compares the virtual DOM with a virtual DOM  _snapshot_  that was taken right before the update.
By comparing the new virtual DOM with a pre-update version, React figures out  _exactly which virtual DOM objects have changed._  This process is called “diffing.”
Once React knows which virtual DOM objects have changed, then React updates those objects,  _and only those objects,_  on the real DOM.
**


## prepare 
in class components we were using didmount,didupdate,willunmount , by react introduce hooks now we can do them using useeffect() and in the same time if needed. 
