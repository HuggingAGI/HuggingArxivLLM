# SEPS：大型语言模型中稳健无学习的可分性度量指标

发布时间：2025年05月20日

`LLM理论` `人工智能` `模型训练`

> SEPS: A Separability Measure for Robust Unlearning in LLMs

# 摘要

> 机器遗忘技术旨在让大型语言模型（LLMs）有选择地遗忘特定知识，同时保留重要信息。现有的遗忘评估指标主要考察模型是否能够正确回答需要保留的问题，同时拒绝回答需要遗忘的问题，但它们无法反映现实场景中需要遗忘的问题很少单独出现的情况。事实上，需要遗忘和保留的问题往往同时出现在同一个提示中，因此对混合查询的评估至关重要。我们引入了SEPS框架，它能够明确衡量模型在单一提示中同时遗忘和保留信息的能力。通过在三个基准数据集上的广泛实验，我们发现现有遗忘方法存在两种主要失效模式：(1) 非目标遗忘在出现需要遗忘的问题时，会无差别地删除需要遗忘和保留的内容；(2) 目标遗忘过度拟合单个查询场景，在处理多个查询时会导致灾难性失败。为了解决这些问题，我们提出了混合提示（MP）遗忘策略，该策略将遗忘和保留查询整合到统一的训练目标中。我们的方法显著提升了遗忘效果，即使在包含多达八个混合遗忘和保留查询的复杂提示场景下，也能表现出强大的鲁棒性。

> Machine unlearning aims to selectively remove targeted knowledge from Large Language Models (LLMs), ensuring they forget specified content while retaining essential information. Existing unlearning metrics assess whether a model correctly answers retain queries and rejects forget queries, but they fail to capture real-world scenarios where forget queries rarely appear in isolation. In fact, forget and retain queries often coexist within the same prompt, making mixed-query evaluation crucial.
  We introduce SEPS, an evaluation framework that explicitly measures a model's ability to both forget and retain information within a single prompt. Through extensive experiments across three benchmarks, we identify two key failure modes in existing unlearning methods: (1) untargeted unlearning indiscriminately erases both forget and retain content once a forget query appears, and (2) targeted unlearning overfits to single-query scenarios, leading to catastrophic failures when handling multiple queries. To address these issues, we propose Mixed Prompt (MP) unlearning, a strategy that integrates both forget and retain queries into a unified training objective. Our approach significantly improves unlearning effectiveness, demonstrating robustness even in complex settings with up to eight mixed forget and retain queries in a single prompt.

[Arxiv](https://arxiv.org/abs/2505.14832)