---
title: "Deploy in AWS"
permalink: /admin_guide/deploy_aws
excerpt: "Deploy in AWS"
modified: 2016-04-13T15:54:02-04:00
redirect_from:
  - /theme-setup/
toc: true
---

{% include base_path %}
This is a step by step guide to deploy a "Region" in your AWS cloud account

First, go to the configuration section

Click on "Regions" submenu on the left side

 

Click on "CREATE NEW"

![](02-deploy-aws-cloud-regions.png)


Select a descriptive name for your new region

Select the cloud provider "AWS"

Select the region to deploy the Isthari Big Data SaaS solution, for example N. Virginia

Indicates a new bucket name to store your initial data. This bucket MUST NOT exists, you can use the "Test" button to verify

And then click on "CREATE TEMPLATE"

![](02-deploy-aws-create-region-step-01.png)


The platform has just created an AWS Cloud Formation Template and is ready to start deploying your new regions, you just need to click on "Deploy Template"

![](02-deploy-aws-create-region-step-02.png)


Verify the IP addresses that will be used by your new VPC and click on "Next" button

![](02-deploy-aws-cloudfront-step-01.png)


On the "Configure stack options" screen click on Next button

![](02-deploy-aws-cloudfront-step-02.png)


In the last screen please check the option "I acknowledge that AWS CloudFormation might create IAM resources with custom names" and click "Create Stack"

![](02-deploy-aws-cloudfront-step-03.png)


Once started the process, you can check the status from the regions table


---

