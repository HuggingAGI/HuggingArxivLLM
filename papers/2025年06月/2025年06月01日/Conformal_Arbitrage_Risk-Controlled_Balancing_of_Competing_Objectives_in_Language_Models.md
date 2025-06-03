# **一致套衡：在语言模型中实现风险可控的目标平衡**

发布时间：2025年06月01日

`LLM应用` `可信AI`

> Conformal Arbitrage: Risk-Controlled Balancing of Competing Objectives in Language Models

# 摘要

> 现代语言模型的部署往往需要在多个相互竞争的目标之间找到平衡，例如有用性与无害性、成本与准确性以及奖励与安全性。我们提出了Conformal Arbitrage这一后验框架，它通过学习一个数据驱动的阈值，来协调一个针对主要目标优化的主模型和一个更为保守的守护者（可以是另一个模型或与护栏目标对齐的人类领域专家）。该阈值通过符合式风险控制进行校准，从而在有限样本、无分布假设的情况下，确保事实错误或安全违规等不良事件的长期频率不超过用户指定的配额。由于Conformal Arbitrage完全基于API层面运作，无需访问模型的logits或更新模型权重，因此它可以与基于权重的对齐技术互补，并与现有的成本感知级联无缝集成。实证研究表明，Conformal Arbitrage能够追踪高效前沿，使用户能够在定义一个目标的可接受性能水平的同时，在另一个目标上实现最大效用。我们发现，与在模型之间随机路由相比，我们的方法在准确性和成本匹配方面表现更优。这些特性使Conformal Arbitrage成为在广泛且可能相互竞争的目标范围内，实现可信且经济的大语言模型部署的实用且理论基础扎实的工具。


> Modern language model deployments must often balance competing objectives, for example, helpfulness versus harmlessness, cost versus accuracy, and reward versus safety. We introduce Conformal Arbitrage, a post hoc framework that learns a data driven threshold to mediate between a Primary model optimized for a primary objective and a more conservative Guardian which could be another model or a human domain expert aligned with a guardrail objective. The threshold is calibrated with conformal risk control, yielding finite sample, distribution free guarantees that the long run frequency of undesirable events, such as factual errors or safety violations, does not exceed a user specified quota. Because Conformal Arbitrage operates wholly at the API level, without requiring access to model logits or updating model weights, it complements weight based alignment techniques and integrates seamlessly with existing cost aware cascades. Empirically, Conformal Arbitrage traces an efficient frontier, allowing users to define an acceptable performance level for one objective while maximizing utility in another. We observe that our method outperforms, in terms of accuracy, cost matched random routing between models. These properties make Conformal Arbitrage a practical, theoretically grounded tool for trustworthy and economical deployment of large language models across a broad range of potentially competing objectives.

[Arxiv](https://arxiv.org/abs/2506.00911)