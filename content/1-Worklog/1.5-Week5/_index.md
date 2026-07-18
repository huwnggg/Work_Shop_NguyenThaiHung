---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:
* Explore relational database solutions using Amazon RDS and configure isolated network topologies (VPC, DB Subnet Groups, Security Groups).
* Practice provisioning RDS Database Instances and deploy application connectivity wrappers.
* Research NoSQL database designs on DynamoDB (Primary Keys, Secondary Indexes) via Console, CloudShell, and SDK Python.
* Optimize database query performance using caching structures (Amazon ElastiCache Redis Cluster).
* Implement database disaster recovery strategies (Backup & Restore) and execute full resource cleanup across all three labs.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Friday | **Day 1: Relational Database (Amazon RDS) - Overview & Setup** <br>- Understand S3 transaction patterns (OLTP) and Amazon RDS purposes. <br>- Provision database networking components: create custom VPC, DB Subnet Group, and Security Group rules. | 15/05/2026 | 15/05/2026 | [RDS Intro](https://000005.awsstudygroup.com/1-introduce/) <br>[RDS Networking](https://000005.awsstudygroup.com/2-prerequiste/) |
| Sat - Sun | **Day 2: RDS Provisioning & Application Deployment** <br>- Launch EC2 servers and initialize Amazon RDS PostgreSQL Database Instances. <br>- Deploy application codes to test connectivity logic directly to the RDS instance. | 16/05/2026 | 17/05/2026 | [RDS Database Creation](https://000005.awsstudygroup.com/4-create-rds/) <br>[Deploy App](https://000005.awsstudygroup.com/5-deploy-app/) |
| Monday | **Day 3: Non-Relational Database (Amazon DynamoDB) - Core Concepts** <br>- Study DynamoDB NoSQL capabilities: Partition/Sort keys, index choices, and Read/Write capacity. <br>- Create tables, save items, and query values using the AWS Console and CloudShell. | 18/05/2026 | 18/05/2026 | [DynamoDB Intro](https://000060.awsstudygroup.com/1-introduce/) <br>[Console/CloudShell Labs](https://000060.awsstudygroup.com/2-prerequiste/) |
| Tuesday | **Day 4: DynamoDB Interaction via AWS SDK (Python)** <br>- Install AWS CLI and write Python scripts utilizing Boto3 SDK to automate DynamoDB operations (table creation, batch insertions, query/scan queries). | 19/05/2026 | 19/05/2026 | [AWS SDK Python](https://000060.awsstudygroup.com/3-gettingstartedwithawssdk/3.2-pythonandynamodb/) |
| Wednesday | **Day 5: Performance Caching (Amazon ElastiCache Redis)** <br>- Analyze Redis as a performance caching layer to offload RDS queries. <br>- Configure Subnet Groups, create ElastiCache Clusters (verifying Cluster Mode enable/disable), and verify node connection routing. | 20/05/2026 | 20/05/2026 | [ElastiCache Prep](https://000061.awsstudygroup.com/2-prerequiste/) <br>[Create Redis Cluster](https://000061.awsstudygroup.com/3-amazonelasticacheforredis/) |
| Thursday | **Day 6: ElastiCache Data Read/Write via SDK** <br>- Use programming SDKs to query ElastiCache Redis endpoints. <br>- Execute basic Get/Set commands, interact with hash collections, configure Pub/Sub, and execute Stream interactions. | 21/05/2026 | 21/05/2026 | [SDK ElastiCache](https://000061.awsstudygroup.com/4-sdkelasticache/) |
| Friday | **Day 7: Backup and Teardown Cleanup** <br>- Practice manual backup snapshot exports and point-in-time recovery setups on Amazon RDS. <br>- Clean up all created assets (RDS database, DynamoDB tables, ElastiCache cluster) to prevent cost leakages. | 22/05/2026 | 22/05/2026 | [RDS Backup](https://000005.awsstudygroup.com/6-backup/) <br>[RDS Cleanup](https://000005.awsstudygroup.com/7-cleanup/) <br>[DynamoDB Cleanup](https://000060.awsstudygroup.com/4-cleanupresource/) <br>[ElastiCache Cleanup](https://000061.awsstudygroup.com/5.cleanupresource/) |

### Week 5 Achievements:
* Gained skills to deploy securely isolated relational database servers (RDS PostgreSQL) and verified code connection bindings.
* Designed tables and optimized indexing methods in DynamoDB NoSQL, automating database reads/writes using Python Boto3 SDK.
* Provisioned ElastiCache Redis environments and executed complex caching operations (Pub/Sub, Stream, Hash) via the SDK.
* Successfully validated RDS backup snapshots to secure system recovery limits.
* Completed clean teardowns of all RDS database endpoints, DynamoDB tables, and ElastiCache clusters.
