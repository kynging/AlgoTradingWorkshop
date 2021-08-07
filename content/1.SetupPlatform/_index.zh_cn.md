---
title: "1. 从零构建量化平台"
chapter: false
weight: 2
---

{{% notice note %}}
本实验建议在 us-east-1 区域进行。
{{% /notice  %}}

（此处应有架构图）
![](/images/0.3.aws_sdk/)

在这个部分，我们将体验在量化开发中使用 AWS 大数据服务和容器服务。这包括：

- 通过 AWS 托管的大数据服务快速创建金融数据湖
- 在 Notebook 中运行基于 Python 简单 BackTrader 策略
- 在 ECS 并行运行大量容器执行 Python 代码
- 体验 SageMaker 特有的超参优化功能