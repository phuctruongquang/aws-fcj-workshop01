---
title : "Reduce system operating costs with AWS Lambda"
date : "`r Sys.Date()`"
weight : 1
chapter : false
---

# Reduce system operating costs with AWS Lambda

#### Overview

This article will show you how to use Lambda Function to optimize your system costs on the AWS Cloud environment. We will schedule the server to automatically turn on and off for only a few hours a day.

For servers that operate 24/7, **Saving Plan** is an effective way to optimize costs for servers. You can learn more here [AWS Savings Plans](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html)

Below is the deployment model you can refer to:

   ![1-introduce sodo](/aws-fcj-workshop01/images/1-introduce/Workshop01-Introduce.png?width=70pc)

#### Content
1. [Introduce](1-introduce/)
2. [Preparation steps](2-createvpc-ec2/)
3. [Create AWS Lambda and Amazon EventBridge](3-createlambdastartstop/)
4. [Create email notifications when version status changes](4-createiam-ses/)
5. [Demo lab](5-combinetogether/)
6. [Delete resource](6-delete/)