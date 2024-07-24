# IaC-for-S3-Event-Notifications-with-AWS-SAM-AWS-CDK-and-Terraform
A notification system that triggers on s3:ObjectCreated:* events. This system will monitor an S3 bucket for new file uploads, trigger a Lambda function to process the uploaded files, send a notification using Simple Notification Service (SNS), and store metadata in a Simple Queue Service (SQS) queue for further processing.

<img width="1262" alt="Screenshot 2024-07-25 at 1 14 53 AM" src="https://github.com/user-attachments/assets/2f2b6602-06f0-4cc3-a1e4-4b591b3cca05">




