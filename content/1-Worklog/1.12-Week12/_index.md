---
title: "Week 12 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.12. </b> "
---

### Week 12 Objectives:
* Automate the Genzite application deployment using CI/CD pipelines via Jenkins.
* Deploy secure access systems utilizing Bastion Hosts, SSM Session Manager, and AWS WAF/Shield.
* Configure logging and monitoring capabilities using Amazon CloudWatch.
* Complete performance self-assessments, finish the Hugo report site, and perform final resources teardown.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Monday | **CI/CD Automation via Jenkins Pipeline** <br>- Install a Jenkins build controller and construct a custom Jenkinsfile to pull, compile, and publish Genzite. | 06/07/2026 | 06/07/2026 | [Jenkins CI/CD Pipeline](../../../aws-workshop-genzite.md#L1491) |
| Tuesday | **Secure Gateways via Bastion Host & SSM Session Manager** <br>- Launch Bastion Host servers inside public subnets for edge proxy routing. <br>- Configure Systems Manager Session Manager to establish SSH command shells into private EC2 targets. | 07/07/2026 | 07/07/2026 | [Bastion Host & SSM](../../../aws-workshop-genzite.md#L1739) |
| Wednesday | **System-wide Monitoring via CloudWatch** <br>- Configure CloudWatch Metrics, Alarms, and Logs Insights to audit the health of web, DB, and cache instances. | 08/07/2026 | 08/07/2026 | [CloudWatch Monitoring](../../../aws-workshop-genzite.md#L1824) |
| Thursday | **Network Shielding with AWS WAF & Shield** <br>- Deploy Web ACLs via AWS WAF to safeguard the Genzite public web portal from SQL injections, XSS, and DDoS triggers. | 09/07/2026 | 09/07/2026 | [WAF & Shield Security](../../../aws-workshop-genzite.md#L1913) |
| Friday | **Final Project Teardown & Report Submission** <br>- Tear down and clean up all resources created on the AWS console to terminate billing. <br>- Perform self-assessments (Self-assessment) and compile the daily work log site. | 10/07/2026 | 10/07/2026 | [Genzite Cleanup](../../../aws-workshop-genzite.md#L1963) <br>[Self-assessment](../../6-Self-evaluation/) |

### Week 12 Achievements:
* Successfully established an automated build and deploy pipeline using Jenkins CI/CD.
* Enforced least-privilege administration configurations via SSM Session Manager shell sessions.
* Built CloudWatch Dashboards displaying system health metrics and aggregate logs.
* Shielded public web interfaces using AWS WAF rules to block malicious traffic patterns.
* Completed clean teardowns of all active capstone resources and submitted the final work log report site.
