# AWS CLI
The AWS CLI (or Command Line Interface) allows you to access and control services running in your AWS account from the command line. To use the CLI, simply download, install, and configure it.

[AWL CLI](https://aws.amazon.com/cli/)

### Sample cli commands
```aws s3 ls s3://bucketName```  
```aws sqs receive-message --queue https://queue.url```  
```aws sns publish --topic-arn arn:aws:sns:zone:topicName --message "Thi is my message"```  