# Reading notes class 3

## Review: ES6 Classes

**Classes are a template for creating ____.**
Objects

**Can a class declaration be hoisted?**
Yes

**How would you describe a constructor and contextual “this” to a non-technical friend?**
A constructor is a special method of a class or structure in object-oriented programming that initializes a newly created object of that type. The contextual this keyword refers to an object.

## Using Express Routing

**Within Express, what does routing refer to?**
Routing refers to how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method such as GET and POST.

**What is the difference between a route path and a route method?**
A route method is derived from one of the HTTP methods, while route paths, along with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.

**When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**
When next is invoked, it executes the middleware succeeding the current middleware. If next has been passed to your middleware as a parameter, you must use next() with nothing in it unless you want to cause an error.

## Express Routing

**What is an Express Router?**
It is a mini express application without all the bells and whistles of an express application, just the routing stuff.

**By what mean do we initialize express.Router() in an express server?**
When creating our frontend routes for our application. This includes the Home and About pages.

**What do we use route middleware for?**
We use route middleware to run a certain route parameter. In our case with the lab, we are using :name in our hello route

## Reflection

**What are your learning goals after reading and reviewing the class README?**

My learning goals are to become aware and comfortable with backend just in general, but to be more specific, learning how to target routes and use them to do what I want.
