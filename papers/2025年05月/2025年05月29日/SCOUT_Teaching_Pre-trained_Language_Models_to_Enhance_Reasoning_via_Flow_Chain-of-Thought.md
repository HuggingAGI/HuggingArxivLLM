# SCOUT：通过流动的思维链，教授预训练语言模型提升推理能力
摘要
SCOUT 通过构建流动的思维链，帮助预训练语言模型在多种推理任务中实现性能提升。

发布时间：2025年05月29日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的推理机制，特别是通过改进递归推理方法来提升模型的推理能力。它提出了新的推理范式（Flow CoT）和微调框架（SCOUT），这些都属于对LLM内部机制的理论研究和优化，因此归类到LLM理论。` `人工智能` `推理系统`

> SCOUT: Teaching Pre-trained Language Models to Enhance Reasoning via Flow Chain-of-Thought

# 摘要

> 思维链提示（Chain of Thought, CoT）通过鼓励逐步推理，显著提升了大型语言模型（LLMs）的推理性能。然而，CoT方法的局限性在于其依赖于中间推理步骤，这在一定程度上限制了其扩展性和通用性。近期研究探索了递归推理的新方向，其中LLMs通过复用内部层在迭代过程中优化潜在表示，而无需显式的CoT监督。尽管这些方法展现出巨大潜力，但它们通常需要昂贵的预训练，并且缺乏一个系统性的框架来指导推理在迭代过程中的演进。针对这一问题，我们提出了Flow Chain of Thought（Flow CoT），一种将递归推理建模为潜在认知状态渐进轨迹的推理范式。Flow CoT将每次迭代视为一个独立的认知阶段，通过逐步加深推理而不依赖人工监督。为了实现这一目标，我们开发了SCOUT（Stepwise Cognitive Optimization Using Teachers），一种轻量级微调框架，无需预训练即可实现Flow CoT风格的推理。SCOUT通过渐进式蒸馏技术将每次迭代与适当容量的教师模型对齐，并引入了一个基于跨注意力的回顾模块，能够整合之前迭代的输出同时保留模型原始计算流程。在八项推理基准测试中，SCOUT在微调过程中不仅显著提高了准确性和解释质量，还实现了高达1.8%的性能提升。定性分析进一步表明，SCOUT能够在迭代过程中实现逐步加深的推理，同时优化信念形成和解释粒度。这些结果不仅充分验证了SCOUT的有效性，还证明了Flow CoT作为增强LLMs推理能力的可扩展框架的实用潜力。

> Chain of Thought (CoT) prompting improves the reasoning performance of large language models (LLMs) by encouraging step by step thinking. However, CoT-based methods depend on intermediate reasoning steps, which limits scalability and generalization. Recent work explores recursive reasoning, where LLMs reuse internal layers across iterations to refine latent representations without explicit CoT supervision. While promising, these approaches often require costly pretraining and lack a principled framework for how reasoning should evolve across iterations. We address this gap by introducing Flow Chain of Thought (Flow CoT), a reasoning paradigm that models recursive inference as a progressive trajectory of latent cognitive states. Flow CoT frames each iteration as a distinct cognitive stage deepening reasoning across iterations without relying on manual supervision. To realize this, we propose SCOUT (Stepwise Cognitive Optimization Using Teachers), a lightweight fine tuning framework that enables Flow CoT style reasoning without the need for pretraining. SCOUT uses progressive distillation to align each iteration with a teacher of appropriate capacity, and a cross attention based retrospective module that integrates outputs from previous iterations while preserving the models original computation flow. Experiments across eight reasoning benchmarks show that SCOUT consistently improves both accuracy and explanation quality, achieving up to 1.8% gains under fine tuning. Qualitative analyses further reveal that SCOUT enables progressively deeper reasoning across iterations refining both belief formation and explanation granularity. These results not only validate the effectiveness of SCOUT, but also demonstrate the practical viability of Flow CoT as a scalable framework for enhancing reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2505.24181)