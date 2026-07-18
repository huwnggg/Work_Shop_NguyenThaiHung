---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:
* Launch application server groups on EC2 and distribute traffic using Application Load Balancers (ALB) for Genzite.
* Configure dynamic Auto Scaling Groups (ASG) to handle automated scale-out/scale-in events.
* Map domain records via Route 53 and verify SSL/TLS certificates using AWS Certificate Manager (ACM).
* Deploy global content delivery network distribution endpoints via Amazon CloudFront.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Monday | **EC2 Server Launch & Launch Templates** <br>- Boot EC2 servers configured with Docker to host Genzite. <br>- Package server configurations and create a reusable Launch Template. | 29/06/2026 | 29/06/2026 | [EC2 Web Server](../../../aws-workshop-genzite.md#L1048) |
| Tuesday | **Application Load Balancer (ALB) Provisioning** <br>- Create an ALB and set up Target Groups to route traffic. <br>- Forward incoming HTTP queries (port 80) to active EC2 web servers. | 30/06/2026 | 30/06/2026 | [Load Balancer Setup](../../../aws-workshop-genzite.md#L1120) |
| Wednesday | **Auto Scaling Group (ASG) Setup** <br>- Create an Auto Scaling Group to dynamically scale based on load. <br>- Verify scaling policies to maintain high availability (HA). | 01/07/2026 | 01/07/2026 | [Auto Scaling Group](../../../aws-workshop-genzite.md#L1190) |
| Thursday | **SSL/TLS Certificates (ACM) & Route 53 Domain Routing** <br>- Request and validate public SSL/TLS certificates via ACM. <br>- Create DNS Record Sets in Route 53 pointing to the ALB endpoint for secure HTTPS access. | 02/07/2026 | 02/07/2026 | [Route 53 & ACM](../../../aws-workshop-genzite.md#L1254) |
| Friday | **CloudFront CDN Distribution Setup** <br>- Create a CloudFront Distribution sourcing from the S3 bucket (frontend) and ALB (backend). <br>- Optimize delivery by enabling cache policies at Edge locations. | 03/07/2026 | 03/07/2026 | [CloudFront Distribution](../../../aws-workshop-genzite.md#L1390) |

### Week 11 Achievements:
* Successfully deployed EC2 web servers balanced by an ALB and scaled via ASG configurations.
* Ensured high availability and self-healing properties of the Genzite platform.
* Activated secure HTTPS protocols across all platform domains using Route 53 and ACM.
* Published the site globally using CloudFront CDN to minimize latency.
