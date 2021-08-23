## Review, Research, and Discussion
1.  Why choose Redux instead of the Context API for global state? `Redux` is much more powerful and provides a large number of features that the `Context Api` doesn't provide
2.  What is the purpose of a reducer? **determines changes to an application's state**
3.  What does an action contain? the value of the case 
4 .  Why do we need to copy the state in a reducer?
-   They are not allowed to modify the existing  `state`. Instead, they must make  _immutable updates_, by copying the existing  `state`  and making changes to the copied values.
### Document the following Vocabulary Terms
immutable state **an object whose state cannot be modified after it is created**

time travel redux : is the ability to move back and forth among the previous states of an application and view the results in real time.

An action creator is **merely a function that returns an action object**

a reducer is **a pure function that takes an action and the previous state of the application and returns the new state**

Dispatch:
dispatch is a function of the Redux store. You call store.  **dispatch to dispatch an action**. This is the only way to trigger a state change. With React Redux, your components never access the store directly - connect does it for you.

## Preview

-   First and foremost,  `combineReducers`  is simply  **a utility function to simplify the most common use case when writing Redux reducers**. 
reducer roles
-   They should only calculate the new state value based on the  `state`  and  `action`  arguments
-   They are not allowed to modify the existing  `state`. Instead, they must make  _immutable updates_, by copying the existing  `state`  and making changes to the copied values.
-   They must not do any asynchronous logic or other "side effects"
