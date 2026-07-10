---
title: "Week 2 Worklog"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:

* Understand networking concepts in AWS and set up a Virtual Private Cloud (VPC).
* Learn about VPN (Virtual Private Network) and Site-to-Site VPN connections for hybrid connectivity.
* Get familiar with Amazon EC2 (Elastic Compute Cloud) instances and compute resources.
* Learn how to launch, configure, and manage EC2 instances.

### Tasks to be carried out this week:

| Topic | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Networking & VPC | **Amazon VPC and AWS Site-to-Site VPN Workshop** <br> - Set up a Virtual Private Cloud (VPC) <br> - Configure subnets (public and private) <br> - Understand route tables and network ACLs <br> - Learn Site-to-Site VPN for hybrid connectivity | 04/27/2026 | 05/03/2026 | <https://000003.awsstudygroup.com/> |
| Compute | **Introduction to Amazon EC2** <br> - Launch EC2 instances <br> - Understand EC2 instance types and families <br> - Configure security groups and key pairs <br> - Monitor EC2 instances and manage storage | 04/27/2026 | 05/03/2026 | <https://000004.awsstudygroup.com/> |

# Week 2 Achievements

## VPC and Networking
- Successfully set up a Virtual Private Cloud (VPC) with proper subnets and routing configurations.
- Understood how to configure **public and private subnets** to control traffic flow and improve security.
- Learned about **Security Groups** (stateful firewall) and **Network ACLs** (stateless firewall) as layers of network protection.
- Explored **Site-to-Site VPN** connections, which allow secure communication between on-premises networks and AWS infrastructure, essential for hybrid cloud architectures.

## EC2 Fundamentals
- Launched and configured **Amazon EC2 instances**, the core compute service in AWS.
- Understood **instance types** (t2, t3, m5, c5, etc.) and how to choose the right type based on workload requirements (compute-optimized, memory-optimized, general purpose, etc.).
- Learned about **key pairs** for SSH access and **security groups** for controlling inbound/outbound traffic.
- Gained hands-on experience with instance lifecycle management (launch, stop, terminate) and monitoring through AWS Management Console.

### Theory Summary
- **VPC**: An isolated network environment in AWS where you can launch resources with full control over IP addressing, subnets, and routing.
- **Site-to-Site VPN**: Encrypted connection between on-premises networks and VPC, enabling hybrid cloud scenarios.
- **EC2**: Provides scalable virtual machines (instances) with various configurations for different workload types.
- **Security Groups**: Acts as a virtual firewall controlling inbound and outbound traffic at the instance level.
