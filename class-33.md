# Reading notes class 33

## [What is Role Based Access Control (RBAC)?](https://www.digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

**What is Role Based Access Control (RBAC)?**

Role Based Access Control is a security model used to manage and control access to resources within a system or application. It is a widely adopted approach for enforcing access control policies in various domains such as computer systems, databases, and web applications.

**Share an example of RBAC including all possible CRUD operations and correlating roles.**

1. Admin:

• Can create, read, update, and delete any document.

 • Has full control and unrestricted access to all documents.

2. Editor:

 • Can create, read, update, and delete documents.

 • Cannot perform administrative tasks like managing users or system settings.

3. Author:

 • Can create, read, update, and delete their own documents.

 • Cannot access or modify documents created by other users.

4. Viewer:

 • Can only read documents.

 • Cannot create, update, or delete any documents.

As an example, here are four roles defined above, each with different levels of access to the CRUD operations on documents.

**What are the Benefits of RBAC?**

RBAC provides an organized and efficient approach to access control, enhancing security, simplifying administration, and promoting least privilege principles, which are crucial for maintaining the integrity and confidentiality of data and resources within a system.

## Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named

[react-cookie library](https://www.npmjs.com/package/react-cookie)

[react-cookies component](https://www.npmjs.com/package/react-cookies)

**Describe some react-cookie features.**

React-cookie is a popular library for managing cookies in React applications. Some key features provided by react cookie are:

- Cookie CRUD: react cookie allows you to create cookies, retrieve cookies, update cookie values or modify them, and delete cookies by providing the name, value, or the optional configurations like expiration time, domain, path, and secure flag depending on the method used. You can use the useCookies hook or the withCookies higher-order component (HOC) to access the cookie creation functionality, cookie data, to update specific cookies, and for removing cookies.
- React cookie provides support for server-side rendering (SSR) in React applications. It offers a CookiesProvider component that facilitates cookie management on both the client and server side, ensuring consistent cookie handling during SSR.

**Describe some react-cookies features.**

React cookies is a widely used library for handling cookies in React applications. Some key features provided by the react cookies library are:

- Cookie Crud: React cookies allows you to create cookies, retrieve cookies, update cookies, and delete cookies by setting their name, value, or optional configurations such as expiration time, domain, path, and secure flag. You can use the react cookies API to create cookies with specific properties, read cookie data, update the value or properties of the cookies, and remove cookies.
- React cookies provides support for server-side rendering (SSR) in React applications. It offers functions that enable cookie management on both the client and server side, ensuring consistent cookie handling during SSR.

**Which library would you prefer? Why?**

I think for me, I would prefer the react cookies library just because after reading some things about it and even asking openai the benefits of each, I now know that react cookies is known for its simplicity and straightforward API. It offers a minimalistic approach to cookie management, making it easy to grasp and use. I also think I’d prefer the react cookies library over react cookie because react cookies is lightweight. React cookies is a lightweight library with no external dependencies. It doesn’t add much overhead to your project’s bundle size either. It is also easy to integrate into existing projects without much effort.

Although, I can see both being handy, it just depends on what you’re trying to do and the application it is used in.

## Things I want to know more about
