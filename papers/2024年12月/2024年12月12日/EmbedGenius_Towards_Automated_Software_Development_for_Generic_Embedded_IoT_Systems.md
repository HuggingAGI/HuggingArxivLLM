# EmbedGenius：致力于实现通用嵌入式物联网系统的自动化软件开发

发布时间：2024年12月12日

`LLM应用` `物联网` `嵌入式系统`

> EmbedGenius: Towards Automated Software Development for Generic Embedded IoT Systems

# 摘要

> 嵌入式物联网系统的开发对于在众多应用中实现无缝连接和功能起着关键作用。然而，这一复杂过程需要硬件和软件的跨领域知识，所以常常需要开发人员直接介入，导致其劳动强度大、耗时久且易出错。为应对此挑战，本文推出了 EmbedGenius，这是首个面向通用嵌入式物联网系统的全自动化软件开发平台。其核心思路是借助大型语言模型（LLMs）的推理能力和嵌入式系统的专业知识，来实现硬件在环开发过程的自动化。主要方法涵盖用于处理硬件依赖的组件感知库解析方法、将实用领域知识注入 LLMs 的库知识生成方法以及确保成功部署的自动编程方法。我们在 71 个模块和四个主流嵌入式开发平台上，针对超过 350 个物联网任务对 EmbedGenius 的性能进行了评估。实验结果显示，EmbedGenius 生成代码的准确率达 95.7%，完成任务的成功率为 86.5%，分别比人工在环基线高出 15.6% - 37.7% 和 25.5% - 53.4%。我们还通过环境监测和远程控制系统开发的案例研究展现了 EmbedGenius 的潜力。

> Embedded IoT system development is crucial for enabling seamless connectivity and functionality across a wide range of applications. However, such a complex process requires cross-domain knowledge of hardware and software and hence often necessitates direct developer involvement, making it labor-intensive, time-consuming, and error-prone. To address this challenge, this paper introduces EmbedGenius, the first fully automated software development platform for general-purpose embedded IoT systems. The key idea is to leverage the reasoning ability of Large Language Models (LLMs) and embedded system expertise to automate the hardware-in-the-loop development process. The main methods include a component-aware library resolution method for addressing hardware dependencies, a library knowledge generation method that injects utility domain knowledge into LLMs, and an auto-programming method that ensures successful deployment. We evaluate EmbedGenius's performance across 71 modules and four mainstream embedded development platforms with over 350 IoT tasks. Experimental results show that EmbedGenius can generate codes with an accuracy of 95.7% and complete tasks with a success rate of 86.5%, surpassing human-in-the-loop baselines by 15.6%--37.7% and 25.5%--53.4%, respectively. We also show EmbedGenius's potential through case studies in environmental monitoring and remote control systems development.

[Arxiv](https://arxiv.org/abs/2412.09058)