---
title: "Week 2 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:
* Master the foundational networking concepts of Amazon VPC (Subnet, Route Table, IGW, NAT Gateway, Security Groups, NACLs).
* Learn how to provision a custom VPC network manually and configure log monitoring via VPC Flow Logs.
* Deploy EC2 instances securely inside the VPC, verify route connectivity using Reachability Analyzer, and access via SSM Session Manager.
* Set up a simulated AWS Site-to-Site VPN connection and establish active VPN Tunnels.
* Explore Infrastructure as Code (IaC) deployment with CloudFormation and execute resource cleanup strategies.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Monday | **VPC Theory & Network Security** <br>- Study core concepts: Subnets, Route Tables, Internet Gateways, NAT Gateways. <br>- Learn about VPC security layers (Security Groups, Network ACLs) and VPC Resource Map. | 27/04/2026 | 27/04/2026 | [VPC Intro](https://000003.awsstudygroup.com/1-introduce/) <br>[VPC Security](https://000003.awsstudygroup.com/2-firewallinvpc/) |
| Tuesday | **VPC Network Environment Setup & Flow Logs** <br>- Provision VPC, Subnets, Internet Gateways, Route Tables, and Security Groups. <br>- Enable VPC Flow Logs to monitor and capture network traffic patterns. | 28/04/2026 | 28/04/2026 | [Network Prep](https://000003.awsstudygroup.com/3-prerequisite/) |
| Wednesday | **EC2 Server Deployment & Monitoring** <br>- Launch EC2 instances in private subnets, routing outbound traffic through a NAT Gateway. <br>- Enforce secure session management without SSH keypairs using Systems Manager Session Manager. <br>- Verify traffic path connection via Reachability Analyzer and monitor in CloudWatch. | 29/04/2026 | 29/04/2026 | [EC2 Deployment](https://000003.awsstudygroup.com/4-createec2server/) |
| Thursday | **AWS Site-to-Site VPN & Infrastructure as Code** <br>- Build a simulated VPN network: create CGW, VGW, and establish secure VPN Tunnels. <br>- Study VPN extension using Strongswan software with Transit Gateway. <br>- Explore automating cloud resources using CloudFormation templates (IaC). | 30/04/2026 | 30/04/2026 | [AWS VPN Setup](https://000003.awsstudygroup.com/5-vpnsitetosite/) <br>[Strongswan VPN](https://000003.awsstudygroup.com/5-vpnsitetosite/5.3-vpnsitetosite-optional/) <br>[IaC CloudFormation](https://000003.awsstudygroup.com/7-infrastructureascode/) |
| Friday | **Resource Cleanup & Best Practices Review** <br>- Clean up all provisioned components (VPC, EC2, VPN, etc.) to optimize subscription costs. <br>- Review network design architectures against cloud security best practices. | 01/05/2026 | 01/05/2026 | [VPC Cleanup](https://000003.awsstudygroup.com/6-cleanup/) |

### Week 2 Achievements:
* Understood VPC networking architecture, comparing the stateful behavior of Security Groups with the stateless nature of NACLs.
* Designed and built a fully functional multi-tier VPC environment and analyzed logs using VPC Flow Logs.
* Deployed EC2 instances and successfully connected via Systems Manager Session Manager, debugging routing paths with Reachability Analyzer.
* Created an AWS Site-to-Site VPN tunnel connection, establishing secure customer-to-cloud VPN links.
* Explored and implemented infrastructure automation using CloudFormation, and performed a total cleanup to avoid cloud billing.
