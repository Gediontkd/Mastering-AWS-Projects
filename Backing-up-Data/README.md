
# Backing up Data

[![AWS](https://img.shields.io/badge/AWS-100000?style=flat&logo=amazon&logoColor=FFFFFF&labelColor=5C5C5C&color=FF7300)](https://docs.aws.amazon.com/quicksight/latest/user/signing-up.html)
[![EC2](https://img.shields.io/badge/AWS_EC2-100000?style=flat&logo=amazonec2&logoColor=white&labelColor=494949&color=FF7300)](https://aws.amazon.com/ec2/)
[![Aurora](https://img.shields.io/badge/AWS_Aurora-100000?style=flat&logo=amazonaws&logoColor=white&labelColor=494949&color=FF7300)](https://aws.amazon.com/rds/aurora/)
[![Backup](https://img.shields.io/badge/AWS_Backup-100000?style=flat&logo=amazonaws&logoColor=white&labelColor=494949&color=FF7300)](https://aws.amazon.com/backup/)
[![KMS](https://img.shields.io/badge/AWS_KMS-100000?style=flat&logo=amazonaws&logoColor=white&labelColor=494949&color=FF7300)](https://aws.amazon.com/kms/)
[![EBS](https://img.shields.io/badge/AWS_EBS-100000?style=flat&logo=amazonaws&logoColor=white&labelColor=494949&color=FF7300)](https://aws.amazon.com/ebs/)

## Project Source
This project was developed as part of the AWS Cloud Quest: Solutions Architect learning path (https://explore.skillbuilder.aws/learn/courses/7636/cloud-quest). AWS Cloud Quest provides hands-on experience in architecting cloud solutions through real-world scenarios.

## Project Description:

This repository contains scripts and configuration files for backing up data on AWS using various services such as Amazon EBS volumes and Aurora Serverless clustering.

<p align="center">
  <img src="./img/1.png" alt="" style="display: block; margin: auto;" />
</p>

## Table of Contents

- [Requirements](#requirements)
- [Steps](#Steps)
- [Conclusion](#conclusion)
- [Contributors](#contributors)


## Requirements
To complete this quest, you will need an AWS account with access to the following services:
- Amazon Aurora Serverless 
- Amazon Backup
- Amazon KMS
- Amazon EBS
- Amazon EC2

## Steps
### Step 1: Create a custom backup vault
<p align="center">
  <img src="./img/2.png" alt="" style="display: block; margin: auto;" />
</p>

### Step 2:Creating a backup plans
Create automated backup plans for EC2 attached Amazon EBS volumes using tags

<p align="center">
  <img src="./img/3.png" alt="" style="display: block; margin: auto;" />
</p>

### Step 3:Configure an AWS backup plan for an Amazon Aurora
Configure an AWS backup plan for an Amazon Aurora Serverless clustering by using the default backup vault

Assign the Aurora Serverless cluster as a resource by using the tag "Backup-DIY" = "TRUE"
<p align="center">
  <img src="./img/4.png" alt="" style="display: block; margin: auto;" />
</p>


## Conclusion
In conclusion, backing up your data is essential to ensure its safety and continuity in the event of an unexpected event. AWS provides multiple solutions for backing up your data, including creating a custom backup vault, configuring automated backup plans, and using tags to manage resources. With the knowledge gained from this guide, you can now confidently create and manage backup solutions for your AWS resources, ensuring that your data is always protected and available. Remember to regularly review and test your backup plans to ensure their effectiveness and make any necessary adjustments.

## Contributors

[Gedion Daniel](https://gediondaniel.dev/)
[LinkedIn](https://www.linkedin.com/in/gedion-daniel-760ba6280/)
