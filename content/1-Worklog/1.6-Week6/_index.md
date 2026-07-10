---
title: "Week 6 Worklog"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:

* Understand NoSQL databases with Amazon DynamoDB.
* Learn serverless computing with AWS Lambda and cost optimization.
* Master content delivery with CloudFront.
* Optimize application performance and reduce latency globally.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| NoSQL Database | **Work with Amazon DynamoDB** <br> - Create and manage DynamoDB tables <br> - Understand partition keys and sort keys <br> - Configure read/write capacity modes <br> - Learn about global tables for global distribution | 05/25/2026 | 05/25/2026 | <https://000060.awsstudygroup.com/> |
| Serverless & Cost Optimization | **Optimizing EC2 Costs with Lambda** <br> - Create Lambda functions for task automation <br> - Use Lambda to replace or supplement EC2 instances <br> - Understand pay-per-execution pricing model <br> - Optimize function performance and duration | 05/28/2026 | 05/28/2026 | <https://000022.awsstudygroup.com/> |
| Content Delivery | **CloudFront with S3 Bucket Origin** <br> - Create CloudFront distributions <br> - Configure S3 as an origin <br> - Set up caching behaviors and TTLs <br> - Use cache invalidation for content updates | 05/30/2026 | 05/30/2026 | <https://000094.awsstudygroup.com/> |

# Week 6 Achievements

## NoSQL with DynamoDB
- Successfully created and managed **DynamoDB tables** with flexible schema design.
- Understood the importance of **partition keys and sort keys** for efficient data distribution and querying.
- Configured **read/write capacity modes**: provisioned (predictable costs) vs on-demand (pay-per-request for variable workloads).
- Explored **DynamoDB Streams** for capturing changes and triggering other AWS services.
- Learned about **Global Tables** for multi-region replication and low-latency access globally.

## Serverless Computing with Lambda
- Created **AWS Lambda functions** to automate tasks without managing servers.
- Understood how **Lambda pricing** is based on execution count and duration, making it cost-effective for sporadic workloads.
- Used **Lambda to replace or supplement EC2 instances** for tasks like scheduled jobs, data processing, and API endpoints.
- Optimized **function performance** by managing memory allocation, function duration, and dependencies.
- Learned about **Lambda layers** for sharing code across multiple functions and reducing deployment package size.

## Content Delivery with CloudFront
- Created **CloudFront distributions** to cache content closer to end users globally.
- Configured **S3 buckets as origins** for static content delivery with integrated caching.
- Set up **caching behaviors** and time-to-live (TTL) values to balance freshness and performance.
- Used **cache invalidation** to immediately remove stale content when updates are published.
- Understood **edge locations** and how CloudFront improves performance by serving content from servers closest to users.

### Theory Summary
- **DynamoDB**: Fully managed NoSQL database offering single-digit millisecond latency and massive scalability, ideal for real-time applications.
- **Partition Key**: Primary identifier for distributing data across DynamoDB partitions; must be unique and have sufficient cardinality.
- **Lambda**: Serverless compute service that runs code in response to events without provisioning or managing servers.
- **CloudFront**: Content Delivery Network (CDN) that caches and serves content from edge locations worldwide, reducing latency.
- **TTL**: Time-to-Live setting determining how long CloudFront caches content before requesting fresh versions from the origin.
