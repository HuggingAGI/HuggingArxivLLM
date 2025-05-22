# STAR-R1：强化多模态LLM实现空间变换推理

发布时间：2025年05月21日

`LLM应用` `图像处理` `计算机视觉`

> STAR-R1: Spacial TrAnsformation Reasoning by Reinforcing Multimodal LLMs

# 摘要

> 多模态大型语言模型（MLLMs）在多种任务中表现优异，但在空间推理能力上与人类仍有显著差距。我们通过转换驱动视觉推理（TVR）这一具有挑战性的任务，深入探究了这一差距。TVR要求在不同视角下识别图像中的物体变换，这对模型提出了更高要求。然而，传统的监督微调（SFT）在跨视角设置中难以生成连贯的推理路径，而稀疏奖励强化学习（RL）则面临探索效率低下和收敛速度慢的难题。针对这些问题，我们提出了STAR-R1，一个创新性框架，将单阶段RL范式与专为TVR设计的细粒度奖励机制相结合。STAR-R1通过对部分正确性给予奖励，同时对过度枚举和被动不作为进行惩罚，实现了高效探索和精准推理。全面评估结果表明，STAR-R1在全部11项指标上达到最先进水平，并在跨视角场景中较SFT提升了23%。进一步分析揭示了STAR-R1的类人行为特征，并突显其通过比较所有对象以提升空间推理的独特能力。本研究为推进多模态大型语言模型和推理模型的研究提供了重要见解。相关代码、模型权重及数据集将在https://github.com/zongzhao23/STAR-R1公开发布。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities across diverse tasks, yet they lag significantly behind humans in spatial reasoning. We investigate this gap through Transformation-Driven Visual Reasoning (TVR), a challenging task requiring identification of object transformations across images under varying viewpoints. While traditional Supervised Fine-Tuning (SFT) fails to generate coherent reasoning paths in cross-view settings, sparse-reward Reinforcement Learning (RL) suffers from inefficient exploration and slow convergence. To address these limitations, we propose STAR-R1, a novel framework that integrates a single-stage RL paradigm with a fine-grained reward mechanism tailored for TVR. Specifically, STAR-R1 rewards partial correctness while penalizing excessive enumeration and passive inaction, enabling efficient exploration and precise reasoning. Comprehensive evaluations demonstrate that STAR-R1 achieves state-of-the-art performance across all 11 metrics, outperforming SFT by 23% in cross-view scenarios. Further analysis reveals STAR-R1's anthropomorphic behavior and highlights its unique ability to compare all objects for improving spatial reasoning. Our work provides critical insights in advancing the research of MLLMs and reasoning models. The codes, model weights, and data will be publicly available at https://github.com/zongzhao23/STAR-R1.

[Arxiv](https://arxiv.org/abs/2505.15804)