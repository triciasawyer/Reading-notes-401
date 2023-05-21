# Reading notes class 7

## Intro to JWT

**What is a JSON Web Token (JWT)?**
A JSON Web Token (JWT) is a compact, URL-safe means of representing claims between two parties. It is a self-contained token format that is commonly used for authentication and authorization purposes in web applications and APIs.

**When should we use JSON Web Tokens?**
JWTs provide a flexible and secure way to authenticate and authorize users in various contexts. They offer portability, scalability, and ease of integration across different platforms and technologies, making them a popular choice for modern web applications and distributed systems.

**Claims are expected in which structural component of a JWT?**
Claims are expected to be present in the payload component of a JSON Web Token (JWT). The payload contains the claims or statements that provide information about the authenticated user or other relevant data.

## Are JWTs secure?

**If I get a JWT and I can decode the payload, how can we call that secure?**
The payload of a JWT contains the data or claims that are being transmitted and is Base64Url encoded, making it easily readable when decoded. So, decoding the payload allows you to view the information contained within it, but the security of a JWT lies within the authentication and authorization. The important part is the verification of the signature.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**
The private key or password.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
Sending concatenated content and a secret means sharing a piece of information and a private message securely with someone. It's like putting two things together in a locked box and giving the key to the person you want to share it with.

## JWTs explained

**Why use JWT?**
You can securely transfer information between any two bodies (user, server). It is also digitally signed, so information is verified and trusted.

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**
This is useful because you can send JWT via URL, POST request, and HTTP headers fast. The token you use also is self contained so it contains the information about the user, and allows avoiding query the database more than once, with that token.

**What are the three components (the structure) of a JWT signature?**
First, there’s the header that includes a json object with an algorithm and a type type of JWT token. This part is Base64Url encoded. Then the payload, which includes a structure of a json object that contains claims user details or additional meta data. The payload is also Base64Url encoded. Lastly, the signature that uses Base64Url header and Base64Url payload with a secret. This provides security. They are all combined by a dot.  

## Bookmark and Review

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

## Reflection

**What are your learning goals after reading and reviewing the class README?** To get more comfortable with a basic api server and writing tests, as well as learn how to use a bearer for api and just apis in general. Also, JWT that uses base64Url sounds really interesting too!
