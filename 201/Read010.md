Js debugging: 
Debugging is a to find the source of error and fix it 
Common ways to debug your code is 
1)Using console and developer tools:
2)Common problems
3)Expectation handling

## ## Some tips to know :
 - Order of execution: the interpreter save js statements   then execute them in a to-do list called "callstack" 
Once each statement executed it's deleted "popped" out of the slack and start to execute the one before it until the stack got empty.

- You can use a variable anywhere if it's on global scope however if it's on the lexical scoop you can just use it within its scope ex declare a variable inside a function can only be used within function scope if you try to access a variable without taking into account the scope definition this may cause a reference error

- You should make sure what's the type of something (example: if you adding two numbers you may have had wrong results as they can be strings if they referred from a box that returns a string)

***Errors: EX***
**Syntax** : (*missing comma between array elements*)
**References**: *trying to print a variable that never executed* 
**Range**: *declare an array with -1 size*
**NAN**: *adding a string of characters to number*

To fix any issue , how to face it ...
- You should try to know where is the problem then what is it .. you can now by adding a **breakpoint** to know till where the code has been executed, after knowing where is the problem try to know w**hat cause it,** try to log it to see if returns the expected value.


****Some extra console methods :****
They give the same just log the message but differ in the logo before logging message ex console. warn givers warning logo.

- Console.error gives error logo.
- Console.group to add multiple logging statements into one group.

- Console.tabuler to represent data as a table it can represent objects and arrays.

*Breakpoints* is used to stop executing the code after the first point .. you can add a condition to let the breakpoint valid as well as you can add multi breakpoints 

Using "**debugger**" in your code means you are adding a breakpoint and it will stop the execution of all statements after it

You can use exception handling to handle errors try , catch if you are expecting an error let's say as an example (3+'3') this will not retrieve an error however may not be as you want so you can add if condition inside the try scope to **throw** *a new error* to stop the execution because javascript will not know its as an error for you.