# AWS 

## What is AWS LAMBDA:
AWS Lambda is an event-driven computing cloud service from Amazon Web Services that allows developers to program functions on a pay-per-use basis without having to provision storage or compute resources to support them. This is sometimes referred to function-as-a-service (FaaS).



## Benefits of AWS LAMBDA:
One of the main benefits of AWS Lambda is that it abstracts server management away from the IT professional. With AWS Lambda, Amazon manages the servers, which allows a developer to focus more on writing application code.
![alt text](https://github.com/anjanpaul/AWS/blob/main/Output/lambda.png)

AWS supports code written in a variety of programming languages. AWS Lambda languages include Node.js, Python, Java and C#. Developers can also use code compiler tools, such as Maven or Gradle, and packages to build functions.

## What is AWS API Gateway:
It’s a fully managed service that provides all the necessary tools for developers in order to create, publish, manage and secure your API regarding of scale. Amazon API Gateway will take care of all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, authorization and access control, monitoring, and API version management.

Deployable with a couple of clicks, your Amazon API Gateway will act as the single point of entry to your backend services and will handle the data management, business logic or any other type of functionality or workloads running on services like EC2, AWS Lambda and many more.
![alt text](https://github.com/anjanpaul/AWS/blob/main/Output/apigateway.png)

## AWS Amplify 

AWS Amplify is an open source JavaScript library provided by Amazon Web Services (AWS) that enables developers to build applications with cloud services on web or mobile platforms.

AWS Amplify aims to both enable apps to scale via cloud services and accelerate them to production.

Under Apache License, a developer can use the AWS Amplify declarative API to integrate cloud-based services into their applications. Some of these services, which support automatic and manual setup options, include user authentication, content management, push notifications and analytics.

![alt text](https://github.com/anjanpaul/AWS/blob/main/Output/amplify.png)
## AWS CodePipeline:

A continuous delivery service that enables IT teams to define the steps and workflows required to release software. For example, deploy software packages to dev and staging environments first, where a series of tests and scans are run, before it's released to production instances.


## AWS CodeBuild

A continuous integration service that builds and compiles source code, runs a predefined set of tests and generates artifacts as deployable software.

## AWS CodeCommit:

A source control service on AWS that hosts private Git repositories and works seamlessly with existing Git-based tools. Because it is available on AWS portal as a hosted platform, developers can also use the console version to collaborate and commit, branch and perform other operations on the code repositories from a web UI.

## AWS CodeBuild:

A continuous integration service that builds and compiles source code, runs a predefined set of tests and generates artifacts as deployable software.
![alt text](https://github.com/anjanpaul/Portainer-ECR/blob/main/Output/Screenshot%202022-02-10%20at%2011.11.37%20AM.png)

## Amazon CloudWatch:

 A monitoring and observability service that automatically collects data and metrics from most of AWS' services, like EC2, S3 and Amazon Relational Database Service instances. Developers can also define custom metrics to be collected from any AWS resource. CloudWatch enables users to set up alarms, as well as auto scale and run an AWS Lambda function if an alarm is triggered.
 ![alt text](https://github.com/anjanpaul/AWS/blob/main/Output/cloudwatch.png)

 ## What is Amazon S3:

 Amazon Simple Storage Service (Amazon S3) is a scalable, high-speed, web-based cloud storage service. The service is designed for online backup and archiving of data and applications on Amazon Web Services (AWS). Amazon S3 was designed with a minimal feature set and created to make web-scale computing easier for developers.

## Amazon S3 features:

S3 provides 99.999999999% durability for objects stored in the service and supports multiple security and compliance certifications. An administrator can also link S3 to other AWS security and monitoring services, including CloudTrail, CloudWatch and Macie. There's also an extensive partner network of vendors that link their services directly to S3.

Data can be transferred to S3 over the public internet via access to S3 application programming interfaces (APIs). There's also Amazon S3 Transfer Acceleration for faster movement over long distances, as well as AWS Direct Connect for a private, consistent connection between S3 and an enterprise's own data center. An administrator can also use AWS Snowball, a physical transfer device, to ship large amounts of data from an enterprise data center directly to AWS, which will then upload it to S3.
![alt text](https://github.com/anjanpaul/AWS/blob/main/Output/s3.png)

## Amazon Simple Notification Service (Amazon SNS):

Amazon Simple Notification Service (SNS) is a cloud service for coordinating the delivery of push messages from software applications to subscribing endpoints and clients. All messages published to Amazon SNS are warehoused across several availability zones to prevent loss.

Amazon SNS allows users to push messages to Windows, Google, Apple and certain internet-connected smart devices by using an application programming interface (API) or the AWS Management Console. Once a message is published to the service, it can be sent multiple times to different recipients. Service users also have the flexibility to send direct messages to several devices or to one subscriber by using a sole publish request.

To get started with Amazon SNS, developers first have to create a topic, which is an access point for subscribers who are interested in receiving notifications about a specific subject. Developers publish a message to a topic when they have an update for subscribers and this action prompts Amazon SNS to distribute the message to all appropriate subscribers.

Amazon SNS has pay-as-you-go-pricing and no upfront costs. Users who sign up for AWS Free Tier receive 1 million mobile push notifications. Topic owners are able to set policies specifying which types of protocols will be supported. They can also be used to limit who can subscribe to notifications or publish messages. The subscribers, who are also called clients, can choose how notifications will be delivered.

## Amazon Simple Email Service (Amazon SES):

Amazon Simple Email Service is a pay-per-use service that allows you to build in email functionality into an application that you are running on AWS.

Using SMTP or a simple API call, this service offers high rate of email deliverability and easy, immediate access to your email-sending statistics. It also provides built-in notifications for successful and unsuccessful email deliveries and complaints. Amazon SES can send bounce-back and complaint messages by email or through Amazon Simple Notification Service.

Amazon SES offers a mailbox simulator that tests how your application will handle different possible email-sending situations, like a hard bounce, an out-of-office auto response, a complaint or a successful email acceptance. Because these test messages are received by Amazon SES and not actual email recipients, bounce and complaint rates aren’t affected. Another use for the simulator is to find out your system’s maximum throughput without using up your daily sending quota.

You can use Amazon SES if you’re an Amazon EC2 user who requires an email-sending service. Email capabilities can be added to any application running on an EC2 instance and users are eligible for the Free Usage Tier if they send emails directly from an Amazon EC2 instance or through AWS Elastic Beanstalk.