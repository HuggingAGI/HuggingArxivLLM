# 超越提示内容：通过内容与格式集成的提示优化提升LLM性能

发布时间：2025年02月06日

`LLM应用

**理由**：这篇论文主要讨论了如何通过优化提示内容和格式来提升大型语言模型（LLMs）的性能。它提出了一种名为“内容-格式集成提示优化（CFPO）”的方法，并通过实验验证了其有效性。这属于对LLM在实际应用中的性能优化，因此归类为“LLM应用”。` `人工智能`

> Beyond Prompt Content: Enhancing LLM Performance via Content-Format Integrated Prompt Optimization

# 摘要

> 大型语言模型（LLMs）在各类任务中表现出色，其实际效果常受提示设计影响。尽管近期研究聚焦于优化提示内容，但提示格式这一关键却常被忽视的维度却鲜有系统性探讨。本文提出内容-格式集成提示优化（CFPO），通过迭代优化过程同时优化提示内容和格式。CFPO利用自然语言变异探索内容变化，并采用动态格式探索策略，系统评估多种格式选项。我们在多个任务和开源LLMs上的广泛评估显示，CFPO相比仅优化内容的方法，性能提升显著。这凸显了内容-格式集成优化的重要性，并提供了一种实用的、模型无关的方法来提升LLM性能。代码将在https://github.com/HenryLau7/CFPO上提供。

> Large Language Models (LLMs) have shown significant capability across various tasks, with their real-world effectiveness often driven by prompt design. While recent research has focused on optimizing prompt content, the role of prompt formatting, a critical but often overlooked dimension, has received limited systematic investigation. In this paper, we introduce Content-Format Integrated Prompt Optimization (CFPO), an innovative methodology that jointly optimizes both prompt content and formatting through an iterative refinement process. CFPO leverages natural language mutations to explore content variations and employs a dynamic format exploration strategy that systematically evaluates diverse format options. Our extensive evaluations across multiple tasks and open-source LLMs demonstrate that CFPO demonstrates measurable performance improvements compared to content-only optimization methods. This highlights the importance of integrated content-format optimization and offers a practical, model-agnostic approach to enhancing LLM performance. Code will be available at https://github.com/HenryLau7/CFPO.

[Arxiv](https://arxiv.org/abs/2502.04295)