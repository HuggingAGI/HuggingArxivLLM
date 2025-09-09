# DRF：LLM-AGENT 动态声誉过滤框架

发布时间：2025年09月06日

`Agent` `基础理论`

> DRF: LLM-AGENT Dynamic Reputation Filtering Framework

# 摘要

> 随着生成式AI的不断发展，基于大型语言模型（LLMs）的多智能体系统已成为应对复杂任务的有力工具。然而，这类系统在量化智能体性能时仍面临难题，且缺乏评估智能体可信度的有效机制。针对这些问题，我们提出了动态声誉过滤框架DRF。DRF通过构建交互式评分网络来量化智能体性能，设计声誉评分机制以衡量智能体的诚实度与能力，并融入基于置信上限（Upper Confidence Bound）的策略来提升智能体选择效率。实验结果显示，DRF在逻辑推理和代码生成任务中显著提升了任务完成质量与协作效率，为多智能体系统应对大规模任务提供了新思路。

> With the evolution of generative AI, multi - agent systems leveraging large - language models(LLMs) have emerged as a powerful tool for complex tasks. However, these systems face challenges in quantifying agent performance and lack mechanisms to assess agent credibility. To address these issues, we introduce DRF, a dynamic reputation filtering framework. DRF constructs an interactive rating network to quantify agent performance, designs a reputation scoring mechanism to measure agent honesty and capability, and integrates an Upper Confidence Bound - based strategy to enhance agent selection efficiency. Experiments show that DRF significantly improves task completion quality and collaboration efficiency in logical reasoning and code - generation tasks, offering a new approach for multi - agent systems to handle large - scale tasks.

[Arxiv](https://arxiv.org/abs/2509.05764)