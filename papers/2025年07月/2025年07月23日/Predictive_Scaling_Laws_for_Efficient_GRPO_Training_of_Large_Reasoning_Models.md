# 预测缩放定律：大型推理模型的高效 GRPO 训练方法

发布时间：2025年07月23日

`LLM应用

摘要中讨论了如何优化大型语言模型的训练过程，特别是通过预测框架和经验缩放定律来提高资源利用效率。这属于应用层面的优化，因此归类为LLM应用。`

> Predictive Scaling Laws for Efficient GRPO Training of Large Reasoning Models

# 摘要

> 使用强化学习方法（如组相对策略优化，GRPO）对大型语言模型（LLMs）进行推理任务的微调需要大量计算资源。为了解决这一问题，我们提出了一种基于训练动力学的预测框架，旨在优化资源利用。通过对Llama和Qwen模型（3B和8B参数）进行实验，我们根据模型规模、初始性能和训练进展，得出了一个经验缩放定律。该定律能够预测奖励轨迹，并识别出三个一致的训练阶段：缓慢启动、快速提升和平台期。我们发现，当训练超过某个特定的epoch数后，收益明显减少，因此提前停止训练可以在不降低性能的情况下显著节省计算资源。我们的方法适用于多种模型类型，为基于GRPO的高效微调提供了实用的指导。

> Fine-tuning large language models (LLMs) for reasoning tasks using reinforcement learning methods like Group Relative Policy Optimization (GRPO) is computationally expensive. To address this, we propose a predictive framework that models training dynamics and helps optimize resource usage. Through experiments on Llama and Qwen models (3B 8B), we derive an empirical scaling law based on model size, initial performance, and training progress. This law predicts reward trajectories and identifies three consistent training phases: slow start, rapid improvement, and plateau. We find that training beyond certain number of an epoch offers little gain, suggesting earlier stopping can significantly reduce compute without sacrificing performance. Our approach generalizes across model types, providing a practical guide for efficient GRPO-based fine-tuning.

[Arxiv](https://arxiv.org/abs/2507.18014)