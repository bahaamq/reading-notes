*It's better to have specific  images  size  because HTML and css load first so all HTML/css render then **leave a space** for images to be loaded .. so that allowing html css to render first without waiting for the images to loaded.
As images are displayed inline by default , if you wish to center an image you can convert it to block-level element then center it by using ex: margin or text-align.*

Images  can be backgrounds and same as normal images they may be the last thing that is loaded on the page.
The background image has multi properties for example **background-repeat** and you can choose whether horizontal or vertical or no-repeat or fixed or on scroll .. there is background position that allows you to control the horizontal and vertical alignment the first represents the horizontal the sec vertical if you choose one value then by default the other one will be centre below is an example of what values can be used for background-position : (left top, left center, left bottom, center top, center center, center bottom, right top, right center, right bottom)


You can also use percentage , PX  as the initial value **as the top left value is equal to = 0,0 .**
*There is a shorthand* to add all properties and values to the background at the same time directly for example:  background: #ffffff url("images/tulip.gif")  no-repeat top right;}

***Also, you can use multiple backgrounds in different positions.***

To reduce server requests we can use **Image Sprites** and control image position using background-position property.

***Search engine optimization.***
not only depends on what you do to your page to get a higher rank but it also depends on how many sites added to your site and how relevant are they. (*Off-page technique)*
*On-page technique* is a set of instructions that you can on your page to get higher rank  *examples:*
**Using  related keywords  in :**
- Each image should have  an alternative related text inside (alt attribute)
-  Adding a relative (heading,text,page description text on the page to have keywords that represent related info
Url
- Linkable text should be related not unrelated ex click here for more info
To have special keywords you can make a brainstorming session, using researching tools that gives you related keywords, compare the keywords, map them for all pages and the more you enter page the more meaningful and have detailed meaning these keywords will be.

***Google Analytics*** is a great tool that analyzes user to know from where do they come what they are looking for. And if they leave from which page did they .

>> Examples are token from the Duckett HTML book.