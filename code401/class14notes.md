# Readings: AWS: Cloud Servers

## AWS EC2

## What is an EC2 Instance?

An EC2 (Elastic Compute Cloud) instance is a virtual server offered by Amazon Web Services (AWS). It provides scalable computing capacity in the cloud and allows users to run applications, host websites, and perform various computing tasks without the need to manage physical hardware.

## Name 2 use cases for EC2.

* **Web Hosting:** EC2 instances can be used to host websites and web applications. Users can choose instance types based on their resource requirements and scale up or down as needed.

* **Data Processing:** EC2 is commonly used for data processing tasks, such as batch processing, data analytics, and machine learning. Users can launch instances with suitable configurations to process large datasets efficiently.

## Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

One reason to use AWS Elastic Container Service (ECS) over platform-as-a-service (PaaS) providers like Heroku, Digital Ocean, or Render.com is **greater control and flexibility**. ECS allows users to manage and orchestrate containers using Docker, providing fine-grained control over containerized applications. This is beneficial for complex, customized deployments where specific configurations or dependencies are required, making ECS a preferred choice for organizations with unique infrastructure needs. PaaS providers, while user-friendly, may offer less flexibility in terms of container management and customization.

## EC2 For Humans

## Where can we find EC2 on the AWS Console?

You can find EC2 on the AWS Console by following these steps:

* Log in to your AWS account.
* Once logged in, go to the "Services" menu at the top left.
* Under "Compute," you'll find "EC2." Click on it to access the EC2 dashboard.

## Explain the general difference between T2 Micro and XL.

T2 Micro and XL are types of EC2 instances on AWS. The main difference between them is their size and computing power:

* **T2 Micro:** This is a small, low-cost instance suitable for lightweight applications and testing. It has a limited amount of CPU and memory resources.
* **XL (Extra Large):** XL instances are larger and more powerful, designed for resource-intensive applications. They provide more CPU and memory capacity compared to T2 Micro, making them suitable for demanding workloads.

## Explain a “Compute Cycle” to a non-technical friend.

A "compute cycle" is like a small unit of work that a computer does. Imagine your computer is like a chef in a kitchen. When you ask the chef to chop vegetables, that's one compute cycle. If you then ask the chef to cook the chopped vegetables, that's another compute cycle. So, a compute cycle is just a way to measure how much work a computer does, like counting how many tasks the chef completes in the kitchen.

## Elastic Beanstalk

## What is Elastic Beanstalk?

Elastic Beanstalk is a Platform-as-a-Service (PaaS) offered by Amazon Web Services (AWS) that simplifies the deployment, scaling, and management of web applications and services. It provides a platform where developers can upload their code, and Elastic Beanstalk handles the infrastructure provisioning, deployment, and monitoring, allowing developers to focus on writing code.

## Describe the relationship between EC2 and Elastic Beanstalk.

Elastic Beanstalk leverages Amazon EC2 instances as part of its underlying infrastructure. When you deploy an application using Elastic Beanstalk, it automatically provisions and manages EC2 instances to run your application. These EC2 instances serve as the hosting environment for your web application. Elastic Beanstalk abstracts many of the complexities of directly managing EC2 instances, making it easier to deploy and manage applications.

## Name some benefits of using Elastic Beanstalk.

* **Simplicity:** Elastic Beanstalk simplifies the deployment process by handling infrastructure provisioning, load balancing, scaling, and application monitoring.
* **Scalability:** It can automatically scale your application up or down based on traffic, ensuring optimal performance and cost-efficiency.
* **Monitoring:** Provides built-in monitoring and dashboards for application health and performance.
* **Easy Updates:** Allows for easy application updates and rollbacks, ensuring seamless deployments.
* **Support for Multiple Languages:** Supports various programming languages and frameworks, making it versatile for different types of applications.
* **Integrated Services:** Seamlessly integrates with other AWS services like RDS (Relational Database Service), S3 (Simple Storage Service), and more, enhancing your application's capabilities.
