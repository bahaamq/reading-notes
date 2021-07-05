**Basic Authentication** : you have to give a username and secret to be authonticated and get authorized
**Bearer Authentication** : you have to give access token to be get authorized and you can give a time to this token so no need to re add your username and secret untill that time 

**Jwt packages**
securely transmitting information between parties as a JSON object

What considerations should we make when creating and storing a SECRET?
Store secrets safely and never share them with others or push them to the internet
*Definitions*
**Encryption** converts plain text into a cipher text in order to ensure its confidentiality and integrity  so that it's unreadable for anyone unless who has a key

**Token**:general, a token is an object that represents something else, such as another object (either physical or virtual),

The name “**Bearer authentication**” can be understood as “give access to the bearer of this token.” The bearer token is a cryptic string

**JSON Web Token (JWT) i**s an open standard ([RFC 7519](https://tools.ietf.org/html/rfc7519)) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the **HMAC** algorithm) or a public/private key pair using **RSA** or **ECDSA**.

**Preview:**
1.  Which 3 things had you heard about previously and now have better clarity on? RBAC,Basic Authentication , Bearer Authentication 
2.  Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Encryption ,Basic Authentication , Bearer Authentication 
3.  What are you most excited about trying to implement or see how it works? RBAC

**Preparation**
**RBAC:** giving access to different resource depends on your role(job) IN THE SYESTEM as a user

**1. Inventory your systems**
**2. Analyze your workforce and create roles**
**3. Assign people to roles**
**4. Never make one-off changes**
**5. Audit**

Resources:
https://www.google.com/
https://jwt.io/introduction
https://www.wikipedia.org/
https://stackoverflow.com
https://swagger.io/docs/specification/authentication/bearer-authentication/