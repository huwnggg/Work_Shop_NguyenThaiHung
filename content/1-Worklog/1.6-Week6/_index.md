---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:
* Learn and deploy Docker containers on Amazon Lightsail.
* Build, push, and deploy custom Docker container images on Amazon Lightsail.
* Build high-availability web applications using Elastic Load Balancing (ELB) and Auto Scaling Groups (ASG) on EC2 and RDS.
* Configure CPU/RAM utilization metrics and log monitoring with Amazon CloudWatch Metrics & Logs.
* Establish automated alerts (CloudWatch Alarms) and construct system dashboards (CloudWatch Dashboards).
* Perform final resource cleanup across all labs to optimize subscription costs.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Friday | **Day 1: Amazon Lightsail - Initialization & Basic Container Deployment** <br>- Study Amazon Lightsail Containers to easily run Docker containers in the cloud. <br>- Create a Container Service and deploy a public Docker image. | 22/05/2026 | 22/05/2026 | [Lightsail Prep](https://000046.awsstudygroup.com/1-prepare/) <br>[Deploy Public Image](https://000046.awsstudygroup.com/3-deploy-publicimage/) |
| Sat - Sun | **Day 2: Amazon Lightsail - Custom Container Image Deployment** <br>- Create an Ubuntu host instance on Lightsail, installing Docker and AWS CLI. <br>- Build a custom Docker image locally, push to Lightsail Container Service, and execute deployment. | 23/05/2026 | 24/05/2026 | [Deploy Custom Image](https://000046.awsstudygroup.com/4-deploy-yourimage/) |
| Monday | **Day 3: Auto Scaling & ELB - Infrastructure Prep & Load Balancer** <br>- Prepare infrastructure: custom VPC, EC2 web server, RDS database, and Launch Templates. <br>- Provision an Elastic Load Balancer (Target Group & ALB) to balance web traffic. | 25/05/2026 | 25/05/2026 | [Infra Prep](https://000006.awsstudygroup.com/2-preparation/) <br>[ALB Setup](https://000006.awsstudygroup.com/4-setup-load-balancer/) |
| Tuesday | **Day 4: Auto Scaling & ELB - Auto Scaling Group & Scaling Tests** <br>- Create an Auto Scaling Group to dynamically scale EC2 instances. <br>- Test scaling solutions: manual, scheduled, dynamic, and predictive scaling options. | 26/05/2026 | 26/05/2026 | [ASG Setup](https://000006.awsstudygroup.com/6-create-auto-scaling-group/) <br>[Scaling Test](https://000006.awsstudygroup.com/7-test-solutions/) |
| Wednesday | **Day 5: Amazon CloudWatch - Metric Aggregation & Log Analysis** <br>- Analyze CloudWatch metrics using search expressions and math functions. <br>- Collect application logs using CloudWatch Logs (querying via Logs Insights and creating Metric Filters). | 27/05/2026 | 27/05/2026 | [CloudWatch Metrics](https://000008.awsstudygroup.com/3-cloud-watch-metric/) <br>[CloudWatch Logs](https://000008.awsstudygroup.com/4-cloud-watch-logs/) |
| Thursday | **Day 6: Amazon CloudWatch - Alarm Setup & Console Dashboards** <br>- Create CloudWatch Alarms to send emails when performance breaches happen, reducing MTTR. <br>- Build visual CloudWatch Dashboards to monitor resources in a single pane of glass. | 28/05/2026 | 28/05/2026 | [CloudWatch Alarms](https://000008.awsstudygroup.com/5-cloud-watch-alarm/) <br>[CloudWatch Dashboards](https://000008.awsstudygroup.com/6-cloud-watch-dashboard/) |
| Friday | **Day 7: Resource Cleanup** <br>- Clean up all created assets (Lightsail Containers, EC2/ASG/ALB/RDS, CloudWatch Metrics) to optimize cloud spend. | 29/05/2026 | 29/05/2026 | [Lightsail Cleanup](https://000046.awsstudygroup.com/5-clean-up/) <br>[Auto Scaling Cleanup](https://000006.awsstudygroup.com/8-cleanup/) <br>[CloudWatch Cleanup](https://000008.awsstudygroup.com/7-clean-up-resources/) |

### Week 6 Achievements:
* Gained experience building and deploying Docker containerized services on Amazon Lightsail.
* Constructed a high-availability infrastructure featuring Elastic Load Balancing and Auto Scaling Groups.
* Mastered diagnostic routines, log aggregation using CloudWatch Logs Insights, and metric alarm triggers.
* Developed CloudWatch Dashboards displaying database, container, and compute metrics.
* Completed successful cleanup tasks across all three environments.
