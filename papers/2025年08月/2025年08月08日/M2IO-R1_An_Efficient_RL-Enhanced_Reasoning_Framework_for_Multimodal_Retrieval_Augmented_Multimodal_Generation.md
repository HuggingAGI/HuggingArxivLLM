# M2IO-R1：高效强化学习增强推理框架，专为多模态检索增强生成设计。

发布时间：2025年08月08日

`LLM应用` `多模态` `计算机视觉`

> M2IO-R1: An Efficient RL-Enhanced Reasoning Framework for Multimodal Retrieval Augmented Multimodal Generation

# 摘要

> 当前关于多模态检索增强生成（MRAG）的研究支持多样化的多模态输入，但输出仍局限于单一模态，这限制了其表达能力和实际应用价值。相比之下，现实世界的应用通常需要同时支持多模态输入和输出，以实现有效的沟通和基于事实的推理。受到强化学习（RL）在大型语言模型（LLMs）复杂推理任务中 recent success 的启发，我们采用 RL 作为一种原理性和有效的范式，来应对多模态输出生成中固有的多步骤、结果驱动的挑战。在这里，我们引入了 M2IO-R1，一个支持多模态输入和输出的新型多模态检索增强多模态生成（MRAMG）框架。我们框架的核心是一个基于 RL 的插入器 Inserter-R1-3B，它通过 Group Relative Policy Optimization 进行训练，以一种可控且语义对齐的方式指导图像选择和放置。实验结果表明，我们轻量级的 3B 插入器在推理能力上表现出色，显著降低了延迟，无论是在质量还是效率上都超越了基线模型。

> Current research on Multimodal Retrieval-Augmented Generation (MRAG) enables diverse multimodal inputs but remains limited to single-modality outputs, restricting expressive capacity and practical utility. In contrast, real-world applications often demand both multimodal inputs and multimodal outputs for effective communication and grounded reasoning. Motivated by the recent success of Reinforcement Learning (RL) in complex reasoning tasks for Large Language Models (LLMs), we adopt RL as a principled and effective paradigm to address the multi-step, outcome-driven challenges inherent in multimodal output generation. Here, we introduce M2IO-R1, a novel framework for Multimodal Retrieval-Augmented Multimodal Generation (MRAMG) that supports both multimodal inputs and outputs. Central to our framework is an RL-based inserter, Inserter-R1-3B, trained with Group Relative Policy Optimization to guide image selection and placement in a controllable and semantically aligned manner. Empirical results show that our lightweight 3B inserter achieves strong reasoning capabilities with significantly reduced latency, outperforming baselines in both quality and efficiency.

[Arxiv](https://arxiv.org/abs/2508.06328)