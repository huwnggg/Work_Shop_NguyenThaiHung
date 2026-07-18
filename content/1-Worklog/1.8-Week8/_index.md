---
title: "Week 8 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:
* Explore the global content delivery network Amazon CloudFront and integrate S3 and EC2 instances as origin servers.
* Configure application redundancy using Origin Groups (failover routing) and configure granular Cache Behaviors.
* Customize HTTP Response Headers, execute Edge cache invalidations, and deploy Custom Error Pages.
* Study Edge Computing paradigms, authoring and deploying Lambda@Edge functions on CloudFront edge networks.
* Monitor CloudFront statistics using built-in Metrics and access logs, executing queries via Athena.
* Execute thorough resource cleanup workflows to disable all experimental setups and save costs.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Friday | **Day 1: CloudFront Overview & S3 Origin Integration** <br>- Learn the architecture of Amazon CloudFront content delivery network. <br>- Create an S3 bucket, upload index.html, and configure a CloudFront CDN referencing the S3 bucket. | 05/06/2026 | 05/06/2026 | [CloudFront Intro](https://000130.awsstudygroup.com/1-introduction/) <br>[S3 Bucket Creation](https://000094.awsstudygroup.com/1.1-t%E1%BA%A1o-nh%C3%B3m-s3/) <br>[Upload & Configure CDN](https://000094.awsstudygroup.com/1.2-t%E1%BA%A3i-l%C3%AAn-t%E1%BB%87p-index.html/) & [Configure CDN](https://000094.awsstudygroup.com/1.3-c%E1%BA%A5u-h%C3%ACnh-amazon-cloudfront/) |
| Sat - Sun | **Day 2: EC2 Origin Integration & Origin Group Failovers** <br>- Spin up an EC2 instance and declare it as a secondary CloudFront Origin. <br>- Configure an Origin Group to enable automatic failovers between multiple origins during service outages. | 05/06/2026 | 07/06/2026 | [EC2 & Origin Setup](https://000130.awsstudygroup.com/2--preparation/2.1-createec2/) & [Add EC2 Origin](https://000130.awsstudygroup.com/3-create-cloudfront-distribution/3.1-addec2/) <br>[Origin Group Tutorial](https://000130.awsstudygroup.com/6-origin-group/) |
| Monday | **Day 3: Cache Behavior & Custom Error Pages** <br>- Create and customize Cache Behaviors to optimize file caching efficiency. <br>- Design a Custom Error Page to display user-friendly responses for runtime errors. | 08/06/2026 | 08/06/2026 | [Cache Behavior](https://000130.awsstudygroup.com/8--cache-behavior/) <br>[Custom Error Page](https://000130.awsstudygroup.com/5-custom-error-page/) |
| Tuesday | **Day 4: Cache Invalidations & HTTP Response Headers** <br>- Configure HTTP Response Headers policies on the distribution endpoint. <br>- Execute cache Invalidations across Edge Servers to force immediate web updates. | 09/06/2026 | 09/06/2026 | [Response Headers](https://000130.awsstudygroup.com/7-response-headers/) <br>[Invalidations](https://000130.awsstudygroup.com/4-distribution-invalidations/) |
| Wednesday | **Day 5: Edge Computing - Lambda@Edge Initialization** <br>- Approach Edge Computing: write and initialize a Lambda@Edge function to intercept requests and responses directly at Edge locations. | 10/06/2026 | 10/06/2026 | [Lambda@Edge Init](https://000130.awsstudygroup.com/9-lambda@edge-function/) |
| Thursday | **Day 6: Lambda@Edge Deployment & Metrics Logging** <br>- Deploy the compiled Lambda@Edge function onto the active CloudFront Distribution. <br>- Establish log metrics, archive audit files in S3, and analyze access data via Athena. | 11/06/2026 | 11/06/2026 | [Deploy Lambda@Edge](https://000130.awsstudygroup.com/10-deploy-lambda@edge-function/) <br>[Metrics & Logs](https://000130.awsstudygroup.com/11-metrics-and-logs/) |
| Friday | **Day 7: Sandbox Resource Cleanup** <br>- Delete and disable all trial structures (CloudFront distributions, S3 buckets, EC2 hosts, Lambda functions) to clear sandbox charges. | 12/06/2026 | 12/06/2026 | [Teardown WS1](https://000130.awsstudygroup.com/12-cleanup/) <br>[Teardown WS2](https://000094.awsstudygroup.com/1.4-d%E1%BB%8Dn-d%E1%BA%B9p-t%C3%A0i-nguy%C3%AAn/) |

### Week 8 Achievements:
* Gained foundational knowledge of CDN delivery paths, successfully publishing S3 web content globally.
* Built high-availability distributions with automated S3-to-EC2 origin group failover triggers.
* Mastered cache behavioral logic, invalidation routines, and custom HTTP response headers.
* Successfully executed JavaScript request hooks at Edge server routers using Lambda@Edge.
* Established system metrics tracking, archived request logs, and analyzed web usage patterns via Athena queries.
* Performed safe teardowns of all CloudFront distributions, Lambda functions, and S3 resources.
