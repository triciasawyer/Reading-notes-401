# Reading notes class 18

## AWS API Gateway Overview

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

## AWS API Gateway

**What are the some benefits of using Amazon API Gateway?**

**What two API types might you choose from?**

## AWS DynamoDB Guide

**What is DynamoDB?**

**Under what circumstances would you recommend DynamoDB over MongoDB?**

## AWS DynamoDB

**Explain to a non-technical friend how DynamoDB works.**

## Dynamoose

**What is Dynamoose?**

**What are some key features of Dynamoose?**

## Reflection

**What are your learning goals after reading and reviewing the class README?**
