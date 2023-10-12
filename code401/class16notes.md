# AWS: API, Dynamo and Lambda

## AWS API Gateway Overview

### What is Amazon API Gateway?

Amazon API Gateway is a fully managed service provided by AWS that allows you to create, publish, and manage APIs for your applications. It acts as a front-end service for your backend applications, enabling you to expose your endpoints and microservices securely and easily.

### Why is Amazon API Gateway an important part of the Serverless ecosystem?

Amazon API Gateway is a crucial component of the Serverless ecosystem because it simplifies the process of building, deploying, and scaling serverless applications. It allows you to create HTTP and WebSocket APIs to trigger serverless functions, making it easier to build RESTful or real-time applications without managing traditional servers.

### How does API Gateway integrate with other AWS services?

Amazon API Gateway seamlessly integrates with various AWS services, including AWS Lambda, AWS DynamoDB, AWS Cognito, and more. These integrations enable you to build powerful and scalable serverless applications. For example, you can connect API Gateway to AWS Lambda functions to execute code in response to API requests, or link it with AWS DynamoDB to store and retrieve data. These integrations make it easier to create comprehensive serverless solutions on AWS.

## AWS API Gateway

### What are the some benefits of using Amazon API Gateway?

* **Ease of API Management:** It simplifies the creation, deployment, and management of APIs.
* **Scalability:** It automatically scales to handle varying levels of traffic.
* **Security:** It offers built-in security features like authentication and authorization.
* **Integration:** It easily integrates with various AWS services.
* **Monitoring:** It provides monitoring and analytics for your APIs.
* **Cost-Efficiency:** You only pay for the API calls made, making it cost-effective.

### What two API types might you choose from?

* **RESTful APIs:** Represented in a more structured, HTTP-like way. They are great for exposing resources and actions.
* **WebSocket APIs:** Designed for real-time, bidirectional communication, often used for chat applications or gaming.

## AWS DynamoDB Guide

### What is DynamoDB?

DynamoDB is a managed NoSQL database service provided by AWS (Amazon Web Services). It's designed for high scalability and low-latency performance. DynamoDB is a key-value and document database that can handle large volumes of data with automatic scaling and high availability.

### Under what circumstances would you recommend DynamoDB over MongoDB?

* **When You Need Seamless Scaling:** DynamoDB automatically scales to accommodate increasing workloads without manual intervention, making it a good choice for applications with variable demand.
* **For Serverless and Microservices:** DynamoDB integrates well with serverless and microservices architectures, where you need a managed and easily scalable database.
* **When High Availability Is Critical:** DynamoDB provides high availability and redundancy, making it suitable for applications that require 24/7 uptime.
* **For Simplicity and Low Maintenance:** DynamoDB is fully managed, requiring less administrative overhead compared to self-managed databases like MongoDB.
* **When You Need Predictable Performance:** DynamoDB offers predictable, single-digit millisecond latency, which can be crucial for certain real-time and low-latency applications.

## AWS DynamoDB

### Explain to a non-technical friend how DynamoDB works.

DynamoDB is like a super-fast and organized digital storage where you can save and find your stuff easily, and it makes sure your stuff is always safe.

## Dynamoose

### What is Dynamoose?

Dynamoose is a library for Node.js that simplifies working with Amazon DynamoDB. It's like a helper tool that makes it easier for developers to interact with DynamoDB in their JavaScript applications.

### What are some key features of Dynamoose?

* **Simplified DynamoDB:** Dynamoose provides a more straightforward and user-friendly interface for working with DynamoDB, so you don't have to deal with the nitty-gritty details.
* **Schema Definition:** You can define data schemas for your DynamoDB tables using JavaScript objects, making it easy to manage your data structure.
* **Validation:** Dynamoose helps ensure your data meets certain rules or criteria before it's saved in DynamoDB, which helps maintain data quality.
* **Middleware:** It supports the use of middleware functions to perform actions before or after interacting with DynamoDB, adding flexibility to your code.
* **Integration with Promises:** Dynamoose works well with JavaScript Promises, making it easy to work with asynchronous operations.
* **Compatibility with Mongoose:** If you're familiar with Mongoose (for MongoDB), Dynamoose has a similar interface, so transitioning between databases is more straightforward.
