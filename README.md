<h1 align="center">Temporal Distributed Workflow Management Platform</h1>
<p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
</p>

## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction

[Temporal](https://github.com/temporalio/temporal) is an open-source distributed workflow management platform designed to simplify the development and operation of complex, stateful applications. The product deployment is based on the arm architecture's Huawei Cloud EulerOS 2.0 64-bit system.

### Why Temporal?

Temporal solves many problems that developers face while building distributed applications. But most of them revolve around these three themes:

**Reliable distributed applications**

**Productive development paradigms and code structure**

**Visible distributed application state**

### Reliable execution
**How does Temporal make applications reliable?**

Temporal makes it easier for developers to build and operate reliable, scalable applications without sacrificing productivity. The design of the system ensures that, once started, an application's main function executes to completion, whether that takes minutes, hours, days, weeks, or even years. Temporal calls this Durable Execution.

### Code Structure

**How does Temporal simplify application code for software developers?**

By shifting the burden of fault handling from the application to the platform, application developers write, test, and maintain less code. Temporal's programming model provides developers with a way to express their business logic as coherent workflows, which are easier to develop than distributed codebases.

Choose the SDK that best suits your preferred programming language and start writing business logic. Integrate your favorite IDEs, libraries, and tools into your development process. Temporal also supports multi-language and idiomatic programming, which enables developers to leverage the advantages of various programming languages and integrate Temporal into existing codebases. Developers can achieve all these functions without managing queues or complex state machines.

### State Visibility

**How does Temporal make it easier to view the state of an application?**

Temporal provides out-of-the-box tools that allow developers to view the state of an application when needed. The Temporal command line enables developers to effectively manage, monitor, and debug Temporal applications. The browser-based Web UI allows you to quickly isolate, debug, and resolve production issues.

The open-source image product [**Temporal Distributed Workflow Management Platform**](https://marketplace.huaweicloud.com/hidden/contents/425948e6-59f9-495d-a472-85db0d636efb#productid=OFFI1121280798300516352) provided by this project has pre-installed Temporal version 1.27.2 and its related runtime environment and provides deployment templates. Come and refer to the usage guide to easily start an efficient "out-of-the-box" experience!

> **System requirements are as follows:**
> - CPU: 2vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                       | Feature Description | Remarks |
|------------------------------------------------------------------------------------------------------------| --- | --- |
| [Temporal1.27.2-arm-v1](https://github.com/HuaweiCloudDeveloper/temporal-image/tree/Temporal1.27.2-arm-v1) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |  |

## Get Help
- For more questions, you can contact us via [issue](https://github.com/HuaweiCloudDeveloper/streamlit-image/issues) or the service support of the specified product on the Huawei Cloud Marketplace.
- For other open-source images, see [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos).

## How to Contribute
- Fork this repository and submit a merge request.
- Synchronously update README.md based on your open-source image information.