---
title: "Week 11 Worklog"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Finalize the overall architecture for the ReviewSentinel project.
* Define the security model for the system (authentication, authorization).
* Design the DynamoDB data schema for the application.
* Draft the specification for the core Lambda functions to be implemented.
* Learn about a few additional AWS services related to operations and security.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Finalize the Overall Architecture** <br> - Agree with the team on the ReviewSentinel architecture: edge layer, application layer, processing, AI analysis, monitoring | 06/30/2026 | 06/30/2026 | AWS Study Group |
| 3 | **Define the Security Model** <br> - Define the Cognito authentication flow <br> - Define least-privilege IAM authorization <br> - Define authorization at the API Gateway layer | 07/01/2026 | 07/01/2026 | AWS Study Group |
| 4 | **Design the DynamoDB Schema** <br> - Design the Reviews, Products, and Users tables <br> - Define the query patterns to be used | 07/02/2026 | 07/02/2026 | AWS Study Group |
| 5 | **Draft the Lambda Function Specification** <br> - Detail the functions: review-processor, sentiment-analyzer, API handler <br> - Define the corresponding trigger for each function | 07/03/2026 | 07/03/2026 | AWS Study Group |
| 6 | **Learn Supporting Services** <br> - Learn about EBS Data Lifecycle Manager <br> - Learn about AWS SSO <br> - Learn about IAM Permission Boundaries <br> - Learn about AWS Security Hub | 07/04/2026 | 07/04/2026 | AWS Study Group |

# Week 11 Achievements

## Overall Architecture

- Agreed with the team on the overall ReviewSentinel architecture, consisting of 5 layers: edge, application, processing, AI analysis, and monitoring.

## Security Model

- Defined the user authentication flow via Amazon Cognito.
- Defined the least-privilege approach for IAM authorization.
- Defined authorization at the API Gateway layer.

## DynamoDB Data Schema

- Designed the core tables: Reviews, Products, and Users.
- Defined the query patterns to be used for each table.

## Lambda Function Specification

- Drafted the specification for the 3 core Lambda functions: review-processor, sentiment-analyzer, and API handler.
- Defined the corresponding trigger for each function.

## Additional Learning

- Learned about EBS Data Lifecycle Manager, AWS SSO, IAM Permission Boundaries, and AWS Security Hub.

### Theory Summary

- **Amazon Cognito** provides secure user authentication and management through User Pools and JWT tokens.
- **IAM Least Privilege** is the principle of granting only the permissions each role actually needs, reducing security risk.
- **Amazon DynamoDB** is a fully managed NoSQL database; a well-designed schema helps optimize query performance.
- **AWS Lambda** executes code in response to events, fitting naturally into serverless architectures when triggered by sources such as S3, DynamoDB Streams, or EventBridge.
- **AWS Security Hub** aggregates and evaluates the security posture across an entire AWS account against standards such as CIS and PCI DSS.
