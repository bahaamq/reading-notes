
## Write the following steps in the correct order:

1.  Register your application to get a client_id and client_secret
2.  Ask the client if they want to sign in via a third party
3.  Redirect to a third party authentication endpoint
4.  Make a request to a third-party API endpoint
5.  Receive authorization code
6.  Receive access token
7.  Make a request to the access token endpoint

*What can you do with an authorization code?*
used by the client to obtain an access token

**What can you do with an access token?**
passes the access token as a credential when it calls the target API.

 **What’s a benefit of using OAuth instead of your own basic authentication? ?**
1.  It allows you to read data of a user from another application.
2.  It supplies the authorization workflow for web, desktop applications, and mobile devices.
3.  Is a server side web app that uses authorization code and does not interact with user credentials.
4.  It gives users more control over their data; they can selectively grant access to various functionalities for applications they want to use.
https://www.clowder.com/post/why-your-organization-should-be-using-oauth-2.0

The **Client ID** (cid) is a unique **identifier** for a browser–device
A **client secret** is a **secret** known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors.
**Authentication Endpoint** A method ensures that only valid or authorized ****endpoint**** devices have access. to network

**Access token Endpoint: is where apps make a request to **get** an **access token** for a user. This section describes how to verify **token** requests and how to return the appropriate response and errors

Api Endpoint:An Application Programming Interface (API) allows two systems to communicate together

Authorization Code:
used by the client to obtain an access token
Access Token: access token is used  as a credential when it calls the target API.

Which 3 things had you heard about previously and now have better clarity on?

-  Linked list
-  Authentication/Authorization
-  Modularity

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

-  Data structure and algorithm
- Authentication
- Access Tokens


What are you most excited about trying to implement or see how it works?
Access Tokens

**Prepare** 
JWT JSON Web Token (JWT)  -contained way for securely transmitting information between parties as a JSON object. 

## When should you use JSON Web Tokens?

Here are some scenarios where JSON Web Tokens are useful:

-   **Authorization**: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.
    
-   **Information Exchange**: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with.
Whenever the user wants to access a protected route or resource, the user agent should send the JWT, typically in the  **Authorization**  header using the  **Bearer**  schema. The content of the header should look like the following:

Authorization: Bearer token
