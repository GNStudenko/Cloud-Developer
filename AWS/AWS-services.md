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


 