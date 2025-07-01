 <h1 align="center">Temporal分布式工作流管理平台</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[Temporal](https://github.com/temporalio/temporal) 是一个开源的分布式工作流管理平台，旨在简化复杂、有状态应用的开发与运维。商品部署基于arm架构的Huawei Cloud EulerOS 2.0 64bit系统。

**为什么选择 Temporal？**

Temporal解决了开发人员在构建分布式应用程序时面临的许多问题。但大多数都围绕着这三个主题：

**可靠的分布式应用**

**生产开发范例和代码结构**

**可见分布式应用状态**


**可靠执行**

Temporal 如何保障应用可靠性？

Temporal使开发人员更容易构建和操作可靠的、可伸缩的应用程序，而不会牺牲生产力。系统的设计确保，一旦启动，应用程序的主要功能执行完成，无论这需要几分钟，几小时，几天，几周，甚至几年。临时调用此持久执行。

**代码结构**

Temporal如何为软件开发人员简化应用程序代码？

通过将故障处理的负担从应用程序转移到平台，应用程序开发人员编写、测试和维护的代码就更少了。Temporal的编程模型为开发人员提供了一种将他们的业务逻辑表达成连贯工作流的方法，这比分布式代码库更容易开发。

选择最适合您首选编程语言的SDK，并开始编写业务逻辑。将您喜欢的IDE、库和工具集成到您的开发过程中。Temporal还支持多语言和习惯编程——这使开发人员能够利用各种编程语言的优势，并将Temporal集成到现有的代码库中。开发人员无需管理队列或复杂的状态机即可实现所有这些功能。

**状态可见性**

Temporal如何使查看应用程序的状态变得更容易？

Temporal提供了开箱即用的工具，使开发人员能够在需要时查看应用程序的状态。时态命令行允许开发人员有效地管理、监视和调试时态应用程序。基于浏览器的Web UI允许您快速隔离、调试和解决生产问题。

本项目提供的开源镜像商品 [**Temporal分布式工作流管理平台**](https://marketplace.huaweicloud.com/hidden/contents/425948e6-59f9-495d-a472-85db0d636efb#productid=OFFI1121280798300516352) 已预先安装1.27.2版本的Temporal及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                       | 特性说明 | 备注 |
|------------------------------------------------------------------------------------------------------------| --- | --- |
| [Temporal1.27.2-arm-v1](https://github.com/HuaweiCloudDeveloper/temporal-image/tree/Temporal1.27.2-arm-v1) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/temporal-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
