
## How does React differ from vanilla JS/HTML/CSS?
1.  Plain JS apps usually start with the initial UI created on the server (as HTML), whereas React apps start with a blank HTML page, and dynamically create the initial state in JavaScript.
2.  React requires you to break your UI into components, but plain JS apps can be structured in any way you see fit.
3.  Data for plain JS apps are stored in the DOM itself and has to be found from the DOM before it can be used. React apps store data in regular JavaScript variables
4.  UI updates in plain JS have to happen by finding the DOM node to update and manually appending or removing elements. React  _automatically_  updates the UI based on setting and changing  `state`  within the component.
https://www.framer.com/blog/posts/react-vs-vanilla-js/

## What is the primary difference between a function component and a class component?

Syntax , functional as it's reqular function , it doesn’t have its own state, components are ES6 classes and Functional Components are function,
1.  Functional component are much  **easier to read and test** because they are plain JavaScript functions without state or lifecycle-hooks
2.  You end up with  **less code**
3.  They help you to use  **best practices**. It will get easier to separate container and presentational components because you need to think more about your component’s state if you don’t have access to setState() in your component
4.  The React team mentioned   that there may be a  **performance**  boost for functional component in future React versions
https://djoech.medium.com/functional-vs-class-components-in-react-231e3fbd7108


***Definations***
**Functional Components:** : normal JSX functions used to return a React element (JSX).


**Children* / Child Components** the parent component is the only rendered component it calls  a component  that contains all components all expect the parent are considered as children components.

**Preview**
1.  Which 3 things had you heard about previously and now have better clarity on?
2. Functional component , child compnent , class vs functional components
3.  Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Functional component , hooks , state updates ,react life cycle 
4.  What are you most excited about trying to implement or see how it works? Mounting unmounting and these things that are related to react life cycle ,more about DOM

***Hooks  , Code reuse ,***
as react project divided into components assuming that theree are some component depend on eacgh other sending data over probs is headeache,, moreover You can’t extract behavior like “watch window size and update the state” or “animate a value over time” from a class component without restructuring your code or introducing an abstraction like Observables. Both approaches hurt the simplicity that we like about React.
***Hooks solve exactly that problem***. Hooks let you use React features (like state) from a function — by doing a single function call. React provides a few built-in Hooks exposing the “building blocks” of React: state, lifecycle, and context. 
