---
title: "Week 3 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:
* Learn and configure AWS Cloud9 online IDE environment on the AWS Console.
* Gain proficiency in basic Cloud9 operations including file management, text editing, and terminal commands.
* Integrate and leverage AWS CLI built-in tools within the Cloud9 IDE workspace.
* Explore application authorization mechanisms and identify security risks associated with Access Keys.
* Practice implementing secure access control using EC2 Instance Profiles (IAM Roles).
* Audit resources and perform cleanup actions for both lab environments.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Monday | **AWS Cloud9 - Initialization & Basic Features** <br>- Learn about the integrated development environment (IDE) AWS Cloud9. <br>- Get familiar with the Dashboard, directory trees, file creation, and terminal. | 04/05/2026 | 04/05/2026 | [Create Cloud9](https://000049.awsstudygroup.com/1-createcloud9/) <br>[Cloud9 Basic Features](https://000049.awsstudygroup.com/2-basicfeature/) |
| Tuesday | **AWS Cloud9 - AWS CLI Integration** <br>- Run AWS CLI commands from the integrated terminal in Cloud9. <br>- Query and manage cloud resources directly from the command line interface. | 05/05/2026 | 05/05/2026 | [Use AWS CLI](https://000049.awsstudygroup.com/3-useawscli/) |
| Wednesday | **App Authorization - Environment Prep** <br>- Provision an EC2 instance and an S3 bucket to prepare for access testing. | 06/05/2026 | 06/05/2026 | [Environment Prep](https://000048.awsstudygroup.com/1-prepare/) |
| Thursday | **App Authorization - Access Key Usage & Security Risks** <br>- Create an IAM User and generate Access Keys to connect EC2 to S3. <br>- Understand security risks of storing hardcoded access credentials on a server. | 07/05/2026 | 07/05/2026 | [Access Key Risk](https://000048.awsstudygroup.com/2-accesskey/) |
| Friday | **App Authorization - IAM Role on EC2 & Cleanup** <br>- Set up secure access by creating an IAM Role and attaching it to the EC2 server. <br>- Verify EC2 can access S3 via metadata credentials. Clean up all resources across both labs (Cloud9, EC2, S3, IAM user/role) to optimize costs. | 08/05/2026 | 08/05/2026 | [IAM Role for EC2](https://000048.awsstudygroup.com/3-iamroleec2/) <br>[Cloud9 Cleanup](https://000049.awsstudygroup.com/4-cleanup/) <br>[IAM Role Cleanup](https://000048.awsstudygroup.com/4-cleanup/) |

### Week 3 Achievements:
* Successfully created an online Cloud9 IDE and mastered directory navigation and editing using the terminal.
* Leveraged built-in AWS CLI tools within Cloud9 for smooth AWS resource queries.
* Identified major security implications of using long-term Access Keys on servers.
* Implemented secure IAM Roles for EC2 instances to enable automatic credential rotation.
* Completed full resource teardown across both lab environments to prevent cost leakages.
