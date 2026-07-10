---
title: "Week 4 Worklog"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

* Understand managed relational databases with Amazon RDS (Relational Database Service).
* Learn about Amazon Lightsail as a simplified compute solution.
* Explore cost optimization strategies on AWS.
* Master monitoring and logging with AWS CloudWatch.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Database Services | **Amazon Relational Database Service (Amazon RDS)** <br> - Create and configure RDS instances <br> - Set up Multi-AZ deployments for high availability <br> - Configure automated backups and snapshots <br> - Understand read replicas for scaling reads | 05/11/2026 | 05/17/2026 | <https://000005.awsstudygroup.com/> |
| Compute & Cost Optimization | **Amazon Lightsail Workshop - Cost Optimization on AWS** <br> - Launch Lightsail instances <br> - Understand Lightsail pricing model <br> - Compare Lightsail with EC2 <br> - Learn cost optimization strategies | 05/11/2026 | 05/17/2026 | <https://000045.awsstudygroup.com/>|
| Container Services | **Amazon Lightsail Container - Run apps on Lightsail Container** <br> - Deploy containerized applications on Lightsail <br> - Understand container basics <br> - Configure load balancing <br> - Manage container updates | 05/11/2026 | 05/17/2026 | <https://000046.awsstudygroup.com/> |
| Monitoring & Observability | **AWS CloudWatch Workshop** <br> - Create and monitor metrics <br> - Set up alarms for proactive alerting <br> - Use CloudWatch logs for centralized logging <br> - Create dashboards for visualization | 05/11/2026 | 05/17/2026 | <https://000008.awsstudygroup.com/> |

# Week 4 Achievements

## Database Management with RDS
- Launched and configured **Amazon RDS instances** with support for multiple database engines (MySQL, PostgreSQL, MariaDB, Oracle, SQL Server).
- Understood **Multi-AZ deployments** which provide automatic failover and high availability across availability zones.
- Configured **automated backup policies**, point-in-time recovery, and manual snapshots for data protection.
- Explored **read replicas** to distribute read traffic and improve application performance without increasing the primary database workload.

## Simplified Compute with Lightsail
- Deployed **Amazon Lightsail instances** as a user-friendly alternative to EC2, with simpler pricing (fixed monthly cost) and fewer configuration options.
- Compared **Lightsail vs EC2**: Lightsail is better for simple workloads and beginners, while EC2 offers more flexibility for complex architectures.
- Learned cost optimization strategies: right-sizing instances, using reserved capacity, and monitoring unused resources.

## Container Deployment on Lightsail
- Successfully deployed **containerized applications on Lightsail Containers**, simplifying container orchestration without needing Kubernetes.
- Configured **load balancing** to distribute traffic across multiple container instances.
- Understood container image deployment and automatic scaling capabilities.

## Monitoring with CloudWatch
- Created **custom metrics** and monitored key performance indicators (CPU, memory, disk, network, application metrics).
- Set up **CloudWatch alarms** to trigger notifications when metrics exceed defined thresholds, enabling proactive incident response.
- Centralized **application and system logs** using CloudWatch Logs for easier debugging and troubleshooting.
- Built **dashboards** for real-time visualization of multiple metrics and operational visibility.

### Theory Summary
- **RDS**: Managed relational database service handling backups, patching, and high availability, reducing operational overhead.
- **Multi-AZ**: Automatic failover mechanism providing fault tolerance across availability zones.
- **Lightsail**: Simplified compute platform ideal for small projects, WordPress sites, and learning AWS basics.
- **CloudWatch**: Comprehensive monitoring service for metrics, logs, and alarms, essential for operational excellence.
- **Metrics & Alarms**: Enable proactive monitoring and automated responses to infrastructure issues.
