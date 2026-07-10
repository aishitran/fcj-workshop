---
title: "Week 9 Worklog"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Understand Infrastructure as Code (IaC) concepts and AWS CDK fundamentals.
* Learn how to provision AWS infrastructure using AWS Cloud Development Kit (CDK).
* Understand how to select appropriate EC2 instance types for different workloads.
* Monitor AWS network infrastructure using CloudWatch.
* Manage billing access securely with IAM.
* Learn AWS service quotas and quota increase requests.
* Explore resource usage monitoring and cost management using IAM and AWS billing services.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Infrastructure as Code | **CDK Basic – 2** <br> - Create infrastructure using AWS CDK <br> - Understand stacks and constructs <br> - Deploy infrastructure with CDK CLI <br> - Manage CloudFormation resources | 06/15/2026 | 06/15/2026 | <https://000076.awsstudygroup.com/> |
| Infrastructure as Code | **Introduction to Infrastructure as Code** <br> - Understand IaC concepts and benefits <br> - Compare manual provisioning with automated deployment <br> - Learn infrastructure version control <br> - Improve deployment consistency | 06/16/2026 | 06/16/2026 | <https://000102.awsstudygroup.com/> |
| EC2 Optimization | **Choose the correct EC2 size** <br> - Compare EC2 instance families <br> - Select appropriate instance types for workloads <br> - Balance performance and cost <br> - Apply EC2 sizing best practices | 06/17/2026 | 06/17/2026 | <https://000032.awsstudygroup.com/> |
| Monitoring | **Monitor network infrastructure** <br> - Monitor network performance with CloudWatch <br> - Analyze network metrics <br> - Configure monitoring dashboards <br> - Detect networking issues | 06/18/2026 | 06/18/2026 | <https://000074.awsstudygroup.com/> |
| Billing & IAM | **Delegate access to the billing console** <br> - Enable IAM access to Billing Console <br> - Grant billing permissions securely <br> - Apply least privilege principle | 06/19/2026 | 06/19/2026 | <https://000075.awsstudygroup.com/> |
| Service Quotas | **Requesting a quota increase** <br> - Understand AWS Service Quotas <br> - Identify quota limitations <br> - Submit quota increase requests | 06/20/2026 | 06/20/2026 | <https://000063.awsstudygroup.com/> |
| Cost Management | **Resource Usage and Cost Management with IAM on AWS** <br> - Monitor AWS resource usage <br> - Control access to billing information with IAM <br> - Understand cost management best practices <br> - Improve resource governance | 06/21/2026 | 06/21/2026 | <https://000064.awsstudygroup.com/> |

# Week 9 Achievements

## Infrastructure as Code with AWS CDK
- Learned the fundamentals of **Infrastructure as Code (IaC)** and its advantages over manual infrastructure provisioning.
- Created AWS infrastructure using **AWS Cloud Development Kit (CDK)** by organizing resources into stacks and constructs.
- Understood how AWS CDK synthesizes infrastructure definitions into AWS CloudFormation templates.
- Deployed and managed cloud resources using the AWS CDK CLI.

## Infrastructure Automation
- Understood the importance of infrastructure versioning, consistency, and repeatable deployments.
- Learned how Infrastructure as Code improves automation, reduces configuration drift, and simplifies infrastructure maintenance.
- Compared manual infrastructure deployment with automated provisioning approaches.

## EC2 Instance Optimization
- Compared different **Amazon EC2 instance families** for compute, memory, storage, and general-purpose workloads.
- Selected appropriate EC2 instance types based on workload requirements.
- Evaluated performance and cost considerations when choosing EC2 instance sizes.
- Applied EC2 sizing best practices to optimize cloud resource utilization.

## Network Monitoring
- Monitored network infrastructure using **Amazon CloudWatch** metrics.
- Observed network performance indicators to identify potential bottlenecks.
- Configured monitoring dashboards for infrastructure visibility.
- Improved understanding of network performance monitoring and operational health.

## Billing Access Management
- Enabled IAM user access to the **AWS Billing Console**.
- Configured billing permissions following the principle of least privilege.
- Understood how delegated billing access improves account security and administration.

## AWS Service Quotas
- Learned how AWS Service Quotas define resource limits across AWS services.
- Identified quota limitations that may affect application deployment.
- Understood the process of requesting service quota increases when additional capacity is required.

## Resource Usage and Cost Management
- Explored AWS resource usage monitoring and cloud cost management practices.
- Understood how IAM permissions help protect billing and cost management resources.
- Learned best practices for monitoring AWS resource utilization and controlling cloud costs.
- Improved awareness of governance strategies for efficient AWS resource management.

### Theory Summary

- **Infrastructure as Code (IaC):** The practice of managing and provisioning infrastructure through code instead of manual configuration.
- **AWS CDK:** A development framework that allows cloud infrastructure to be defined using programming languages and deployed through AWS CloudFormation. :contentReference[oaicite:1]{index=1}
- **Amazon EC2 Instance Types:** Different instance families designed for general-purpose, compute-optimized, memory-optimized, storage-optimized, and specialized workloads.
- **Amazon CloudWatch:** Monitoring service used to collect metrics, logs, and alarms for AWS resources.
- **AWS Billing Console:** Centralized dashboard for viewing AWS usage, billing information, and cost management.
- **AWS Service Quotas:** Service limits that define the maximum number of AWS resources available within an account or Region.
- **IAM for Cost Management:** IAM policies can be used to securely delegate access to billing and cost management resources while following the principle of least privilege.