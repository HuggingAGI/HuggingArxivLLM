# 提升LLM代码生成能力：通过多智能体协作与运行时调试进行系统性评估以提升准确性、可靠性和响应速度

发布时间：2025年05月04日

`LLM应用` `软件工程` `计算机科学`

> Enhancing LLM Code Generation: A Systematic Evaluation of Multi-Agent Collaboration and Runtime Debugging for Improved Accuracy, Reliability, and Latency

# 摘要

> 大型语言模型（LLMs）在自动化代码生成领域的应用已成为重要研究焦点。随着模型的持续演进，它们在理解和生成复杂代码结构方面的能力为实现精确代码生成的自动化复杂编程任务带来了新可能。尽管当代基础模型在代码生成方面取得了积极进展，研究人员仍在探索优化的后训练策略以提升代码质量，包括监督微调、检索增强生成（RAG）、调试等。

本文将多智能体协作和基于运行时执行信息的调试相结合，旨在提升代码生成的功能性、可靠性和实际应用价值。通过实证研究，我们不仅评估了单一策略的表现，还深入研究了所提组合策略的效果。本研究采用了19种LLMs，全面分析了不同编程活动组合及训练范式对代码生成效能的影响。

特别地，我们构建了一个结合两种策略的链式系统，利用两个常用的代码生成基准数据集，评估了它们对功能性准确性、代码可靠性和生成延迟的综合影响。我们的研究发现为寻求 robust AI驱动代码解决方案的组织提供了宝贵见解，指导其选择能够更好适应复杂后训练策略的模型，从而推动更高效、可靠的代码生成技术的采用。

> The use of large language models (LLMs) for automated code generation has emerged as a significant focus within AI research. As these pretrained models continue to evolve, their ability to understand and generate complex code structures has opened new possibilities for automating intricate programming tasks for the sake of accurate code generation. Although contemporary foundational models demonstrate promoting results, researchers continue to explore optimal post-training strategies to enhance code quality. These include supervised fine-tuning, retrieval-augmented generation (RAG), debugging, and many others. In this paper, we combine two widely used approaches namely multi-agent collaboration and runtime execution information-based debugging, for improving code generation functionality, reliability, and practical applicability. We perform an empirical study in order to extend the evaluation of the individual strategies as well as the proposed composition of the activities of both strategies. Our study use 19 LLMs to examines the performance of individual and the proposed strategies, offering comprehensive insights into how different programming activities compositions and training paradigms influence code generation effectiveness. In particular, we implement a chained system that combines both strategies to assess their combined impact on functional accuracy, code reliability, and generation latency using two benchmark datasets commonly used for code generation. Our findings provide valuable insights for organizations seeking robust AI-driven coding solutions by guiding them in selecting models that can better adapt to complex post-training strategies, ultimately fostering the adoption of more effective and reliable code generation technologies.

[Arxiv](https://arxiv.org/abs/2505.02133)