# # 从实例级别视角深入探索Pythia模型的记忆机制
从实例级别视角深入探索Pythia模型的记忆机制。

发布时间：2025年06月13日

`LLM理论` `人工智能`

> Extending Memorization Dynamics in Pythia Models from Instance-Level Insights

# 摘要

> 大型语言模型具备非凡的逐字记忆能力。尽管已有大量研究探讨了影响模型记忆的因素，但记忆模式的动态演变仍是一个未被充分探索的领域。本文对Pythia模型家族在不同规模和训练步骤下，面对前缀扰动的记忆模式进行了详细分析。通过细粒度的指标，我们研究了模型架构、数据特性和扰动对这些模式的影响。我们的研究发现：(1) 随着模型规模的增大，记忆能力逐步增强，但效率却迅速下降；(2) 随着模型规模的增大，新记忆的获取速率降低，而旧记忆的遗忘速率增加；(3) 数据特性（如token频率、重复次数和不确定性）对已记忆和未记忆样本的影响存在显著差异；(4) 前缀扰动会按扰动强度比例减少记忆并增加生成不确定性，其中冗余度低的样本表现出更高的脆弱性，而大型模型并未展现出额外的鲁棒性。这些发现深化了我们对记忆机制的理解，为训练优化、隐私保护和架构改进提供了直接指导。

> Large language models have demonstrated a remarkable ability for verbatim memorization. While numerous works have explored factors influencing model memorization, the dynamic evolution memorization patterns remains underexplored. This paper presents a detailed analysis of memorization in the Pythia model family across varying scales and training steps under prefix perturbations. Using granular metrics, we examine how model architecture, data characteristics, and perturbations influence these patterns. Our findings reveal that: (1) as model scale increases, memorization expands incrementally while efficiency decreases rapidly; (2) as model scale increases, the rate of new memorization acquisition decreases while old memorization forgetting increases; (3) data characteristics (token frequency, repetition count, and uncertainty) differentially affect memorized versus non-memorized samples; and (4) prefix perturbations reduce memorization and increase generation uncertainty proportionally to perturbation strength, with low-redundancy samples showing higher vulnerability and larger models offering no additional robustness. These findings advance our understanding of memorization mechanisms, with direct implications for training optimization, privacy safeguards, and architectural improvements.

[Arxiv](https://arxiv.org/abs/2506.12321)