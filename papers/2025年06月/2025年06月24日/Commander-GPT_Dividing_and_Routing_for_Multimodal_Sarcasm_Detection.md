# Commander-GPT：多模态讽刺检测的分割与路由方法

发布时间：2025年06月24日

`LLM应用` `讽刺分析`

> Commander-GPT: Dividing and Routing for Multimodal Sarcasm Detection

# 摘要

> 多模态讽刺理解是一个高级认知任务。尽管大型语言模型（LLMs）在许多下游NLP任务中表现优异，但它们在讽刺理解方面仍面临挑战。本文提出了一种名为Commander-GPT的模块化决策路由框架，灵感源自军事指挥理论。与单一依赖LLM能力不同，Commander-GPT通过协调一支由专门化LLM代理组成的团队来执行任务，每个代理专注于特定子任务，例如上下文建模或情感分析。这些代理的输出会被整合到指挥官模块中，最终完成讽刺判断。我们设计了三种类型的指挥官：轻量级编码器基指挥官（如多模态BERT）、能力适中的自回归语言模型（如DeepSeek-VL），以及基于大型LLM的指挥官（如Gemini Pro和GPT-4o），它们以零-shot方式完成任务分配、输出聚合和讽刺决策。在MMSD和MMSD 2.0基准测试中，Commander-GPT相较于现有最先进方法，在F1分数上分别提升了4.4%和11.7%，充分证明了其有效性。

> Multimodal sarcasm understanding is a high-order cognitive task. Although large language models (LLMs) have shown impressive performance on many downstream NLP tasks, growing evidence suggests that they struggle with sarcasm understanding. In this paper, we propose Commander-GPT, a modular decision routing framework inspired by military command theory. Rather than relying on a single LLM's capability, Commander-GPT orchestrates a team of specialized LLM agents where each agent will be selectively assigned to a focused sub-task such as context modeling, sentiment analysis, etc. Their outputs are then routed back to the commander, which integrates the information and performs the final sarcasm judgment. To coordinate these agents, we introduce three types of centralized commanders: (1) a trained lightweight encoder-based commander (e.g., multi-modal BERT); (2) four small autoregressive language models, serving as moderately capable commanders (e.g., DeepSeek-VL); (3) two large LLM-based commander (Gemini Pro and GPT-4o) that performs task routing, output aggregation, and sarcasm decision-making in a zero-shot fashion. We evaluate Commander-GPT on the MMSD and MMSD 2.0 benchmarks, comparing five prompting strategies. Experimental results show that our framework achieves 4.4% and 11.7% improvement in F1 score over state-of-the-art (SoTA) baselines on average, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2506.19420)