---
title: "Week 11 Worklog"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Understand the overall ReviewSentinel system architecture and assigned AWS services.
* Study authentication and authorization using Amazon Cognito and IAM.
* Review the DynamoDB data model and event-driven workflow.
* Learn the responsibilities of Lambda functions within the project.
* Prepare the Terraform development environment for infrastructure deployment.
* Get ready for implementing the application infrastructure in Week 12.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Review ReviewSentinel System Architecture** <br> - Study the interaction between API Gateway, Lambda, DynamoDB, S3, Comprehend, and Bedrock <br> - Understand the overall request and processing flow <br> - Identify AWS resources assigned for implementation | 06/29/2026 | 06/29/2026 | AWS Study Group |
| 3 | **Study Authentication and Authorization** <br> - Learn Amazon Cognito User Pools <br> - Review JWT authentication flow with API Gateway <br> - Understand IAM least-privilege permissions for Lambda functions | 06/30/2026 | 06/30/2026 | AWS Study Group |
| 4 | **Review Database Design** <br> - Analyze DynamoDB table structures <br> - Study partition keys, sort keys, and access patterns <br> - Understand S3 event notifications and processing workflow | 07/01/2026 | 07/01/2026 | AWS Study Group |
| 5 | **Study AWS Lambda Design** <br> - Review Lambda function responsibilities <br> - Understand event sources and execution flow <br> - Learn CloudWatch logging and error handling | 07/02/2026 | 07/02/2026 | AWS Study Group |
| 6 | **Prepare Terraform Development Environment** <br> - Configure Terraform locally <br> - Review provider, variables, and module structure <br> - Verify the deployment workflow for AWS resources | 07/03/2026 | 07/03/2026 | AWS Study Group |

# Week 11 Achievements

## System Architecture Review

- Reviewed the overall **ReviewSentinel** architecture to understand how each AWS service interacts within the application.
- Identified the responsibilities of API Gateway, AWS Lambda, Amazon DynamoDB, Amazon S3, Amazon Comprehend, and Amazon Bedrock in the complete workflow.
- Gained a clear understanding of the end-to-end request flow from user submission to sentiment analysis and result storage.

## Authentication and Security

- Studied **Amazon Cognito** authentication and user management.
- Understood how **JWT tokens** are validated through API Gateway authorization.
- Reviewed the **IAM least-privilege** principle and how Lambda functions receive only the permissions required for their assigned tasks.

## Database and Event-driven Workflow

- Analyzed the DynamoDB data model, including **Reviews**, **Products**, and **Users** tables.
- Learned the expected access patterns used by the application to improve query efficiency.
- Understood how **Amazon S3 event notifications** trigger Lambda functions for automatic review processing.

## AWS Lambda Preparation

- Reviewed the responsibilities of the project's Lambda functions and their execution flow.
- Learned how Lambda integrates with API Gateway, DynamoDB Streams, and Amazon S3.
- Studied CloudWatch logging and basic error-handling practices for serverless applications.

## Terraform Environment Setup

- Prepared the local **Terraform** development environment.
- Reviewed the project structure, including providers, variables, and reusable modules.
- Verified the workflow for provisioning AWS infrastructure using Infrastructure as Code (IaC).

### Theory Summary

- **Amazon Cognito** provides user authentication and authorization using managed user pools and JWT tokens.
- **AWS Lambda** enables serverless execution based on events from services such as API Gateway, Amazon S3, and DynamoDB Streams.
- **Amazon DynamoDB** is a fully managed NoSQL database optimized through partition keys, sort keys, and efficient access patterns.
- **Terraform** is an Infrastructure as Code (IaC) tool that automates AWS resource provisioning through reusable configuration files.
- **Event-driven architecture** allows AWS services to communicate asynchronously, enabling scalable and loosely coupled applications.