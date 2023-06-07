# Reading notes class 19

## AWS SQS vs SNS

**What is the difference between SQS and SNS?**
SQS is a queue-based service that enables asynchronous communication between components, while SNS is a pub/sub service that allows you to broadcast messages to multiple subscribers. The choice between SQS and SNS depends on the specific messaging pattern and requirements of your application.

**What are some use cases for both SNS and SQS?**
Some use cases for SQS are workload decoupling, event processing, and task queues.
Some use cases for SNS are pub/sub messaging, mobile push notifications, and email and SMS messaging.

## AWS SNS and SQS

**Describe how to use SQS and SNS in a “fanout” pattern.**

- To create an SNS Topic and go to the AWS Management Console and navigate to the Amazon SNS service. Click on "Create topic" and provide a name and optional display name for the topic.
Once the topic is created, note down its Amazon Resource Name (ARN), which will be used to subscribe consumers to the topic.
- To create SQS Queues, navigate to the Amazon SQS service in the AWS Management Console. Click on "Create New Queue" to create multiple SQS queues, one for each consumer you want to fan out messages to. Repeat this step for each consumer you have.
- To subscribe SQS Queues to SNS Topic, select an SQS queue that you created in the previous step. Under "Queue Actions," click on "Subscribe Queue to SNS Topic." In the subscription configuration, provide the ARN of the SNS topic you created earlier.
Repeat this step for each SQS queue, subscribing them all to the same SNS topic.
- To publish Messages to the SNS Topic, in your application or system, use the AWS SDK or API to publish messages to the SNS topic.
Messages can be sent in JSON or other supported formats.
The SNS service will distribute the messages to all the subscribed SQS queues.
- To consume Messages from SQS Queues, each consumer can independently retrieve messages from its assigned SQS queue using the AWS SDK or API. Process the messages based on your application logic. Once a consumer retrieves a message, it becomes invisible to other consumers for a specified visibility timeout period. After the timeout, the message becomes visible again and can be consumed by another consumer.

**Explain how “push notifications” work, using SNS.**
Push notifications using SNS (Simple Notification Service) involve the delivery of real-time messages or notifications to subscribers on various platforms, such as mobile devices, web applications, or other endpoints.

- Create an SNS topic and subscribe endpoints (devices or applications) to it. For mobile devices (iOS, Android), integrate SNS with push notification services (APNs, FCM) and register device tokens with SNS. For web applications or other endpoints, subscribe using HTTP/HTTPS protocols and provide endpoint URLs.
- Publishing messages to the SNS topic, you use the AWS SDK or API to send messages in JSON or other formats, including content and metadata.
SNS handles message delivery to all subscribed endpoints based on their protocols.
- With SNS communicates with push notification services or endpoints, for mobile devices, SNS interacts with APNs, FCM, etc.
For web applications or other endpoints, SNS sends HTTP/HTTPS requests directly.
- Endpoint/device/application handles received notifications. Mobile devices display notifications in the notification center, show alerts, play sounds, or update app badges based on the content.
Web applications or other endpoints process the notification based on their platform-specific logic

## SQS and SNS Basics

**How might a large scale, distributed application make use of a Queue system like SQS?**

## Bookmark and Review

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)

## Reflection

**What are your learning goals after reading and reviewing the class README?**
Looking forward to learning about SNS because that is a big thing that we use throughout technology and it will be really interesting building that.
