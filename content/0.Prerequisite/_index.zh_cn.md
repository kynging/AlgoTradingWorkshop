---
title: "0. 准备工作"
chapter: false
weight: 1
---

{{% notice note %}}
本实验建议在 us-east-1 区域进行。
{{% /notice  %}}


在这个部分，我们将创建实验必须的资源。这包括：

- 通过 CloudFormation 模板创建 VPC 和 SageMaker Notebook，以及实验过程中会用到的 IAM 角色
- 创建 S3 和 ECS Fargate 集群，为下一步实验做准备
- 了解 AWS SDK 的使用，并快速通过 Python SDK 创建 S3 和 ECS 资源（可选）

> 您可以在此了解涉及到的 AWS 基础服务的更多信息：
> - AWS CloudFormation：[https://aws.amazon.com/cn/cloudformation/](https://aws.amazon.com/cn/cloudformation/)
> - Amazon VPC：[https://aws.amazon.com/cn/vpc/](https://aws.amazon.com/cn/vpc/)
> - Amazon S3：[https://aws.amazon.com/cn/s3/](https://aws.amazon.com/cn/s3/)
> - Amazon ECS：[https://aws.amazon.com/cn/ecs/](https://aws.amazon.com/cn/ecs/)
> - Amazon SageMaker：[https://aws.amazon.com/cn/sagemaker/](https://aws.amazon.com/cn/sagemaker/)
> - AWS SDK 工具包：[https://aws.amazon.com/cn/getting-started/tools-sdks/](https://aws.amazon.com/cn/getting-started/tools-sdks/)