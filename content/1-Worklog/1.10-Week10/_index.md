---
title: "Week 10 Worklog"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Build complete serverless applications using AWS Lambda, API Gateway, and related services.
* Learn modern application architecture patterns (microservices, event-driven).
* Master authentication and security for serverless applications with Cognito.
* Implement CI/CD pipelines for serverless deployments.
* Set up comprehensive monitoring and debugging for serverless applications.
* Explore GraphQL APIs with AWS AppSync.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Serverless Fundamentals | **Serverless Bookstore: Getting Started with AWS Lambda Functions** <br> - Create Lambda functions for core business logic <br> - Understand Lambda execution environments <br> - Manage function configuration and environment variables <br> - Implement proper error handling and logging | 06/22/2026 | 06/22/2026 | <https://000078.awsstudygroup.com/> |
| API Development | **Serverless - Build Frontend to call API Gateway** <br> - Create REST API endpoints with API Gateway <br> - Configure request/response models <br> - Implement CORS for cross-origin requests <br> - Build frontend applications consuming APIs | 06/23/2026 | 06/23/2026 | <https://000079.awsstudygroup.com/> |
| Infrastructure as Code | **Serverless - Deploying applications with SAM** <br> - Use Serverless Application Model (SAM) for infrastructure definition <br> - Define Lambda, API Gateway, and data resources <br> - Automate deployment pipelines <br> - Manage environment-specific configurations | 06/23/2026 | 06/23/2026 | <https://000080.awsstudygroup.com/> |
| Authentication & Security | **Serverless - Authentication with Amazon Cognito** <br> - Set up Cognito user pools for user management <br> - Implement JWT token validation <br> - Integrate Cognito with API Gateway <br> - Manage user attributes and permissions | 06/24/2026 | 06/24/2026 | <https://000081.awsstudygroup.com/> |
| HTTPS & Security | **Serverless - Setting up SSL for your serverless app** <br> - Configure SSL/TLS certificates with ACM <br> - Set up custom domain names <br> - Implement HTTPS enforcement <br> - Configure security headers | 06/25/2026 | 06/25/2026 | <https://000082.awsstudygroup.com/> |
| Asynchronous Processing | **Serverless - Processing orders with SQS and SNS** <br> - Create SQS queues for decoupled processing <br> - Publish messages to SNS topics <br> - Implement Lambda consumers for async workflows <br> - Handle message batching and error handling | 06/26/2026 | 06/26/2026 | <https://000083.awsstudygroup.com/> |
| CI/CD | **Serverless - CI/CD with AWS CodePipeline** <br> - Design serverless CI/CD pipelines <br> - Integrate source control and build stages <br> - Automate testing and deployment <br> - Implement rollback strategies | 06/27/2026 | 06/27/2026 |<https://000084.awsstudygroup.com/> |
| Monitoring & Debugging | **Serverless - Monitoring Serverless app with CloudWatch and X-Ray** <br> - Configure CloudWatch logs and metrics <br> - Trace Lambda execution with X-Ray <br> - Identify performance bottlenecks <br> - Set up alarms and dashboards | 06/28/2026 | 06/28/2026 | <https://000085.awsstudygroup.com/> |
| API Evolution | **Serverless - Introduction to AWS AppSync** <br> - Design GraphQL schemas <br> - Connect data sources to AppSync <br> - Implement resolvers for queries and mutations <br> - Set up real-time subscriptions | 06/28/2026 | 06/28/2026 | <https://000086.awsstudygroup.com/> |

# Week 10 Achievements

## Serverless Application Foundation
- Created **Lambda functions** implementing business logic for the Bookstore application.
- Understood **Lambda execution environment**, handler functions, and function invocation models.
- Managed **function configuration** including memory, timeout, environment variables, and VPC settings.
- Implemented **comprehensive error handling and logging** using CloudWatch Logs for troubleshooting.

## REST API Development
- Built **REST API endpoints** using Amazon API Gateway with resource-based architecture.
- Configured **request/response models**, validation, and data transformations.
- Implemented **CORS (Cross-Origin Resource Sharing)** headers for secure browser-based API access.
- Connected **frontend applications** to the serverless backend API for interactive user experiences.

## Infrastructure as Code with SAM
- Defined **complete serverless architectures** using AWS SAM (Serverless Application Model) templates.
- Specified **Lambda functions, API Gateway configurations, database resources, and permissions** in declarative YAML.
- Automated **SAM deployments** creating CloudFormation stacks and managing resource lifecycle.
- Managed **environment-specific configurations** for development, staging, and production deployments.

## User Authentication with Cognito
- Set up **Amazon Cognito User Pools** for managing user registration, authentication, and identity.
- Implemented **JWT (JSON Web Token) validation** in API Gateway for secure API access.
- Integrated **Cognito authentication** with serverless applications using OAuth 2.0 flows.
- Managed **user attributes, groups, and permissions** for fine-grained access control.

## HTTPS & SSL Configuration
- Configured **AWS Certificate Manager (ACM) certificates** for secure HTTPS connections.
- Set up **custom domain names** mapped to API Gateway endpoints.
- Enforced **HTTPS** and redirected HTTP traffic, ensuring encrypted communication.
- Implemented **security headers** (HSTS, X-Frame-Options, etc.) for additional security.

## Asynchronous Processing
- Created **SQS (Simple Queue Service) queues** for decoupling Lambda functions and handling spiky traffic.
- Published **messages to SNS (Simple Notification Service) topics** for fan-out messaging patterns.
- Implemented **Lambda consumers** triggered by SQS events for processing orders asynchronously.
- Handled **message batching, visibility timeout, and Dead-Letter Queues** for reliable message processing.

## CI/CD Pipeline Implementation
- Designed and implemented **AWS CodePipeline** for automated serverless application deployment.
- Integrated **source control (GitHub/CodeCommit), build (CodeBuild), and deployment (CodeDeploy)** stages.
- Automated **testing** including unit tests, integration tests, and security scanning in the pipeline.
- Implemented **rollback strategies** for quick recovery from problematic deployments.

## Comprehensive Monitoring
- Configured **CloudWatch Logs** for centralized Lambda function logging and debugging.
- Used **CloudWatch Metrics and Alarms** for proactive monitoring and incident response.
- Enabled **AWS X-Ray tracing** to visualize Lambda execution flows, identify bottlenecks, and understand service dependencies.
- Created **operational dashboards** showing application health, performance, and error rates in real-time.

## GraphQL API with AppSync
- Designed **GraphQL schemas** for flexible and efficient API queries.
- Connected **multiple data sources** (Lambda, RDS, DynamoDB, HTTP) to AppSync for unified API access.
- Implemented **resolvers** translating GraphQL operations to data source queries.
- Set up **real-time subscriptions** for pushing data changes to connected clients.

### Theory Summary
- **Lambda**: Serverless compute service running code in response to events; ideal for building scalable, event-driven applications.
- **API Gateway**: Fully managed service for creating, publishing, and managing REST and WebSocket APIs.
- **SAM**: Infrastructure-as-Code template language simplifying serverless application definition and deployment.
- **Cognito**: User identity and access management service enabling secure authentication and authorization.
- **SQS/SNS**: Message-based services enabling asynchronous, decoupled, scalable communication patterns.
- **X-Ray**: Distributed tracing service providing visibility into Lambda execution and service dependencies.
- **AppSync**: Managed GraphQL service enabling flexible API design and real-time data synchronization.
- **CodePipeline**: Continuous integration and continuous deployment (CI/CD) service automating application release processes.
