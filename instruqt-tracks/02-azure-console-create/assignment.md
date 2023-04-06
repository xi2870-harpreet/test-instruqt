---
slug: azure-console-create
id: gpsy1uqeaty8
type: challenge
title: Azure
tabs:
- title: Azure-Console
  type: service
  hostname: cloud-client
  path: /
  port: 80
- title: AZ-CLI
  type: terminal
  hostname: cloud-client
difficulty: basic
timelimit: 900
---
👋 Introduction
===============

Use the terminal to create vm instance:

```
az group create --name test --location eastus
az vm create --resource-group test --name example-host --image Debian

```

To complete this challenge, press **Check**.
