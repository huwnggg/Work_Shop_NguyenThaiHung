---
title: "Lab 4: CloudWatch Monitoring"
weight: 5
chapter: false
pre: " <b> 5.5. </b> "
---

## Overview

In this section, we will configure and use **Amazon CloudWatch** to monitor the resources of the Genzite system, specifically creating a Log Group to collect logs from the EC2 Backend and tracking operational metrics.

> **Permission Note:** Setting up monitoring on CloudWatch is a task within the scope of **User C (Application & Storage)**.

## Step 1: Create a Log Group for the Backend

1. Open the AWS Management Console and search for the **CloudWatch** service.
2. On the left menu, select **Logs** -> **Log groups**.
3. Click the **Create log group** button.
4. Configure the following parameters:
   - **Log group name**: `/aws/ec2/genzite-backend-dev`
   - **Retention setting**: `1 week (7 days)`
   - **Log class**: `Standard`
5. Click **Create**.

![Create CloudWatch Log Group](image/5.5.1.png)

## Step 2: View Log Groups and Log Data

1. After creation, return to the **Log groups** page. You will see your newly created `/aws/ec2/genzite-backend-dev` log group in the list (along with others like `RDSOSMetrics` if RDS is configured).

![Log Groups List](image/5.5.2.png)

2. Click on the `/aws/ec2/genzite-backend-dev` log group.
3. Once the EC2 instance pushes logs via the CloudWatch Agent, you can click on the corresponding **Log stream** to monitor incoming logs (Errors, API Requests).

## Step 3: Create an Alarm (Automated Alert)

1. On the left menu, select **Alarms** -> **In alarm**.
2. Click **Create alarm**.
3. Select the metric **CPUUtilization** (CPU usage level) of the EC2 Backend.
4. Set the alert threshold (e.g., `> 80%` for 5 continuous minutes).
5. (Optional) Configure notifications via Amazon SNS to send an email to the administrator when the system is overloaded.

---
**Congratulations!** You have successfully set up the "monitoring center" for Genzite. Thanks to CloudWatch, the team can easily detect and handle issues.
