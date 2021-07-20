---
title: "如何使用hugo"
chapter: false
weight: 0
---

这个页面不会提供给最终客户，只是向大家展示如何使用 hugo 搭建 workshop 网站。

- 首先，这个网站的源代码储存在 [https://github.com/kynging/algo-trading-workshop](https://github.com/kynging/algo-trading-workshop)，**请务必给个 star** 然后 clone 到本地
- 然后，去 hugo 的官方网站根据指示下载 hugo server：[https://gohugo.io/getting-started/installing/](https://gohugo.io/getting-started/installing/)
- 下载成功后运行以下命令行启动 hugo server：
```
hugo server -D
```
- 然后就可以去 [localhost:1313](localhost:1313) 访问这个网站了
- 如果需要修改绑定的 IP 和端口，运行：
```
hugo server -D --bind 0.0.0.0 --port xxx
```

接下来介绍以下这个 hugo 项目的文件结构，主要会用到的目录如下：
***
- content：这个文件夹里面包含网站的所有网页内容
  - 0.Prerequisite：对应“0. 准备工作”
    - _index.zh_cn.md：“0. 准备工作”主页面
	- 0.1.vpc_sagemaker_basics.zh_cn.md：“0.1 部署云端基础环境”
	- 0.2.aws_console.zh_cn.md：“0.2 通过 AWS 控制台创建 S3 存储桶和 ECS 集群（选项一）”
	- 0.3.aws_sdk.zh_cn.md：“0.3 使用 AWS SDK 创建 S3 存储桶和 ECS 集群（选项二）”
  - 1.SetupPlatform：对应“1. 从零构建量化平台”
    - _index.zh_cn.md：“1. 从零构建量化平台”主页面
	- 1.1.quickstart_datalake.zh_cn.md：“1.1 快速创建金融数据湖”
	- 1.2.backtrader_intro.zh_cn.md：“1.2 BackTrader 入门”
	- 1.3.sagemaker_hpo.zh_cn.md：“1.3 使用 SageMaker 运行超参优化”
	- 1.4.ecs_gridsearch.zh_cn.md：“1.4 使用 ECS 批量运行任务”
  - 2.MachineLearning：对应“2. 在量化开发中使用机器学习”
    - _index.zh_cn.md：“2. 在量化开发中使用机器学习”主页面
	- 2.1.sagemaker_example.zh_cn.md：“2.1 使用 SageMaker 进行模型训练和部署”
	- 2.2.long_short_predict.zh_cn.md：“2.2 示例策略：多空概率简单预测”
	- 2.3.portfolio_optimization.zh_cn.md：“2.3 示例策略：投资组合优化”
  - 3.Authors：对应“关于作者”
    - _index.zh_cn.md：“关于作者”
  - x.how_to_use_hugo：对应“如何使用hugo”
    - _index.zh_cn.md：“如何使用hugo”
  - _index.zh_cn.md：网站主页面
- static：这个文件夹里面包含网站的所有静态文件
  - images：所有的架构图都保存存在这个路径下
  - files：所有的 notebook 代码和 CloudFormation 模板都保存在这个路径下
***