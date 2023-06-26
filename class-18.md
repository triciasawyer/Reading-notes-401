# Reading notes class 18

## [AWS API Gateway Overview](https://www.serverless.com/guides/amazon-api-gateway)

**What is Amazon API Gateway?**

It is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API, and then connect those endpoints with the corresponding backend logic. It also handles authentication, access control, monitoring, and tracing of API requests.

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**

Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is why API Gateway is so valuable in Serverless setups. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself. That brings the advantages of scalability, low maintenance, and low cost.

**How does API Gateway integrate with other AWS services?**

Some AWS services that support integration with Amazon API Gateway are:

- AWS Lambda: run Lambda functions to generate HTTP API responses.
- AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
- Amazon Cognito: provide authentication and authorization for your HTTP APIs.

API Gateway supports direct integrations that can be configured in the API Gateway user interface with the following actions such as:

- Invoking an AWS Lambda function.
- Invoking another HTTP endpoint, with or without VPC Link.
- Making an HTTP call against the API of any AWS service that provides an HTTP API.
- Returning a mock response generated within API Gateway without calling out to other services.

## [AWS API Gateway](https://aws.amazon.com/api-gateway/)

**What are the some benefits of using Amazon API Gateway?**

Easy API Creation and Management, Scalability and High Availability, and Security and Access Control to name a couple

**What two API types might you choose from?**

RESTful APIs and WebSocket APIs

## [AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

**What is DynamoDB?**

It is a fully managed NoSQL database service provided by Amazon Web Services (AWS). It is designed for applications that require fast and predictable performance, seamless scalability, and low administrative overhead

**Under what circumstances would you recommend DynamoDB over MongoDB?**

While both are NoSQL databases, they have different features and strength, so I would say if you want a fully managed service without the need to worry about infrastructure provisioning, scaling, and maintenance, DynamoDB is the way to go. AWS manages all aspects of DynamoDB, allowing you to focus solely on developing your application.

## [AWS DynamoDB](https://aws.amazon.com/dynamodb/)

**Explain to a non-technical friend how DynamoDB works.**

You can think of it as having a giant bookshelf where you want to store and organize your books. Each book is unique and has its own title and content. Instead of a physical bookshelf, DynamoDB is like a digital bookshelf provided by Amazon.
In DynamoDB, you can create tables to store your data, just like shelves on the bookshelf. Each table can have many items, which are like individual books. Each item has its own unique identification number called a primary key.

## [Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

**What is Dynamoose?**

It is an open-source npm (Node Package Manager) library that provides an easy to use interface for working with Amazon DynamoDB in Node.js applications. It serves as an Object Data Modeling (ODM) library, similar to how an Object-Relational Mapping (ORM) library works with relational database.

**What are some key features of Dynamoose?**

Dynamoose provides an Object Data Modeling (ODM) approach for working with DynamoDB. It allows you to define models that represent tables in DynamoDB. It also allows you to define the structure and attributes of your data using a schema. You can specify the data types, indexes, validation rules, and relationships between entities, ensuring data consistency and integrity. On top of that, Dynamoose simplifies performing CRUD operations on DynamoDB. You can use intuitive methods like create, save, find, update, and delete to interact with your data directly.

## Reflection

**What are your learning goals after reading and reviewing the class README?**

I am excited to learn about dynamoDB and to learn through experience how that works differently than MongoDB

## Things I want to know more about
