# 通过多层自我反思结合自动提示，提升大型语言模型的多步骤数学推理能力

发布时间：2025年06月30日

`LLM应用`

> Advancing Multi-Step Mathematical Reasoning in Large Language Models through Multi-Layered Self-Reflection with Auto-Prompting

# 摘要

> <翻译失败>

> Recent advancements in Large Language Models (LLMs) have significantly improved their problem-solving capabilities. However, these models still struggle when faced with complex multi-step reasoning tasks. In this paper, we propose the Multi-Layered Self-Reflection with Auto-Prompting (MAPS) framework, a novel approach designed to enhance multi-step mathematical reasoning in LLMs by integrating techniques such as Chain of Thought (CoT), Self-Reflection, and Auto-Prompting. Unlike traditional static prompting methods, MAPS employs an iterative refinement process. Initially, the model generates a solution using CoT prompting. When errors are detected, an adaptive self-reflection mechanism identifies and analyzes them, generating tailored prompts to guide corrections. These dynamically adjusted prompts enable the model to iteratively refine its reasoning. Experiments on four well-established benchmarks across multiple LLMs show that MAPS significantly outperforms standard CoT and achieves competitive results with reasoning-optimized models. In addition, MAPS enables general-purpose LLMs to reach performance levels comparable to specialized reasoning models. While deeper reflection layers improve accuracy, they also increase token usage and costs. To balance this trade-off, MAPS strategically limits reflection depth, ensuring an optimal balance between cost and reasoning performance.

[Arxiv](https://arxiv.org/abs/2506.23888)