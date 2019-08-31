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