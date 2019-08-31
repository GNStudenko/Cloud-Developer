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