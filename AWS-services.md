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








