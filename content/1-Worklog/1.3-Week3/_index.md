---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:

* Learn AWS Identity and Access Management (IAM) and security best practices.
* Understand how to grant applications access to AWS services using IAM roles.
* Get started with Amazon S3 (Simple Storage Service) for object storage.
* Learn about S3 buckets, permissions, and data management.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Identity & Access Management | **Granting authorization for an application to access AWS services with an IAM role** <br> - Create IAM roles and policies <br> - Understand the principle of least privilege <br> - Assign roles to EC2 instances <br> - Configure cross-account access | 05/04/2026 | 05/10/2026 | <https://000048.awsstudygroup.com/> |
| Object Storage | **Starting with Amazon S3** <br> - Create and configure S3 buckets <br> - Upload and manage objects <br> - Configure bucket policies and ACLs <br> - Enable versioning and static website hosting | 05/04/2026 | 05/10/2026 | <https://000057.awsstudygroup.com/> |

# Week 3 Achievements

## Identity & Access Management
- Successfully created **IAM roles** and attached **policies** to grant applications permission to access AWS services.
- Understood the critical security principle of **least privilege** - giving users/services only the minimum permissions needed for their tasks.
- Learned how to attach **IAM roles to EC2 instances**, allowing applications running on those instances to access other AWS services (S3, RDS, etc.) without storing credentials.
- Explored **trust relationships** and how to enable cross-account access for more complex architectures.

## Amazon S3 Fundamentals
- Set up **S3 buckets** as containers for storing objects (files) in AWS.
- Learned about **S3 storage classes** and when to use different tiers for cost optimization.
- Configured **bucket policies** (resource-based permissions) and **ACLs** (Access Control Lists) to control who can access objects.
- Enabled **versioning** to maintain multiple versions of objects for data protection and recovery.
- Explored **static website hosting** capability to serve websites directly from S3 buckets.

### Theory Summary
- **IAM**: Identity and Access Management service for controlling who can do what with AWS resources, using users, groups, roles, and policies.
- **IAM Roles**: Temporary credentials granted to services/applications, safer than storing long-lived access keys.
- **S3 Buckets**: Globally unique containers for storing objects, with comprehensive permission and configuration options.
- **Least Privilege**: Security best practice of granting only the minimum necessary permissions to perform a task.
- **S3 Versioning**: Maintains multiple versions of objects, providing protection against accidental deletion.
