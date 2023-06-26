# Reading notes class 16

## [AWS EC2](https://aws.amazon.com/ec2/)

**What is an EC2 Instance?**

An EC2 (Elastic Compute Cloud) instance is a virtual server provided by Amazon Web Services (AWS). It is one of the fundamental building blocks of AWS's cloud computing services. EC2 instances allow users to rent virtual machines on which they can run applications and services.

**Name 2 use cases for EC2.**

- EC2 instances are often used to host web applications and websites. By launching EC2 instances, users can set up virtual servers to run their web application stacks, including web servers, application servers, and databases. They can choose the appropriate instance type and configure the resources based on the anticipated traffic and performance requirements of their application.
- EC2 instances are frequently utilized for big data processing and analytics tasks. Users can launch EC2 instances with ample CPU and memory resources to run distributed processing frameworks like Apache Hadoop or Apache Spark. These instances can process large volumes of data in parallel, perform complex analytics, and generate insights.

**Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.**

One reason to use ECS (Elastic Container Service) instead of services like Heroku, Digital Ocean, or Render.com is the flexibility and control it offers over your infrastructure. ECS allows you to have fine-grained control over the underlying infrastructure and the containerization of your applications. That is beneficial because you have the ability to customize and configure the underlying infrastructure to meet your specific requirements. You can define your own Amazon Machine Images (AMIs), customize networking settings, and configure auto-scaling rules. This level of control allows you to optimize the performance, security, and cost of your infrastructure based on your application's needs.

## [EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)

**Where can we find EC2 on the AWS Console?**

After signing in, you can search EC2 or Elastic Compute Cloud, then EC2 dashboard will open, displaying the overview of your EC2 instances and other information. You can also navigate EC2 from the services menu, and a list of available AWS services will appear. You can scroll down or use the search bar to find EC2.

**Explain the general difference between T2 Micro and XL.**

T2 Micro instances are part of the T2 instance family, which is designed for general purpose workloads. T2 Micro instances have the smallest size within the T2 family and provide a low cost option for applications. T2 Micro instances are burstable performance instances. They come with a baseline CPU performance and CPU credits. T2 Micro instances are suitable for applications with intermittent or low CPU utilization.

The term "XL" is not specific to any particular instance family in EC2. It is just used to refer to larger instance sizes across various families. The performance of an "XL" instance will depend on the specific instance family and size chosen. XL instances, depending on the specific instance family and size chosen, are typically priced higher than T2 Micro instances due to their increased resources and performance capabilities.

**Explain a “Compute Cycle” to a non-technical friend.**

Think of having a task to complete, like solving a math problem. To solve the problem, you need to perform a series of steps, such as adding, subtracting, multiplying, and dividing numbers. Each step you take to solve the problem is like a compute cycle.

## [Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

**What is Elastic Beanstalk?**

Elastic Beanstalk is a fully managed service provided by Amazon Web Services(AWS), that makes it easier to deploy, manage, and scale applications in the cloud. You can simply upload your application code, and the service takes care of provisioning the necessary compute resources, such as Amazon EC2 instances, load balancers, databases, and storage, to run your application

**Describe the relationship between EC2 and Elastic Beanstalk.**

EC2 and Elastic Beanstalk are two related services within the Amazon Web Services (AWS) system. They are both distinct services, but they work together to provide a platform for deploying and managing applications in the cloud.

**Name some benefits of using Elastic Beanstalk.**

## Bookmark and Review

[Virtual Machines](https://www.youtube.com/watch?v=yIVXjl4SwVo)

[VMS and the Cloud](https://www.youtube.com/watch?v=l0DfHUWMjsU)

## Additional Questions

**Looking ahead at this module’s course schedule, What do you look forward to learning?**

What all AWS includes and how to use it.

**What are your learning goals after reading and reviewing the class README?**

To get familair with the cloud and containers.

## Things I want to know more about
