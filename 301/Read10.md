
**CallStack**
When a function is  called it's saved in memory **stack structure** (last in first out), we can call functions until the stack memory is full (stack overflow) (that only happens if the function is invoking another or self function untill the memory is full) so the first function that had to be executed doesn't have the priority, since javascript is a **single-threaded** , only one function can be executed at a time which is the top function of the stack, then it will be ~~removed (popped)~~ from the stack so the next executable function will be the new top one and so on until the stack is empty.
An example of stack overflow is when we have a recursive function*(a function that calls itself)* and this function doesn't have any condition to let it stop calling itself before exceeding the limits of the stack.

example of call stack:
![Callstack Ex:](https://miro.medium.com/max/1200/1*E3zTWtEOiDWw7d0n7Vp-mA.gif)

**..Errors type and why it's happening**
*Reference*: when you use a variable that is not yet declared
*syntax*: when you spell error or when you don't flow the structure of writing js elements.
*Range*: when you add an incorrect range to any element, ex set a length to array to be less than zero
*type*: when you try to access an undefined value,, ex:
var foo = {}  
foo.bar // undefined  
foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined

*breakpoints* is a technique to track code execution for the purpose of debugging, ex if you add a breakpoint at line 50 the program will run till line 50 only...
the "*debugger*" is an example of implementing breakpoint
it's done by "Normally, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.", ex:https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_state_debugger

*Additional Resources
[W3schools](https://www.w3schools.com/)
[javascripttutorial](https://www.javascripttutorial.net/javascript-call-stack/)
[Medium](https://medium.com/)*