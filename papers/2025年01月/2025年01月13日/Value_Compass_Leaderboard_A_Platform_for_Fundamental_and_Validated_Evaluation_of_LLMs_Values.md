# 价值罗盘排行榜：LLMs价值评估的基础与验证平台

发布时间：2025年01月13日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的价值观对齐问题，并提出了一个新的评估框架（价值观指南针排行榜）来澄清、评估和量化LLMs的价值观。这涉及到对LLMs内在价值观的理论探讨和评估方法的创新，属于对LLMs的理论研究和价值观对齐的理论框架设计，因此归类为LLM理论。` `人工智能` `价值观评估`

> Value Compass Leaderboard: A Platform for Fundamental and Validated Evaluation of LLMs Values

# 摘要

> 随着大型语言模型（LLMs）的显著突破，将其价值观与人类对齐已成为其负责任开发和定制应用的关键。然而，目前仍缺乏满足以下三个理想目标的LLMs价值观评估：(1) 价值观澄清：我们期望精确而全面地揭示LLMs的潜在价值观，而当前评估主要局限于偏见和毒性等安全风险。(2) 评估有效性：现有的静态开源基准容易受到数据污染的影响，并且随着LLMs的发展迅速过时。此外，这些判别性评估仅揭示了LLMs对价值观的认知，而非对其行为符合价值观的有效评估。(3) 价值观多元性：在衡量LLMs价值观对齐时，跨个体和文化的多元人类价值观在很大程度上被忽视。为此，我们提出了价值观指南针排行榜，并设计了三个模块：(i) 基于动机上不同的基本价值观，从整体视角澄清LLMs的潜在价值观；(ii) 应用生成性演化评估框架，为不断演化的LLMs提供适应性测试项目，并从现实场景中的行为直接识别价值观；(iii) 提出了一种度量方法，将LLMs与特定价值观的对齐量化为多个维度的加权和，权重由多元价值观决定。

> As Large Language Models (LLMs) achieve remarkable breakthroughs, aligning their values with humans has become imperative for their responsible development and customized applications. However, there still lack evaluations of LLMs values that fulfill three desirable goals. (1) Value Clarification: We expect to clarify the underlying values of LLMs precisely and comprehensively, while current evaluations focus narrowly on safety risks such as bias and toxicity. (2) Evaluation Validity: Existing static, open-source benchmarks are prone to data contamination and quickly become obsolete as LLMs evolve. Additionally, these discriminative evaluations uncover LLMs' knowledge about values, rather than valid assessments of LLMs' behavioral conformity to values. (3) Value Pluralism: The pluralistic nature of human values across individuals and cultures is largely ignored in measuring LLMs value alignment. To address these challenges, we presents the Value Compass Leaderboard, with three correspondingly designed modules. It (i) grounds the evaluation on motivationally distinct \textit{basic values to clarify LLMs' underlying values from a holistic view; (ii) applies a \textit{generative evolving evaluation framework with adaptive test items for evolving LLMs and direct value recognition from behaviors in realistic scenarios; (iii) propose a metric that quantifies LLMs alignment with a specific value as a weighted sum over multiple dimensions, with weights determined by pluralistic values.

[Arxiv](https://arxiv.org/abs/2501.07071)