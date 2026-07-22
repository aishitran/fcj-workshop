---
title: "Week 12 Worklog"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Week 12 Objectives:

* Support the team in completing the remaining infrastructure for the ReviewSentinel project.
* Support deploying and verifying the Lambda functions along with their triggers.
* Take part in reviewing and identifying configuration issues in the pipeline.
* Follow the API Gateway setup and the switch to the real authentication flow.
* Take part in system testing with sample data and help prepare project documentation.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Complete the Remaining Infrastructure** <br> - Support the team in finishing the remaining ReviewSentinel infrastructure components | 07/07/2026 | 07/07/2026 | AWS Study Group |
| 3 | **Deploy Lambda Functions** <br> - Support deploying and verifying the 3 core Lambda functions <br> - Verify the corresponding triggers (S3, DynamoDB Stream, EventBridge) | 07/08/2026 | 07/08/2026 | AWS Study Group |
| 4 | **Review Configuration Issues** <br> - Take part in reviewing the pipeline and identifying configuration issues that came up | 07/09/2026 | 07/09/2026 | AWS Study Group |
| 5 | **API Gateway & Authentication** <br> - Follow the process of building the API Gateway with a Cognito authorizer <br> - Observe and support the switch to a real login flow via Cognito Hosted UI | 07/10/2026 | 07/10/2026 | AWS Study Group |
| 6 | **Testing & Documentation** <br> - Take part in testing the system with sample data <br> - Help prepare the project documentation | 07/11/2026 | 07/11/2026 | AWS Study Group |

# Week 12 Achievements

## Infrastructure Completion

- Supported the team in finishing the remaining infrastructure components for ReviewSentinel.

## Lambda Deployment

- Supported deploying and verifying the 3 core Lambda functions along with their corresponding triggers (S3, DynamoDB Stream, EventBridge).

## Configuration Review

- Took part in reviewing the pipeline and identifying several configuration issues that came up during testing.

## API Gateway & Authentication

- Followed the process of building the API Gateway with a Cognito authorizer.
- Observed and supported the transition to a real login flow via Cognito Hosted UI.

## Testing & Documentation

- Took part in testing the system with sample data.
- Helped prepare the project documentation.

### Theory Summary

- **AWS Lambda Triggers** allow a Lambda function to be automatically invoked in response to events from S3, DynamoDB Streams, or EventBridge.
- **Amazon API Gateway** combined with a **Cognito Authorizer** validates requests before they reach the backend.
- **Cognito Hosted UI** provides a ready-made sign-in/sign-up interface, integrating directly with the OAuth 2.0 flow.
- Reviewing configuration issues (incorrect filter conditions, missing IAM permissions, alarms missing a dimension, etc.) is an important step to ensure the pipeline behaves as designed.
