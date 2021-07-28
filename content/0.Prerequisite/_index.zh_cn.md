---
title: "0. 准备工作"
chapter: false
weight: 1
---

{{% notice note %}}
本实验建议在 us-east-1 区域进行。
{{% /notice  %}}


在这个部分，我们将创建实验必须的资源。这包括：

- 通过 CloudFormation 模板创建 VPC 和 IAM 角色， 以及 SageMaker Notebook
- 通过控制台创建 S3 和 ECS Fargate 集群
- 通过 AWS SDK 快速创建 S3 和 ECS（可选）

（此处应有架构图）