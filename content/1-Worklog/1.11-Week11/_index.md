---
title: "Week 11 Worklog"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Prepare the AWS resources required for the ReviewSentinel project based on the approved architecture.
* Configure authentication and authorization components using Amazon Cognito and IAM.
* Prepare DynamoDB tables and Amazon S3 buckets for application data.
* Build the foundation for AWS Lambda integration.
* Organize the Terraform project structure for infrastructure deployment.
* Verify the infrastructure configuration before implementation in Week 12.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Prepare AWS Infrastructure** <br> - Review the approved ReviewSentinel architecture <br> - Verify resource relationships between API Gateway, Lambda, DynamoDB and Amazon S3 <br> - Prepare the AWS resources required for implementation | 06/29/2026 | 06/29/2026 | AWS Study Group |
| 3 | **Configure Authentication and IAM** <br> - Configure Amazon Cognito User Pool <br> - Prepare IAM Roles and Policies following the least-privilege principle <br> - Verify JWT authentication flow | 06/30/2026 | 06/30/2026 | AWS Study Group |
| 4 | **Prepare Data Storage Resources** <br> - Create DynamoDB table structures <br> - Prepare Amazon S3 buckets for review storage <br> - Verify event notification configuration | 07/01/2026 | 07/01/2026 | AWS Study Group |
| 5 | **Prepare Lambda Deployment** <br> - Organize Lambda function structure <br> - Configure environment variables <br> - Prepare CloudWatch logging and error handling | 07/02/2026 | 07/02/2026 | AWS Study Group |
| 6 | **Organize Terraform Infrastructure** <br> - Update Terraform providers and modules <br> - Prepare the base infrastructure resources <br> - Verify the deployment workflow | 07/03/2026 | 07/03/2026 | AWS Study Group |

# Week 11 Achievements

## AWS Infrastructure Preparation

- Reviewed the approved ReviewSentinel architecture and verified the relationships between API Gateway, AWS Lambda, Amazon DynamoDB, Amazon S3, Amazon Comprehend, and Amazon Bedrock.
- Prepared the AWS resources required for implementing the project infrastructure.
- Confirmed that the infrastructure layout follows the planned application workflow.

## Authentication and Authorization

- Configured Amazon Cognito User Pool for user authentication.
- Prepared IAM Roles and Policies based on the least-privilege principle for Lambda functions.
- Verified the JWT authentication flow between Amazon Cognito and API Gateway.

## Data Storage Preparation

- Prepared the DynamoDB tables required for storing Reviews, Products, and Users.
- Configured Amazon S3 buckets for storing uploaded review data.
- Verified the event notification configuration between Amazon S3 and AWS Lambda.

## Lambda Preparation

- Organized the Lambda function structure for the project.
- Prepared environment variables and execution settings.
- Configured CloudWatch logging to support monitoring and troubleshooting during implementation.

## Terraform Infrastructure

- Organized the Terraform project structure using providers, variables, and reusable modules.
- Prepared the Infrastructure as Code (IaC) configuration for AWS resources.
- Verified that the deployment workflow is ready for the implementation phase.

### Theory Summary

- **Amazon Cognito** provides secure user authentication and authorization through User Pools and JWT tokens.
- **AWS Lambda** enables serverless application development by executing code in response to AWS events.
- **Amazon DynamoDB** is a fully managed NoSQL database designed for high performance and scalability.
- **Amazon S3** provides durable object storage and can trigger serverless workflows through event notifications.
- **Terraform** enables Infrastructure as Code (IaC), allowing AWS resources to be deployed and managed consistently through reusable configuration files.