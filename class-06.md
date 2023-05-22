# Reading notes class 6

## Securing Passwords

**Explain to a non-technical friend how you would safely hash and store a password.**
When it comes to storing passwords securely, we use a process called "hashing." Think of hashing as a way to transform the password into a secret code that is difficult to reverse-engineer. This code, called a hash, is stored in the system instead of the actual password. Instead of storing the actual password, we store the hash code in the system's database. So even if someone gains access to the database, they won't be able to retrieve the original passwords because they only have the hash codes.

**What is Bcrypt?**
Bcrypt is a widely-used password hashing algorithm that is designed to be secure and resistant to various cryptographic attacks. It is commonly used for storing and verifying passwords securely in databases.

**Why might you use something like Bcrypt?**
Bcrypt automatically generates a random salt for each password that is hashed. The salt is combined with the password before hashing to create a unique input, ensuring that even users with the same password will have different hash codes.
Bcrypt also employs multiple rounds of hashing. The number of rounds is determined by the cost factor. The multiple rounds significantly increase the time it takes to hash a password, making it more resistant to attacks.

## Basic AUTH

**What is Basic Authentication?**
Basic Authentication is a method for an HTTP user agent (a web browser) to provide a username and password when making a request.

**What properties are necessary in the header of a Basic Auth request?**
In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic < credentials >, where credentials is the Base64 encoding of ID and password.

**How are username:password in Basic Auth encoded?**
To give an example, if the browser uses Aladdin as the username and open sesame as the password, then the field's value is the Base64 encoding of Aladdin:open sesame, or QWxhZGRpbjpvcGVuIHNlc2FtZQ==. Then the Authorization header field will appear as, "Authorization: Basic QWxhZGRpbjpvcGVuIHNlc2FtZQ=="

## OWASP auth cheatsheet

**Define the authentication process to a non-technical recruiter.**
The user or computer has to prove its identity to the server or client. Usually, authentication by a server entails the use of a user name and password.

**How should your error messaging respond (both HTTP and HTML)? Why?**
When the server wants the user agent to authenticate itself towards the server after receiving an unauthenticated request, it must send a response with a HTTP 401 Unauthorized status line and a WWW-Authenticate header field.

## Bookmark and Review

[bcrypt](https://www.npmjs.com/package/bcrypt)

## Additional questions

**Looking ahead at this module’s course, what do you look forward to learning?**
I am looking forward to learning Role Based Access Control and doibg our guided projects.

**What are your learning goals after reading and reviewing the class readme?**
To better understand Bcrypt.

## Things I want to know more about
