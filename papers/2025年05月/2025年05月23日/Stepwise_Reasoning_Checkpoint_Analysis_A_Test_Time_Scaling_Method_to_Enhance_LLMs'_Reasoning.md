# 逐步推理检查点分析：一种提升大语言模型推理能力的测试时缩放方法

发布时间：2025年05月23日

`LLM应用`

> Stepwise Reasoning Checkpoint Analysis: A Test Time Scaling Method to Enhance LLMs' Reasoning

# 摘要

> 基于链式思维 (CoT) 的数学推理能力已在大型语言模型 (LLMs) 中展现出强大的能力，而通过测试时缩放 (TTS) 方法（如束搜索和 DVTS）可以进一步提升这一能力。然而，尽管这些方法通过在推理过程中分配更多计算资源提高了准确性，但它们常常面临推理路径同质化和中间结果利用率低下的问题。为了解决这些问题，我们提出了分步推理检查点分析 (SRCA) 框架，在推理步骤之间引入检查点。该框架包含两大核心策略：(1) 答案聚类搜索，通过将推理路径按中间检查点答案分组，在确保质量的同时保持多样性；(2) 检查点候选增强，利用所有中间答案进行最终决策。我们的方法通过充分利用高质量的中间结果，有效降低了路径同质化并构建了容错机制。实验结果表明，相较于现有的 TTS 方法，SRCA 在多个数学数据集上显著提升了推理准确性。

> Mathematical reasoning through Chain-of-Thought (CoT) has emerged as a powerful capability of Large Language Models (LLMs), which can be further enhanced through Test-Time Scaling (TTS) methods like Beam Search and DVTS. However, these methods, despite improving accuracy by allocating more computational resources during inference, often suffer from path homogenization and inefficient use of intermediate results. To address these limitations, we propose Stepwise Reasoning Checkpoint Analysis (SRCA), a framework that introduces checkpoints between reasoning steps. It incorporates two key strategies: (1) Answer-Clustered Search, which groups reasoning paths by their intermediate checkpoint answers to maintain diversity while ensuring quality, and (2) Checkpoint Candidate Augmentation, which leverages all intermediate answers for final decision-making. Our approach effectively reduces path homogenization and creates a fault-tolerant mechanism by utilizing high-quality intermediate results. Experimental results show that SRCA improves reasoning accuracy compared to existing TTS methods across various mathematical datasets.

[Arxiv](https://arxiv.org/abs/2505.17829)