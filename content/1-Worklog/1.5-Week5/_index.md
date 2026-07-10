---
title: "Week 5 Worklog"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:

* Master DNS services with Route 53 and hybrid DNS setup.
* Develop proficiency with AWS CLI for infrastructure automation.
* Learn about ElastiCache for in-memory caching and performance improvement.
* Understand database migration strategies and tools.
* Explore disaster recovery capabilities on AWS.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| DNS & Hybrid Connectivity | **Set up Hybrid DNS with Route 53 Resolver** <br> - Configure Route 53 hosted zones <br> - Set up Route 53 Resolver for hybrid DNS <br> - Create DNS failover policies <br> - Understand DNS routing policies | 05/18/2026 | 05/24/2026 | <https://000010.awsstudygroup.com/> |
| Infrastructure Automation | **Getting Started with the AWS CLI** <br> - Master AWS CLI command structure <br> - Automate EC2, S3, and RDS operations <br> - Configure profiles and credentials <br> - Write scripts for infrastructure management | 05/18/2026 | 05/24/2026 | <https://000011.awsstudygroup.com/> |
| Caching & Performance | **Amazon ElastiCache - Redis** <br> - Deploy Redis clusters <br> - Understand caching patterns and strategies <br> - Configure replication and failover <br> - Monitor cache performance | 05/18/2026 | 05/24/2026 | <https://000061.awsstudygroup.com/> |
| Data Migration | **Database Schema Conversion & Migration** <br> - Assess migration readiness <br> - Convert database schemas between engines <br> - Migrate data with minimal downtime <br> - Validate data integrity post-migration | 05/18/2026 | 05/24/2026 | <https://000043.awsstudygroup.com/> |
| Disaster Recovery | **AWS Elastic Disaster Recovery Workshop** <br> - Understand RTO and RPO concepts <br> - Set up replication and failover <br> - Create disaster recovery plans <br> - Test recovery procedures | 05/18/2026 | 05/24/2026 | <https://000100.awsstudygroup.com/> |

# Week 5 Achievements

## DNS Management with Route 53
- Successfully configured **Route 53 hosted zones** and DNS records for domain management.
- Set up **Route 53 Resolver** to enable hybrid DNS resolution between on-premises networks and AWS VPCs.
- Learned **DNS failover policies** for automatic failover to healthy endpoints when primary resources become unavailable.
- Understood various **routing policies** (simple, weighted, latency-based, failover, geolocation) for sophisticated traffic management.

## AWS CLI Proficiency
- Mastered **AWS CLI command structure** and became comfortable with command-line infrastructure management.
- Automated operations across **EC2, S3, RDS, and other services** using CLI commands, improving efficiency and reducing manual errors.
- Configured **multiple profiles and credentials** for managing different AWS accounts and roles from a single CLI.
- Created **automation scripts** for repetitive tasks like instance management, backup scheduling, and security group updates.

## In-Memory Caching with ElastiCache
- Deployed **Redis clusters** on Amazon ElastiCache to provide fast, in-memory data access.
- Understood **caching patterns** (cache-aside, write-through, write-behind) and when to apply each strategy.
- Configured **replication and failover** to ensure high availability of cache layer.
- Monitored **cache hit ratio and eviction policies** to optimize cache performance and cost.

## Database Migration Strategies
- Assessed migration readiness using **AWS Database Migration Service (DMS)** assessment reports.
- Converted **database schemas** between different engines (e.g., Oracle to PostgreSQL) using schema conversion tools.
- Performed **data migration with minimal downtime** using continuous replication features.
- Validated **data integrity** post-migration through comparison and testing procedures.

## Disaster Recovery Planning
- Understood critical disaster recovery metrics: **RTO** (Recovery Time Objective) and **RPO** (Recovery Point Objective).
- Configured **AWS Elastic Disaster Recovery** to continuously replicate on-premises or non-AWS workloads to AWS.
- Created **disaster recovery plans** and defined automated failover procedures.
- Tested recovery procedures to ensure reliability and team preparedness.

### Theory Summary
- **Route 53**: AWS's managed DNS service providing domain registration, DNS hosting, and health-based routing.
- **AWS CLI**: Command-line interface for programmatic access to AWS services, enabling infrastructure-as-code approaches.
- **ElastiCache**: Managed in-memory cache service (Redis or Memcached) for reducing database load and improving application performance.
- **Database Migration**: Moving data from legacy systems to AWS with considerations for schema conversion, downtime minimization, and validation.
- **Disaster Recovery**: Strategies and tools for recovering from failures, with metrics like RTO and RPO defining recovery objectives.
