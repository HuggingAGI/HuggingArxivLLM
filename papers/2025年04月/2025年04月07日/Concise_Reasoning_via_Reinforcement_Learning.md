# 强化学习助力简洁推理

发布时间：2025年04月07日

`LLM理论` `模型优化`

> Concise Reasoning via Reinforcement Learning

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但推理模型的token使用量巨大，导致计算成本、资源需求和响应时间激增。本研究重新审视了强化学习（RL）的核心原则，通过数学分析揭示，生成冗长回应的倾向本质上源于训练过程中基于RL的优化。这一发现挑战了当前普遍认为更长回应更准确的假设。实际上，我们发现简洁性和准确性之间存在一种自然的关联性，这一点长期被忽视。更重要的是，我们证明在训练后引入一个使用少量问题和有限资源的二次RL阶段，可以显著减少模型的思维链，同时保持甚至提升准确性。最终，我们通过广泛的实验结果验证了这一结论。

> Despite significant advancements in large language models (LLMs), a major drawback of reasoning models is their enormous token usage, which increases computational cost, resource requirements, and response time. In this work, we revisit the core principles of reinforcement learning (RL) and, through mathematical analysis, demonstrate that the tendency to generate lengthy responses arises inherently from RL-based optimization during training. This finding questions the prevailing assumption that longer responses inherently improve reasoning accuracy. Instead, we uncover a natural correlation between conciseness and accuracy that has been largely overlooked. Moreover, we show that introducing a secondary phase of RL post-training, using a small set of problems and limited resources, can significantly reduce a model's chain of thought while maintaining or even enhancing accuracy. Finally, we validate our conclusions through extensive experimental results.

[Arxiv](https://arxiv.org/abs/2504.05185)