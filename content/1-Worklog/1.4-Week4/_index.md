---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:
* Master object storage operations using Amazon S3 and command line interactions with AWS CLI.
* Configure and secure S3 Static Website Hosting (Block Public Access, Bucket Policies).
* Verify static website endpoints and manage bucket objects using the AWS CLI.
* Optimize website distribution performance and establish secure SSL endpoints using Amazon CloudFront.
* Research advanced S3 options: Bucket Versioning, Object Replication, and modern AWS Amplify hosting solutions.
* Execute thorough resource cleanup (S3 buckets, CloudFront distribution, Cloud9 environment) to optimize costs.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Friday | **Day 1: S3 Bucket Provisioning & AWS CLI Basics** <br>- Study core concepts of Amazon S3 and create S3 buckets. <br>- Practice basic AWS CLI command lines using the integrated Cloud9 terminal. | 08/05/2026 | 08/05/2026 | [Create S3](https://000057.awsstudygroup.com/2-prerequiste/) <br>[Use AWS CLI](https://000049.awsstudygroup.com/3-useawscli/) |
| Sat - Sun | **Day 2: Static Website Hosting & Access Policies** <br>- Enable Static Website Hosting properties on the target S3 bucket. <br>- Configure Block Public Access settings and apply read permissions via Bucket Policies. | 09/05/2026 | 10/05/2026 | [Static Web](https://000057.awsstudygroup.com/3-staticwebsite/) <br>[Block Public Access](https://000057.awsstudygroup.com/4-blockpublicaccess/) <br>[Public Object](https://000057.awsstudygroup.com/5-publicobject/) |
| Monday | **Day 3: Website Testing & Command Line Tasks** <br>- Test S3 Static Website availability using the generated endpoint. <br>- List (s3 ls), update, or delete bucket objects using CLI terminal inputs. | 11/05/2026 | 11/05/2026 | [Test Website](https://000057.awsstudygroup.com/6-testwebsite/) <br>[Use AWS CLI](https://000049.awsstudygroup.com/3-useawscli/) |
| Tuesday | **Day 4: Website Delivery Optimization via CloudFront** <br>- Build a CloudFront CDN Distribution referencing the S3 bucket source. <br>- Disable direct bucket access to enforce secure delivery over HTTPS via CloudFront. | 12/05/2026 | 12/05/2026 | [CloudFront Setup](https://000057.awsstudygroup.com/7-cloudfront/) |
| Wednesday | **Day 5: Advanced S3 Management (Versioning & Replication)** <br>- Enable Bucket Versioning to store object states and prevent data loss. <br>- Configure Cross-Region Replication (CRR) rules to mirror files across different regions. | 13/05/2026 | 13/05/2026 | [Versioning](https://000057.awsstudygroup.com/8-versioning/) <br>[Replication](https://000057.awsstudygroup.com/10-s3ccr/) |
| Thursday | **Day 6: Best Practices Review & Alternate Solutions** <br>- Study architectural best practices and operations for S3 buckets. <br>- Research AWS Amplify Hosting as a modern hosting solution featuring automatic CI/CD. | 14/05/2026 | 14/05/2026 | [S3 Notes](https://000057.awsstudygroup.com/12-notes/) |
| Friday | **Day 7: Resource Cleanup** <br>- Clean up all created assets (S3 buckets, CloudFront distribution, Cloud9) to keep the account cost-efficient. | 15/05/2026 | 15/05/2026 | [Cleanup](https://000057.awsstudygroup.com/11-cleanup/) |

### Week 4 Achievements:
* Gained proficiency in creating S3 buckets and uploading website content.
* Successfully deployed S3 Static Website Hosting secured via granular bucket policies.
* Integrated Amazon CloudFront CDN to speed up page loads and restrict direct HTTP access to the origin S3 bucket.
* Implemented S3 Bucket Versioning and Cross-Region Replication configurations.
* Evaluated AWS Amplify Hosting as a Git-based alternative to manual S3/CloudFront setups.
* Cleaned up S3 and CloudFront distribution properties to avoid unexpected service billing.
