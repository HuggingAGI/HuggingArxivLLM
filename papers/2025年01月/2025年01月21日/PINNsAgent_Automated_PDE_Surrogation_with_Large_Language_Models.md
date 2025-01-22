# PINNsAgent: 基于大型语言模型的偏微分方程自动代理生成

发布时间：2025年01月21日

`Agent

理由：这篇论文提出了一种名为PINNsAgent的框架，它结合了大型语言模型（LLMs）和物理信息神经网络（PINNs）来解决偏微分方程（PDEs）的问题。PINNsAgent的核心组件包括物理引导知识回放（PGKR）和记忆树推理，这些组件旨在自动化地优化PINNs的配置和架构。由于该框架的核心是使用LLMs来辅助PINNs的自动化优化过程，这符合“Agent”分类的定义，即使用智能体（Agent）来执行特定任务或优化过程。因此，这篇论文应被分类为“Agent”。` `科学计算`

> PINNsAgent: Automated PDE Surrogation with Large Language Models

# 摘要

> # 摘要
神经网络方法求解偏微分方程（PDEs）一直是科学和工程领域的研究热点。物理信息神经网络（PINNs）作为传统数值方法的有力替代，展现出巨大潜力。然而，领域知识与深度学习之间的鸿沟常常阻碍了PINNs的实际应用。以往的研究多依赖于手动实验和启发式规则进行超参数调优。本文提出了一种新颖的替代框架——PINNsAgent，它结合大型语言模型（LLMs）和PINNs，旨在弥合领域知识与深度学习之间的差距。PINNsAgent包含两大核心组件：（1）物理引导知识回放（PGKR），将PDEs的关键特征及其最优PINNs配置编码为结构化知识，实现从已解决问题到新问题的知识迁移；（2）记忆树推理，高效探索最优PINNs架构的搜索空间。通过LLMs和探索策略的结合，PINNsAgent显著提升了基于PINNs的解决方案的自动化水平和效率。我们在14个基准PDEs上验证了PINNsAgent的有效性，结果表明其在自动化替代过程中表现出色，并大幅提高了PINNs解决方案的精度。

> Solving partial differential equations (PDEs) using neural methods has been a long-standing scientific and engineering research pursuit. Physics-Informed Neural Networks (PINNs) have emerged as a promising alternative to traditional numerical methods for solving PDEs. However, the gap between domain-specific knowledge and deep learning expertise often limits the practical application of PINNs. Previous works typically involve manually conducting extensive PINNs experiments and summarizing heuristic rules for hyperparameter tuning. In this work, we introduce PINNsAgent, a novel surrogation framework that leverages large language models (LLMs) and utilizes PINNs as a foundation to bridge the gap between domain-specific knowledge and deep learning. Specifically, PINNsAgent integrates (1) Physics-Guided Knowledge Replay (PGKR), which encodes the essential characteristics of PDEs and their associated best-performing PINNs configurations into a structured format, enabling efficient knowledge transfer from solved PDEs to similar problems and (2) Memory Tree Reasoning, a strategy that effectively explores the search space for optimal PINNs architectures. By leveraging LLMs and exploration strategies, PINNsAgent enhances the automation and efficiency of PINNs-based solutions. We evaluate PINNsAgent on 14 benchmark PDEs, demonstrating its effectiveness in automating the surrogation process and significantly improving the accuracy of PINNs-based solutions.

[Arxiv](https://arxiv.org/abs/2501.12053)