---
slug: aws-console-create
id: 2abqhly27szj
type: challenge
title: AWS
tabs:
- title: AWS-Console
  type: service
  hostname: cloud-client
  path: /
  port: 80
- title: AWS-CLI
  type: terminal
  hostname: cloud-client
difficulty: basic
timelimit: 900
---
👋 Introduction
===============

Use the terminal to create vm instance:

```
aws configure set region us-east-2 --profile default
aws ec2 create-default-vpc || true

aws ec2 run-instances --image-id ami-0beaa649c482330f7 --instance-type t2.nano --tag-specifications 'ResourceType=instance,Tags=[{Key=Name,Value=example-host}]'

```

To complete this challenge, press **Check**.
