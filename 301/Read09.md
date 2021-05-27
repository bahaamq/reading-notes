
**Function programming** is a *style* of building the structure  that treats computation as the evaluation of mathematical functions.

**Pure function** is a function that is built to be  dependent to all other elements , so each time you run it it gives the same value ,, as an example if we have an  IMPURE function that responsible for  multiplying 2 by a global variable , this is impure because it depends on external activates so if you change the value of the global variable each day it will give a different result 


When data is **immutable**, its ****state cannot change**  after it’s created** so imagine that you have an array a=[1,2,3] and you want to add them together to be 1+2+3=6 , you shouldn't modify the value of array a directly but create a new variable and assign the value to it

if the output is always the same we can stop using it example 
sum(3, sum(5, 8)); c**an be converted to be** sum(3, 13); as 5+8 is always 13

*Module is a JS file  , 
Require is used to import the exported file* 