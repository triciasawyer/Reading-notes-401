# Reading notes class 17

## [AWS S3](https://aws.amazon.com/s3/)

**What is Amazon S3?**

An object storage service that offers scalability, data availability, security, and performance. Industries of all sizes can store and protect any amount of data for about any use case including data lakes, cloud-native applications, and mobile apps.

**Name some use cases for Amazon S3.**

Build a data lake, back up and restore critical data, archive data at the lowest cost, and run cloud-native applications.

**Name some benefits of using Amazon S3.**

Optimized costs, organize data, and configured access controls to meet specific business, organizational, and compliance requirements.

## [AWS Lambda Basics](https://www.serverless.com/aws-lambda)

**What is AWS Lambda?**

A serverless computing service within AWS. It allows you to run your code without provisioning or managing servers. You can focus on writing your code while AWS handles the infrastructure and scaling aspects.

**Name some use cases for AWS Lambdas.**

Scalable APIs and data processing

**Describe “serverless” to a non-technical friend.**

Say you want to run a small business, like selling sculpted pieces online. Normally, you would need to rent a physical store, buy display shelves, hire staff, and manage everything yourself. You would have to worry about paying for rent, electricity, and maintaining the store at all times. Now with the serverless concept, it allows you to focus on your core business activities without the need to manage and maintain the technical infrastructure. You could think of it as like renting a store space where you don't have to worry about all the tasks behind the scenes, and you only pay when you actually make sales.

## [CDN](https://cyberhoot.com/cybrary/content-delivery-network-cdn/)

**What is a CDN?**

Content Delivery Network (CDN) is a distributed network of servers located in various geographical locations around the world. Its purpose is to deliver web content and other digital assets to users with high availability and performance. When a user requests a webpage or any other online content, the request is routed to the nearest server within the CDN network. This server, also known as an edge server or a Point of Presence (PoP), stores cached copies of the content. By storing content in multiple edge servers distributed globally, CDNs can reduce latency and improve the delivery speed.

**How does a CDN work with relation to the website visitor?**

The CDNs first step is to request routing. The visitor's request is initially directed to the DNS (Domain Name System) server responsible for resolving the website's domain name. The DNS server will typically route requests through the CDN as it determines the nearest or most optimal server within the CDN network to handle the request based on the geographic proximity, server load, and network conditions. Then, once the DNS server identies the appropriate server, the visitors request is forwarded to that server and stored as a copy. Next, the content availability is where the sever checks if it has the copy of the request content and if so, it directly sends the content to the visitor.

**What are the benefits of employing a CDN?**

Improved Website Performance, Enhanced User Experience(with faster load times), Global Availability, and Scalability and High Availability (CDN helps to prevent overwhelming the origin server)

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To better understand how to work with AWS (especially S3) and CDNs, to then create S3 buckets for file storage

## Things I want to know more about
