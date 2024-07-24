# IaC-for-S3-Event-Notifications-with-AWS-SAM-AWS-CDK-and-Terraform
A notification system that triggers on s3:ObjectCreated:* events. This system will monitor an S3 bucket for new file uploads, trigger a Lambda function to process the uploaded files, send a notification using Simple Notification Service (SNS), and store metadata in a Simple Queue Service (SQS) queue for further processing.

<img width="1311" alt="Screenshot 2024-07-25 at 1 14 53 AM" src="https://github.com/user-attachments/assets/170cd160-f5de-489a-804a-749148564342">



