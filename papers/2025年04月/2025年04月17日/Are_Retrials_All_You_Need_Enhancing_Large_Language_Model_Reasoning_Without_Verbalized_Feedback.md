# 重审是否足够？无需语言化反馈，提升大型语言模型推理能力

发布时间：2025年04月17日

`LLM应用` `人工智能`

> Are Retrials All You Need? Enhancing Large Language Model Reasoning Without Verbalized Feedback

# 摘要

> 大型语言模型（LLMs）的突破加速了通用自主代理的发展，在跨领域复杂推理任务中展现出卓越性能。这一进展催生了大量基于提示的推理框架。近期，研究聚焦于通过自我评估和口头反馈优化输出的迭代推理策略。然而，这些策略需增加计算复杂度，使模型识别并修正错误，导致成本大幅上升。

本研究提出“无反馈重试”概念，这是一种简单却强大的机制，允许LLMs在发现答案错误时重新尝试解决问题，从而提升推理框架。与传统迭代优化方法不同，我们的方法无需明确的自我反思或口头反馈，简化了优化过程。

研究发现，基于简单重试的方法往往超越复杂推理框架，表明复杂方法的收益未必能抵消其计算成本。本研究挑战了更复杂的推理策略必然带来更好性能的普遍假设，揭示了更简单高效的方法如何实现最优结果。

那么，仅需重试就足够了吗？

> Recent advancements in large language models (LLMs) have catalyzed the development of general-purpose autonomous agents, demonstrating remarkable performance in complex reasoning tasks across various domains. This surge has spurred the evolution of a plethora of prompt-based reasoning frameworks. A recent focus has been on iterative reasoning strategies that refine outputs through self-evaluation and verbalized feedback. However, these strategies require additional computational complexity to enable models to recognize and correct their mistakes, leading to a significant increase in their cost. In this work, we introduce the concept of ``retrials without feedback'', an embarrassingly simple yet powerful mechanism for enhancing reasoning frameworks by allowing LLMs to retry problem-solving attempts upon identifying incorrect answers. Unlike conventional iterative refinement methods, our method does not require explicit self-reflection or verbalized feedback, simplifying the refinement process. Our findings indicate that simpler retrial-based approaches often outperform more sophisticated reasoning frameworks, suggesting that the benefits of complex methods may not always justify their computational costs. By challenging the prevailing assumption that more intricate reasoning strategies inherently lead to better performance, our work offers new insights into how simpler, more efficient approaches can achieve optimal results. So, are retrials all you need?

[Arxiv](https://arxiv.org/abs/2504.12951)