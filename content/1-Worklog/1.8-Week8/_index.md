---
title: "Week 8 Worklog"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:

* Master resource tagging strategies for organization and cost tracking.
* Learn advanced IAM techniques with resource tags for fine-grained access control.
* Understand AWS Systems Manager for managing infrastructure at scale.
* Learn session management and remote access to EC2 instances.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Resource Management | **Manage Resources Using Tags and Resource Groups** <br> - Implement tagging strategy <br> - Organize resources using tags <br> - Create resource groups by tags <br> - Track costs using tags | 06/08/2026 | 06/08/2026 | <https://000027.awsstudygroup.com/> |
| Fine-grained Access Control | **Manage Access to EC2 Services with Resource Tags Through IAM Services** <br> - Create tag-based IAM policies <br> - Control resource access using tags <br> - Implement environment-based access (dev, staging, prod) <br> - Audit tag-based access patterns | 06/09/2026 | 06/09/2026 | <https://000028.awsstudygroup.com/> |
| Infrastructure Management | **Manage Patches and Run Commands on Multiple Servers with AWS System Manager** <br> - Set up Systems Manager agent <br> - Create patch policies and patch groups <br> - Run commands across multiple instances <br> - Monitor patch compliance | 06/10/2026 | 06/10/2026 | <https://000031.awsstudygroup.com/> |
| Remote Access | **Work with Amazon System Manager - Session Manager** <br> - Configure Session Manager for secure EC2 access <br> - Create IAM roles for Session Manager <br> - Establish sessions without SSH keys <br> - Monitor and log session activity | 06/11/2026 | 06/11/2026 | <https://000058.awsstudygroup.com/> |

# Week 8 Achievements

## Resource Tagging Strategy
- Implemented a **comprehensive tagging strategy** categorizing resources by environment (dev/staging/prod), project, owner, cost center, and application.
- Organized **large-scale resource inventories** using tags, making resources easily discoverable and manageable.
- Created **resource groups** based on tag filters for logical organization and bulk operations.
- Used **tags for cost allocation**, enabling detailed chargeback and cost tracking by business unit, project, or environment.

## Fine-grained Access Control with Tags
- Created **tag-based IAM policies** allowing permissions based on resource tags rather than resource names or ARNs.
- Implemented **environment-based access control**: developers access only dev resources, QA accesses staging, operations access production.
- Used **condition keys** like `aws:PrincipalTag` and `aws:ResourceTag` for dynamic, scalable permission management.
- Audited **tag-based access patterns** to ensure security policies are correctly enforced and identify anomalies.

## Infrastructure Management at Scale
- Set up **Systems Manager agents** on EC2 instances for management and automation capabilities.
- Created **patch policies** defining patching schedules and patch groups for organized patch management.
- Executed **Run Command** to execute scripts and commands across multiple instances simultaneously, reducing manual configuration effort.
- Monitored **patch compliance** and generated reports showing which instances are up-to-date with security patches.

## Secure Remote Access with Session Manager
- Configured **Session Manager** as a secure alternative to SSH, eliminating the need to manage SSH keys.
- Created **IAM roles with Session Manager permissions** for fine-grained access control to individual instances.
- Established **sessions to EC2 instances** through the AWS console or CLI without exposing instances to the internet.
- Enabled **session logging and monitoring** in CloudTrail and CloudWatch for audit trails and compliance.

### Theory Summary
- **Resource Tags**: Key-value pairs attached to AWS resources for organization, automation, and cost allocation.
- **Tag Strategy**: Systematic approach to tagging defining dimensions (environment, project, owner, cost center, etc.) for consistent resource management.
- **Tag-based IAM Policies**: Condition-based access control using resource and principal tags, enabling scalable permission management without hardcoding resource ARNs.
- **Systems Manager**: Central AWS service for managing infrastructure including patching, automation, and remote access.
- **Session Manager**: Secure remote access tool providing shell access to EC2 instances without SSH keys, with full audit logging.
