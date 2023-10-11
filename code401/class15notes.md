# AWS: S3 and Lambda

## AWS S3

## What is Amazon S3?

Amazon S3 (Simple Storage Service) is a scalable and highly durable cloud storage service provided by Amazon Web Services (AWS). It allows users to store and retrieve data, such as files, images, and videos, over the internet. S3 is designed for reliability, security, and flexibility in managing data.

## Name some use cases for Amazon S3.

* **Data Backup:** Storing backups of data, databases, and server configurations.
* **Static Website Hosting:** Hosting static websites and assets like HTML, CSS, and JavaScript files.
* **Data Archiving:** Archiving old data, logs, and records for compliance and long-term storage.
* **Media Storage:** Storing and serving multimedia content like images, videos, and audio files.
* **Data Analytics:** Storing and analyzing large datasets for data analytics and machine learning.
* **Content Distribution:** Using S3 in combination with Amazon CloudFront for content distribution and content delivery networks (CDNs).
* **Data Sharing:** Sharing files and data with colleagues and clients using pre-signed URLs.
* **Mobile and IoT Applications:** Storing data and assets for mobile apps and Internet of Things (IoT) devices.

## Name some benefits of using Amazon S3.

* **Scalability:** Amazon S3 can store virtually unlimited amounts of data, scaling to meet your storage needs.
* **Durability:** Data stored in S3 is redundantly stored across multiple data centers, ensuring high data durability.
* **Security:** S3 offers robust security features like access control, encryption, and identity management.
* **Flexibility:** S3 supports various storage classes, allowing you to optimize costs based on your data access patterns.
* **Low Latency:** It provides low-latency data retrieval, making it suitable for various applications.
* **Versioning:** S3 supports versioning, allowing you to track changes and recover previous versions of objects.
* **Content Delivery:** When combined with Amazon CloudFront, S3 enables efficient content delivery to users worldwide.
* **Cost-Effective:** S3 offers a pay-as-you-go pricing model, so you only pay for the storage and data transfer you use.

## AWS Lambda Basics

## What is AWS Lambda?

AWS Lambda is like a magic computer that runs your code without needing you to manage a server. You just give it your code, and it runs when needed, automatically.

## Name some use cases for AWS Lambdas.

* **Image Resizing:** Automatically resize images when they're uploaded to a website.
* **Data Processing:** Process and transform data from one format to another.
* **Scheduled Tasks:** Run tasks at specific times, like backups or sending emails.
* **APIs:** Create small, on-demand functions for building web services.
* **IoT:** Handle data from Internet of Things devices, like sensors and smart devices.

## Describe “serverless” to a non-technical friend.

Think of "serverless" like ordering pizza. You don't need to worry about the kitchen or the oven; you just order your pizza, and it arrives at your door when it's ready. With serverless technology, you don't need to worry about servers or computers; you just send your code, and it runs when needed. It's like magic, making it simpler and more convenient for developers.

## CDN

## What is a CDN?

A CDN, or Content Delivery Network, is like a helper for websites. It's a big network of super-fast computers all over the world that store and share website stuff like images, videos, and web pages. This makes websites load faster and work better.

## How does a CDN work with relation to the website visitor?

When you visit a website that uses a CDN, the CDN does a special job. Instead of your computer asking the website's main server far away for everything, it asks the CDN's computer nearby. The CDN's computer gives you the website stuff quickly because it's closer to you. This makes the website load much faster for you.

## What are the benefits of employing a CDN?

* **Faster Loading:**  Websites load quickly for visitors because the CDN serves content from nearby servers.
* **Better Performance:** CDN reduces the strain on the main server, improving website speed and reliability.
* **Improved Security:** CDNs can help protect websites from certain kinds of cyberattacks.
* **Global Reach:** Websites become accessible to visitors worldwide with consistent performance.
* **Cost Savings:** CDNs can reduce the bandwidth costs for website owners.
* **Scalability:** CDNs can handle spikes in traffic, like during viral events or sales, without crashing the website.
* **Caching:** CDNs store website content, reducing the load on the main server and saving resources.
