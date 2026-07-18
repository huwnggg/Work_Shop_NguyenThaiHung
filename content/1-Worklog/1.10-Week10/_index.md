---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:
* Launch the Genzite Capstone Project: Analyze system architecture and organize cloud resources.
* Provision foundational network resources (VPC, Subnets, Route Tables, Internet Gateways, NAT Gateways).
* Enforce security using IAM Roles (`GenziteEC2Role`) and configure specific Security Groups across layers.
* Initialize object storage and database clusters (S3 Frontend/Media buckets, RDS PostgreSQL, ElastiCache Redis).

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Monday | **Genzite Capstone Kick-off & IAM Configuration** <br>- Study the target system architecture diagrams of the Genzite platform. <br>- Create and assign the `GenziteEC2Role` IAM role to grant EC2 access to AWS resources. | 22/06/2026 | 22/06/2026 | [Genzite Architecture](../../../aws-workshop-genzite.md#L552) |
| Tuesday | **VPC Network & Subnet Provisioning** <br>- Deploy custom VPCs, configure CIDR blocks, and build multi-AZ subnets. <br>- Setup Internet Gateways, NAT Gateways, and route tables. | 23/06/2026 | 23/06/2026 | [Genzite VPC Setup](../../../aws-workshop-genzite.md#L628) |
| Wednesday | **S3 Frontend & Media Buckets Provisioning** <br>- Build S3 Frontend buckets for hosting the client assets and S3 Media buckets for assets. <br>- Enforce CORS rules and Block Public Access policies. | 24/06/2026 | 24/06/2026 | [S3 Buckets Setup](../../../aws-workshop-genzite.md#L754) |
| Thursday | **Relational Database (RDS PostgreSQL) Setup** <br>- Launch Amazon RDS PostgreSQL Database Instances in private subnets. <br>- Form DB Subnet Groups and limit traffic using Security Groups. | 25/06/2026 | 25/06/2026 | [RDS Database Setup](../../../aws-workshop-genzite.md#L836) |
| Friday | **ElastiCache Redis Cache Cluster Setup** <br>- Provision caching infrastructures utilizing Amazon ElastiCache for Redis. <br>- Configure security groups and tune caching routes for Genzite. | 26/06/2026 | 26/06/2026 | [Redis Cache Setup](../../../aws-workshop-genzite.md#L947) |

### Week 10 Achievements:
* Gained core architectural overview details and prepared IAM permission boundaries for Genzite.
* Built secure VPC networking paths to support application routing.
* Deployed S3 Frontend & Media buckets, establishing appropriate CORS access guidelines.
* Established private RDS PostgreSQL databases and ElastiCache Redis cache pools within local subnets.
