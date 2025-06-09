# # 部署中心的基础设施即代码生成：基于大语言模型的迭代框架

发布时间：2025年06月05日

`LLM应用` `云计算` `软件工程`

> Deployability-Centric Infrastructure-as-Code Generation: An LLM-based Iterative Framework

# 摘要

> # 基础设施即代码（IaC）生成与评估

基础设施即代码（IaC）生成在自动化云基础设施配置方面展现出巨大潜力。大型语言模型（LLMs）的最新进展为通过自然语言描述生成可部署的基础设施模板提供了民主化开发的机遇，但目前的评估主要关注语法正确性，忽视了可部署性——衡量IaC模板实用性的关键指标。

我们通过两项创新性贡献来填补这一研究空白：（1）IaCGen，一个基于LLM、以可部署性为中心的框架，通过迭代反馈机制生成高质量的IaC模板；（2）DPIaC-Eval，一个包含153个真实场景的以可部署性为中心的IaC模板基准，能够全面评估语法、部署、用户意图和安全性。

我们的评估揭示了令人振奋的结果：尽管最先进的LLMs（如Claude-3.5和Claude-3.7）在初始表现中分别仅达到30.2%和26.8%的部署成功率，但借助IaCGen框架，所有评估模型在25次迭代内均达到超过90%的通过率，其中Claude-3.5和Claude-3.7的成功率更是高达98%。

然而，研究也揭示了仍需攻克的难题：用户意图对齐（25.2%的准确率）和安全合规（8.4%的通过率）仍面临重大挑战，这凸显了未来研究的重点方向。

我们的工作首次全面评估了以可部署性为中心的IaC模板生成，并为未来的研究奠定了坚实的基础。


> Infrastructure-as-Code (IaC) generation holds significant promise for automating cloud infrastructure provisioning. Recent advances in Large Language Models (LLMs) present a promising opportunity to democratize IaC development by generating deployable infrastructure templates from natural language descriptions, but current evaluation focuses on syntactic correctness while ignoring deployability, the fatal measure of IaC template utility. We address this gap through two contributions: (1) IaCGen, an LLM-based deployability-centric framework that uses iterative feedback mechanism to generate IaC templates, and (2) DPIaC-Eval, a deployability-centric IaC template benchmark consists of 153 real-world scenarios that can evaluate syntax, deployment, user intent, and security. Our evaluation reveals that state-of-the-art LLMs initially performed poorly, with Claude-3.5 and Claude-3.7 achieving only 30.2% and 26.8% deployment success on the first attempt respectively. However, IaCGen transforms this performance dramatically: all evaluated models reach over 90% passItr@25, with Claude-3.5 and Claude-3.7 achieving 98% success rate. Despite these improvements, critical challenges remain in user intent alignment (25.2% accuracy) and security compliance (8.4% pass rate), highlighting areas requiring continued research. Our work provides the first comprehensive assessment of deployability-centric IaC template generation and establishes a foundation for future research.

[Arxiv](https://arxiv.org/abs/2506.05623)