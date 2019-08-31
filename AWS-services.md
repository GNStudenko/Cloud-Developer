# AWS Basics

## Elastic Cloud Compute (EC2)
Provides servers in the cloud, it can grow or shrink (they are elastic) is NOT considered serverless.

An EC2 instance is an EC2 server.

## Elastic Block Store (EBS)
Storage for EC2 instances, physical hdd attached to a server and mount

EBS will allow to persist data after EC2 is shutted down.

Can be HDD or SSD

In memory or instance store is also availalbe (non persistant)

EBS data is automatically replicated withing its AZs (Avalability zone)

## Virtual Private Cloud (VPC) 
To create a private network, a VPC lives between a region and can span across multiple AZs

VPC allows you to control your virtual networking environment, which includes:

* IP address ranges  
* subnets  
* route tables  
* network gateways  

## Lambda
Is a serverless computing technology

Code to execute one single task, limited to 15 minutes

Event-driven code

Lambda supports:
* NodeJS
* Python
* Ruby
* Java
* Go
* .NET

## Elastic Beanstalk
An orchestration service that allows you to deploy a web application at the touch of a button by spinning up (or provisioning) all of the services that you need to run your application.

# Messaging and Containers
 
## Simple Notification Service (SNS)
 A cloud service that allows you to send notifications to the users of your applications. SNS allows you to decouple the notification logic from being embedded in your applications and allows notifications to be published to a large number of subscribers.

* SNS uses a publish/subscribe model.
* SNS can publish messages to Amazon SQS queues, AWS Lambda functions, and HTTP/S webhooks.

SNS Topic names are limited to 256 characters

## Simple Queue Service (SQS)

* FIFO queues support up to 300 messages per second.
* FIFO queues guarantee the ordering of messages.
* Standard queues offer best-effort ordering but no guarantees.
* Standard queues deliver a message at least once, but occasionally more than one copy of a message is delivered.

## Elastic Container Service (ECS)

an orchestration service used for automating deployment, scaling, and managing of your containerized applications. ECS works well with Docker containers
 
 ECS is used for automating deployment, scaling and managing your containerized applications.
 