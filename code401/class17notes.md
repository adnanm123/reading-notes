# AWS: Events

## AWS SQS vs SNS

### What is the difference betweeen SQS and SNS?

* **SQS (Simple Queue Service):** SQS is a distributed message queue service. It allows you to decouple the components of a cloud application. Messages are placed in a queue and can be retrieved by one or more consumers, ensuring that each message is processed exactly once. SQS is used for point-to-point communication.

* **SNS (Simple Notification Service):** SNS is a publish-subscribe messaging service. It allows you to send messages to multiple subscribers (endpoints) with a single publish action. Subscribers can receive messages in various ways, such as email, SMS, or HTTP/SQS endpoints. SNS is used for broadcasting messages to multiple consumers.

### What are some use cases for both SNS and SQS?

* **SNS (Simple Notification Service) Use Cases:**

1. **Alerts and Notifications:** Use SNS to send messages to people or systems to notify them about something important.
2. **Distributed Systems:** Use SNS to connect different parts of a system that need to know when something happens.
3. **Fanout Pattern:** Use SNS to share updates with a large group of subscribers, like sending news to many subscribers.

* **SQS (Simple Queue Service) Use Cases:**

1. **Work Queues:** Use SQS to distribute tasks or jobs to workers to be done one at a time.
2. **Decoupling Components:** Use SQS to separate different parts of an application so they can work independently and not slow each other down.
3. **Asynchronous Processing:** Use SQS to handle tasks that can be done later, like sending emails or processing data in the background.

## AWS SNS and SQS

### Describe how to use SQS and SNS in a “fanout” pattern.

* **Fanout Pattern:** SNS sends messages to lots of places at once, like broadcasting a message to many people at the same time. It's like one speaker speaking to a big audience, and everyone hears the same message.

### Explain how “push notifications” work, using SNS.

* **Push Notifications:** SNS can be used to send instant messages to your phone or app, like an alert that something happened. It's like your phone getting a text message when someone sends you a chat message, and you see the notification instantly.

## SQS and SNS Basics

### How might a large scale, distributed application make use of a Queue system like SQS?

* **Task Management:** SQS helps a big application handle many tasks by keeping them in an organized list. It's like a to-do list for the app.

* **Scalability:** When the app gets busier, SQS allows you to easily add more "helpers" (workers) to get tasks done faster, like hiring more people when a job gets bigger.

* **Fault Tolerance:** If one of the "helpers" (workers) can't do a task, SQS ensures the task doesn't get lost and another "helper" can finish it. It's like having a backup plan to avoid losing tasks.
