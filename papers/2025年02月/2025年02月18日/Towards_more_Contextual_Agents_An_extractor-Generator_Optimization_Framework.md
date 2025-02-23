# # 摘要
构建更情境化的智能体：提取器与生成器协同优化框架

发布时间：2025年02月18日

`Agent` `人工智能`

> Towards more Contextual Agents: An extractor-Generator Optimization Framework

# 摘要

> 基于大语言模型（LLM）的智能体在通用任务中表现优异，但在特定行业或研究领域等场景下，由于缺乏专业知识，常导致结果不够精准。为解决这一问题，我们提出了一种通过优化提示来提升智能体在特定场景下适应性的系统化方法。手动优化提示费时费力且不够可靠，因此我们开发了Extractor-Generator框架，用于自动化提升基于LLM的智能体性能。该框架通过两步实现：首先从高质量输入输出示例中提取特征，然后通过迭代优化策略生成更佳提示。这一方法显著提升了提示的泛化能力和适应性，特别在需要保持语义一致性和减少错误传播的关键任务中表现突出。尽管最初设计用于单阶段流程，但该方法同样适用于多阶段流程，在各种智能体系统中具有广泛应用价值。实验证明，我们的框架能显著提升智能体性能，为基于LLM的上下文智能体提供了一种高效可靠的解决方案。


> Large Language Model (LLM)-based agents have demonstrated remarkable success in solving complex tasks across a wide range of general-purpose applications. However, their performance often degrades in context-specific scenarios, such as specialized industries or research domains, where the absence of domain-relevant knowledge leads to imprecise or suboptimal outcomes. To address this challenge, our work introduces a systematic approach to enhance the contextual adaptability of LLM-based agents by optimizing their underlying prompts-critical components that govern agent behavior, roles, and interactions. Manually crafting optimized prompts for context-specific tasks is labor-intensive, error-prone, and lacks scalability. In this work, we introduce an Extractor-Generator framework designed to automate the optimization of contextual LLM-based agents. Our method operates through two key stages: (i) feature extraction from a dataset of gold-standard input-output examples, and (ii) prompt generation via a high-level optimization strategy that iteratively identifies underperforming cases and applies self-improvement techniques. This framework substantially improves prompt adaptability by enabling more precise generalization across diverse inputs, particularly in context-specific tasks where maintaining semantic consistency and minimizing error propagation are critical for reliable performance. Although developed with single-stage workflows in mind, the approach naturally extends to multi-stage workflows, offering broad applicability across various agent-based systems. Empirical evaluations demonstrate that our framework significantly enhances the performance of prompt-optimized agents, providing a structured and efficient approach to contextual LLM-based agents.

[Arxiv](https://arxiv.org/abs/2502.12926)