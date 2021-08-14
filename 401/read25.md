
## Review, Research, and Discussion
 Describe use cases  `useState()`  vs  `useReducer()`
`useReducer()` :  
Next state depends on the previous.
Complex state shape : When the state consists of more than primitive values, like nested object or arrays.


Why do custom hooks need the use prefix?
easily identifying if a function is a custom hook.

1.  What do custom hooks usually do?
2. Custom hooks  **allow us to have cleaner functional components, remove logic from the UI layer**, and prevent code duplication by bringing common use cases to reusable hooks 

useLocalStorage :This hook simplifies the storage and retrieval of data from the  localStorage.

 Describe how a hook that fetches API data might work
 there would be a js file that staart with use to let react know that we are going to use hooks this filr will be called in the main component initialize to it objects so that  returned values saved on these object so we can use them  
 ```
  const { data:, loading, error } = useFetch('https://api.quotable.io/random')

then the file will have three states for data,loading,error there will be useeffect "didmount" that will run automatically after sending the url it will set the loading to "loading" then it will fetch the url using axios for example will set loading to false and set the data to the res.data that back from axios inside a try block the catch will be setting the error to error state .

### Document the following Vocabulary Terms

Reducer :L is a hooks that's used for local state managment and update state with more flexibility based on action it's preferable to use it if you have complex state changes so your code will be more readable and clener as well as if the value of state is dependeing on the previous value 



### Preparation Materials

Context is primarily used when some data needs to be accessible by _many_ components at different nesting levels. 

Note:
****If you only want to avoid passing some props through many levels,  component composition  is often a simpler solution than context.****
