# 面向大型语言模型的不确定性驱动自适应自对齐框架

发布时间：2025年07月23日

`LLM理论` `人工智能`

> An Uncertainty-Driven Adaptive Self-Alignment Framework for Large Language Models

# 摘要

> 大型语言模型（LLMs）在指令理解和通用推理方面取得了显著进展。然而，如何在无需人工标注的情况下实现与人类意图和安全规范的高质量对齐，仍然是一个核心挑战。为此，我们提出了一种基于不确定性的自适应自我对齐（UDASA）框架，旨在以完全自动化的方式提升LLM的对齐效果。具体而言，UDASA首先为每个输入生成多个响应，并从语义、事实性和价值对齐三个维度量化输出的不确定性。基于这些不确定性评分，框架构建偏好对，并根据不确定性差异将训练样本分为三个阶段：保守、中等和探索性。随后，模型逐步在这三个阶段进行优化。此外，我们还开展了一系列初步研究，以验证核心设计假设，并为提出的框架提供强有力的实证支持。实验结果表明，UDASA在多个任务上优于现有对齐方法，包括无害性、有用性、真实性和受控情感生成，显著提升了模型性能。

> Large Language Models (LLMs) have demonstrated remarkable progress in instruction following and general-purpose reasoning. However, achieving high-quality alignment with human intent and safety norms without human annotations remains a fundamental challenge. In this work, we propose an Uncertainty-Driven Adaptive Self-Alignment (UDASA) framework designed to improve LLM alignment in a fully automated manner. UDASA first generates multiple responses for each input and quantifies output uncertainty across three dimensions: semantics, factuality, and value alignment. Based on these uncertainty scores, the framework constructs preference pairs and categorizes training samples into three stages, conservative, moderate, and exploratory, according to their uncertainty difference. The model is then optimized progressively across these stages. In addition, we conduct a series of preliminary studies to validate the core design assumptions and provide strong empirical motivation for the proposed framework. Experimental results show that UDASA outperforms existing alignment methods across multiple tasks, including harmlessness, helpfulness, truthfulness, and controlled sentiment generation, significantly improving model performance.

[Arxiv](https://arxiv.org/abs/2507.17477)