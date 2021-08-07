- ## Review, Research, and Discussion
  
*Name 5 Javascript UI Frameworks (other than React)***
    
    -   Ext JS by Sencha.
    -   Angular.
    -   Vue.
    -   Ember.
    -   Svelte 3.
Usually, a framework tells us what to do. it has the best practice of doing things and provides tooling to support us...the library let you do whatever in your mind but in an easier way and less code!

*On the other hand, Framework is like buying a new house, you don’t have to deal with building problems, but you can’t choose how to sort your rooms because the house is already built. *A library is like building your home from scratch, you have the choice to make your house as you wish, with any architecture you like, you can sort your rooms in the way you like.

![](https://miro.medium.com/max/60/1*tMJUTqe2dKlueiNU17IZug.png?q=20)

Rendering: convert something to something ex : convert html element to a visual thing in the browser.

Templates: a pattern or a structure that's ready to use  that helps you to use it to build your own idea rather than build it from scratch 

State:is like a private varialble on a component that can be used by sending it as probs on other components .


-   ## Preview
    
-   Which 3 things had you heard about previously and now have better clarity on?
    -   templates
    -   libraries vs frameworks 
    -   5 Javascript UI Frameworks
    - 
-   Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    -   hooks
    -   redux ,hooks,functional compments , 
-   What are you most excited about trying to implement or see how it works?  
   anything that makes thing easier and faster that makes me think ", ts easier than what i studied before but i know that i should've learnet it in the hard way at first  and give me a mind trip that things are going to be easier but at least i can imagine the big picture of how it works so mostly debugging stuffs is easier and applicable  

**Sass** : *css preprocessor that makes you write css as it's a programmming lamguage* 

### Pure components:
Performance-optimized version of  `React.Component`. Doesn’t rerender if props/state hasn’t changed.
###  Functional components
Functional components have no state. Also, their  `props`  are passed as the first parameter to a function.

Life cycle:
Before rendering 
`constructor`  

_Don’t use this_ (before component mount , (render))
`componentWillMount()`

render
`render()`

After mounting (rendering )
`componentDidMount()`

**//component Updating stuffs are nit mentioned in this life cucle**

Before DOM removal  .
*This is the last method in the lifecycle as it pertains to the core unmounting and removal from the DOM. The cleaning up of the component is also performed here.
This is used in the logging out of users when they want to clear out the program from their browser.*
`componentWillUnmount()`



Catch errors
`componentDidCatch()`


https://betterprogramming.pub/reactjs-lifecycle-initialization-mounting-updating-unmounting-8ec22a804118
