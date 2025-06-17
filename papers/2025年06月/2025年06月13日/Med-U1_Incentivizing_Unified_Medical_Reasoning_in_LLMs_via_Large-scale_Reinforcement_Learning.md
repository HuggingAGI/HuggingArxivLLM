# Med-U1：激励大规模强化学习在LLMs中实现统一医疗推理

发布时间：2025年06月13日

`LLM应用` `问答系统`

> Med-U1: Incentivizing Unified Medical Reasoning in LLMs via Large-scale Reinforcement Learning

# 摘要

> 医学问答 (QA) 涵盖了从多项选择题 (MCQ) 到开放性文本生成，再到复杂计算推理等多种任务类型。尽管任务类型丰富，但目前尚未出现一个能够统一实现高质量医学问答的框架。尽管近期推理增强型大型语言模型 (LLMs) 取得了进展，但其在实现全面医学理解方面的能力仍有待探索。本文提出了一种名为 Med-U1 的统一框架，旨在通过强化学习实现多种医学问答任务的稳健推理，涵盖从多项选择题到复杂生成和计算任务。Med-U1 采用带有混合规则的二元奖励函数的纯大规模强化学习，并引入长度惩罚项来控制输出的冗长程度。通过多目标奖励优化，Med-U1 指导 LLMs 生成简洁且可验证的推理链。实验结果表明，Med-U1 在多个具有挑战性的医学问答基准测试中显著提升了性能，甚至超越了更大规模的专业化和专有模型。此外，Med-U1 在处理分布外 (OOD) 任务时也表现出强大的泛化能力。通过广泛的分析，我们为医学 LLMs 的训练策略、推理链长度控制和奖励设计提供了深入的见解。代码将公开发布。

> Medical Question-Answering (QA) encompasses a broad spectrum of tasks, including multiple choice questions (MCQ), open-ended text generation, and complex computational reasoning. Despite this variety, a unified framework for delivering high-quality medical QA has yet to emerge. Although recent progress in reasoning-augmented large language models (LLMs) has shown promise, their ability to achieve comprehensive medical understanding is still largely unexplored. In this paper, we present Med-U1, a unified framework for robust reasoning across medical QA tasks with diverse output formats, ranging from MCQs to complex generation and computation tasks. Med-U1 employs pure large-scale reinforcement learning with mixed rule-based binary reward functions, incorporating a length penalty to manage output verbosity. With multi-objective reward optimization, Med-U1 directs LLMs to produce concise and verifiable reasoning chains. Empirical results reveal that Med-U1 significantly improves performance across multiple challenging Med-QA benchmarks, surpassing even larger specialized and proprietary models. Furthermore, Med-U1 demonstrates robust generalization to out-of-distribution (OOD) tasks. Extensive analysis presents insights into training strategies, reasoning chain length control, and reward design for medical LLMs. The code will be released.

[Arxiv](https://arxiv.org/abs/2506.12307)