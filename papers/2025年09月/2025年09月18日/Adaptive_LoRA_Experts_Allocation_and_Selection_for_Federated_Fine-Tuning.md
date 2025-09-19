# 面向联邦微调的自适应LoRA专家分配与选择

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Adaptive LoRA Experts Allocation and Selection for Federated Fine-Tuning

# 摘要

> 大型语言模型（LLMs）在各类任务中已展现出令人瞩目的能力，然而针对特定领域应用对其进行微调查，往往需要大量特定领域数据，而这些数据可能分散在多个组织中。联邦学习（FL）虽提供了隐私保护的解决方案，但应用于LLMs时却面临计算资源受限的难题。低秩适应（LoRA）作为一种参数高效的微调方法应运而生，不过单个LoRA模块在处理不同领域的异构数据时往往难以应对。本文针对联邦LoRA微调中的两个关键挑战展开研究：1. 确定异构客户端间LoRA专家的最优数量与分配方案；2. 使客户端能根据自身数据特征选择性地调用这些专家。我们提出了FedLEASE（联邦自适应LoRA专家分配与选择）——一种新颖框架，该框架基于表示相似性对客户端进行自适应聚类，从而分配并训练特定领域的LoRA专家。该框架还引入了自适应top-M混合专家机制，使每个客户端能自主选择最优数量的专家进行调用。我们在多种基准数据集上的大量实验证实，FedLEASE在异构客户端场景下显著优于现有联邦微调方法，同时保持了通信效率。

> Large Language Models (LLMs) have demonstrated impressive capabilities across various tasks, but fine-tuning them for domain-specific applications often requires substantial domain-specific data that may be distributed across multiple organizations. Federated Learning (FL) offers a privacy-preserving solution, but faces challenges with computational constraints when applied to LLMs. Low-Rank Adaptation (LoRA) has emerged as a parameter-efficient fine-tuning approach, though a single LoRA module often struggles with heterogeneous data across diverse domains. This paper addresses two critical challenges in federated LoRA fine-tuning: 1. determining the optimal number and allocation of LoRA experts across heterogeneous clients, and 2. enabling clients to selectively utilize these experts based on their specific data characteristics. We propose FedLEASE (Federated adaptive LoRA Expert Allocation and SElection), a novel framework that adaptively clusters clients based on representation similarity to allocate and train domain-specific LoRA experts. It also introduces an adaptive top-$M$ Mixture-of-Experts mechanism that allows each client to select the optimal number of utilized experts. Our extensive experiments on diverse benchmark datasets demonstrate that FedLEASE significantly outperforms existing federated fine-tuning approaches in heterogeneous client settings while maintaining communication efficiency.

[Arxiv](https://arxiv.org/abs/2509.15087)