
***Representational State Transfer (REST)***

-  REST APIs are designed around  _resources_, which are any kind of object, data, or service that can be accessed by the client
- An Example of _resource identifier_is *URL .* 
- GET, POST, PUT, PATCH, and DELETE. Are most common HTTP verbs.
- URL Should include nouns not verbs EX:
-https://adventure-works.com/orders // Good 
-https://adventure-works.com/create-order // Avoid

**Chatty API** , An API that's not designed to retrieve data from less requests , however you have to make multi requests to retrieve all data.

Response status for successful **GET** request  is 200
Response status for unsuccessful **GET** request  is 404
Response status for successful **POST** request  is 204

Response status for successful **POST** request  is 201
*If the method does some processing but does not create a new resource, the method can return HTTP status code 200 and include the result of the operation in the response body. Alternatively, if there is no result to return, the method can return HTTP status code 204 (No Content) with no response body.*