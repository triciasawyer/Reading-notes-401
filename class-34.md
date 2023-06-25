# Reading notes class 34

## [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

**Explain the difference between a query string parameter and a path parameter.**

The main difference between a query string parameter and a path parameter lies in their purpose and location within a URL. Query string parameters are appended to the end of the URL and used for additional data or parameters, while path parameters are part of the URL’s structure and used to identify specific resources or entities.

**What would our API URL with a path id parameter be, given the following information:**

    1. Domain: http://our-site.com
    2. v3
    3. model name: stuff
    5. id: things**

Our API URL would be this: “http://our-site.com/v3/stuff/things” given the information above

**We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**

- Imagine our API as a digital service that offers access to a vast collection of “things” on the internet. These “things” can be anything such as articles, images, videos, or any type of information. To interact with our API and retrieve specific “things,” we have created a special way for other software applications to communicate with it. The interface of our API serves as a gateway or entrance point for other applications to connect with our service. It’s like a receptionist who directs visitors to different areas of a building. In our case, the interface helps guide other applications to the right location in our API to find the desired “things.”
- The URL, http://our-site.com/v3/stuff/things is a specific address that represents the interface of our API. When other applications want to access certain “things,” they send requests to this address. The different parts of the URL, such as “v3,” “stuff,” and “things,” act as signposts that guide the request to the appropriate area within our API.

## [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

**Describe how you would use middleware to implement basic and bearer auth.**

By creating custom middleware functions, you can intercept incoming requests and validate the provided credentials or access tokens before granting access to protected routes. Basic authentication involves verifying the username and password against a user database, while bearer authentication verifies the authenticity of a token. The middleware acts as a security checkpoint, ensuring that only authenticated and authorized requests can access sensitive resources. Implementing these authentication mechanisms through middleware adds an extra layer of security to the application, safeguarding sensitive information and allowing only authorized users to access restricted areas.

**Describe the handshake necessary to implement OAuth.**

Imagine you’re using a cool app or website, and you want to access some of your information from another app or service. However, you want to make sure it’s secure and under your control. That’s where OAuth comes in. OAuth acts like a permission system. It allows you to grant specific access to the app or service you want to use. First, you give your consent for the app or service to access your information. Once you give permission, you receive a special authorization token, like a key, which lets you access your data. This token is used to authenticate and authorize your requests to the app or service, ensuring that only authorized access occurs. If the token expires, there’s a way to refresh it without starting the whole process over. OAuth provides a standardized and secure method for you to control how your information is shared between different apps and services.

**Describe how Role Based Access Control works to a non-technical friend.**

RBAC is like a structured system that defines roles with specific permissions and access rights. It ensures that people have the right level of access and can only perform tasks that align with their role. RBAC provides security and efficiency by managing who can do what, just like assigning roles in a group project to make sure everyone contributes effectively.

## Things I want to know more about
