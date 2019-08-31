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

# Storage and Content Delivery

## S3 and S3 Glacier
Amazon Simple Storage Service (or S3) is an object storage system in the cloud.

* A single object can be up to 5 terabytes in size.
* You can enable Multi-Factor Authentication (MFA) Delete on an S3 bucket to prevent accidental deletions.
* S3 Acceleration can be used to enable fast, easy, and secure transfers of files over long distances between your data source and your S3 bucket.

S3 Glacier is a secure, durable, and low-cost storage class for data archiving.

## DynamoDB
DynamoDB is a NoSQL document database service that is fully managed. Unlike traditional databases, NoSQL databases, are schema-less. Schema-less simply means that the database doesn't contain a fixed (or rigid) data structure.

* Stores data in JSON
* Is Serverless

## Relational Database Service (RDS)
RDS Supports:
* Oracle
* PostgreSQL
* MySQL
* MariaDB
* SQL Server

## Redshift
Data warehousing to manage big data

## Cloud Front (CDN)
Reduces latency, decreases server load by caching content in an edge location that is close to the user

# Security
## AWS Shield

 A managed DDoS (or Distributed Denial of Service) protection service that safeguards web applications running on AWS.

It is available out of the box and always running as part of the free tier.

## AWS Web Application Firewall (AWS WAF)
WAF can stop common web attacks like:
* SQL Injection
* Cross-site scripting (XSS)

by reviewing the data being sent to your application and stopping well-known attacks.

## Identity & Access Management (IAM)
Identity & Access Management (IAM) is an AWS service that allows us to configure who can access our AWS account, services, or even applications running in our account. IAM is a global service and is automatically available across ALL regions.

NOT NO BE CONFUSED WITH EC2 Security Group

With IAM it is possible to manage:
* Users: Person or service (username and credentials)
* IAM Groups: Collection of users
* IAM Roles: Identity with permissiosn or set of privileges not asociated to users or groups
* Policies: Granular level permissions, can be attached to users, groups or roles. Policies can be written in JSON

# Networking and Elasticity

## Route 53 (Cloud DNS)
Is a cloud domain name system (DNS) service that has servers distributed around the globe 

## Elasticity
EC2, can be scaled up (vertically) this can easily be achieved by stopping an instance and resizing it to an instance type that has more RAM, CPU, IO, or you can scale out (or horizontally), which increases the number of resources. An example would be adding more servers.

## EC2 Auto Scaling
 Is a service that monitors your EC2 instances and automatically adjusts by adding or removing EC2 instances based on conditions you define in order to maintain application availability and provide peak performance to your users.
 
  You can configure EC2 Auto Scaling to send an SNS notification whenever your EC2 Auto Scaling group scales.
  
 ## AWS Auto Scaling
 Similar to EC2 auto scaling but for other services like DynamoDB
 
 ## Elastic Load Balancer
 Automatically distributes incoming application traffic across multiple servers.
 
 Elastic Load Balancing works with EC2 Instances, containers, IP addresses, and Lambda functions.
 
 You can configure Amazon EC2 instances to only accept traffic from a load balancer.


 
 