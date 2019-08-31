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