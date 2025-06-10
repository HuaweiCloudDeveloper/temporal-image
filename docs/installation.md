# Temporal部署指南

## ‌一、环境准备

### 系统配置
> -  服务器：鲲鹏服务器
> -  操作系统：Huawei Cloud EulerOS 2.0 64bit
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## ‌二、下载安装

#### 2.1 安装docker
参考：[安装Docker](../scripts/deploy_docker.sh)

### 2.2克隆官方仓库并启动服务
```bash
git clone https://github.com/temporalio/docker-compose.git
cd docker-compose
docker-compose up
```

访问 http://localhost:8080 进入 Web UI