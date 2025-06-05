# # Crowd-SFT：通过众包实现 LLM 对齐

发布时间：2025年06月04日

`LLM应用` `人工智能` `机器学习`

> Crowd-SFT: Crowdsourcing for LLM Alignment

# 摘要

> 大型语言模型（LLMs）越来越依赖监督微调（SFT）和从人类反馈中强化学习（RLHF）来对齐模型输出与人类偏好。尽管RLHF采用独立奖励模型的强化学习方法，SFT则使用人工整理的数据集进行监督学习。传统上，这两种方法都依赖于经过筛选的小规模标注团队，导致成本高、易偏见且扩展性有限。我们提出了一种开放的、基于众包的微调框架，通过更广泛的反馈收集解决这些限制，而无需大量标注者培训。我们的框架通过与Shapley值相关联的积分奖励系统实现激励公平，并通过迭代模型更新引导模型收敛。我们的多模型选择框架实现了高达55%的目标距离减少，支持后续实验验证基于积分奖励机制与Shapley值的紧密对齐，从而支持公平和可扩展的参与。

> Large Language Models (LLMs) increasingly rely on Supervised Fine-Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF) to align model responses with human preferences. While RLHF employs a reinforcement learning approach with a separate reward model, SFT uses human-curated datasets for supervised learning. Both approaches traditionally depend on small, vetted groups of annotators, making them costly, prone to bias, and limited in scalability. We propose an open, crowd-sourced fine-tuning framework that addresses these limitations by enabling broader feedback collection for SFT without extensive annotator training. Our framework promotes incentive fairness via a point-based reward system correlated with Shapley values and guides model convergence through iterative model updates. Our multi-model selection framework demonstrates up to a 55% reduction in target distance over single-model selection, enabling subsequent experiments that validate our point-based reward mechanism's close alignment with Shapley values (a well-established method for attributing individual contributions) thereby supporting fair and scalable participation.

[Arxiv](https://arxiv.org/abs/2506.04063)