# IaC for S3 Event Notifications with AWS SAM, AWS CDK and Terraform
A notification system that triggers on **s3:ObjectCreated:*** events. This system will monitor an S3 bucket for new file uploads, trigger a Lambda function to process the uploaded files, send a notification using Simple Notification Service (SNS), and store metadata in a Simple Queue Service (SQS) queue for further processing.


![final2](https://github.com/user-attachments/assets/38ae37b5-7c74-4b0b-97b5-90deb8010b0e)


## Key Features:

- **Automated Workflow:** Seamlessly trigger Lambda functions, send SNS notifications, and store metadata in an SQS queue upon new file uploads.
- **Multiple IaC Options:** Choose the IaC tool that best suits your project needs (AWS SAM, AWS CDK, or Terraform).
- **Streamlined Dependency Management:** Automated Lambda dependency packaging ensures efficient deployments across all methods.
- **GitHub Actions Integration (CDK):** Simplified deployment and automation for the CDK submodule.

This repository consists of 3 submodules for AWS SAM, AWS, CDK and TErraform

## Submodules:

This monorepo is organized into three subdirectories, each focused on a specific IaC tool:

- **aws-sam:** Implements the S3 event notification system using AWS Serverless Application Model (SAM).
- **aws-cdk:** Employs AWS CDK for infrastructure definition and deployment.
- **terraform:** Leverages Terraform for infrastructure provisioning.

check out the blog post for more details: https://adityadubey.tech/iac-for-s3-event-notifications-with-aws-sam-aws-cdk-and-terraform 








