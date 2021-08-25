# Welcome to StackEdit!

1.  What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
I think using thunk middleware , since we are saying on application  start so the states are empty and since we are dealing with redux to give the states something to be saved before despatching we can using thunk ,,, example using it to make a get request for third party api and since it has access to dispatch we can send the results to dispatch function so yeah we can have an initial value to state onload.
2.  When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
the thunk since you are gonna call it and the thunk action will call the dispatcher function since it has access to it.

**middleware** : function that runs in the middle of the process usuaaly it does somethinf/modify / update .etc  and has access to special things 

**thunk**: asynchronous redux middleware has access to dispatcher function 


The Redux Toolkit package was developed to be the new standard way to write Redux code, handling three major concerns about Redux itself...

1.  "Configuring a Redux store is too complicated"
2.  "I have to add a lot of packages to get Redux to do anything useful"
3.  "Redux requires too much boilerplate code"

Using Redux Toolkit is not required when using Redux, however it is encouraged because it does make your code DRYe
