# COPA: 比较那些看似无法比较的对象，探索 Pareto 前沿

发布时间：2025年03月18日

`LLM应用` `自动化机器学习`

> COPA: Comparing the Incomparable to Explore the Pareto Front

# 摘要

> 在机器学习（ML）中，选择模型时通常需要兼顾多个目标。然而，如何比较、聚合并权衡这些目标常常让人困惑，因为它们可能以不同的单位或尺度衡量。例如，在部署大型语言模型（LLMs）时，我们不仅关注性能，还关注二氧化碳消耗。本研究探讨如何合理比较和聚合目标，以导航帕累托前沿。为此，我们提出通过目标的CDF（累积分布函数），利用相对排名进行近似，使不可比较的目标变得可比较。这使我们能够在匹配用户偏好时聚合目标，使从业者能够有意义地在帕累托前沿中导航和搜索模型。我们的方法在大型语言模型选择、领域泛化和AutoML基准测试等领域展现出潜在影响，传统的目标聚合和标准化方法在此类场景下往往失效。

> In machine learning (ML), it is common to account for multiple objectives when, e.g., selecting a model to deploy. However, it is often unclear how one should compare, aggregate and, ultimately, trade-off these objectives, as they might be measured in different units or scales. For example, when deploying large language models (LLMs), we might not only care about their performance, but also their CO2 consumption. In this work, we investigate how objectives can be sensibly compared and aggregated to navigate their Pareto front. To do so, we propose to make incomparable objectives comparable via their CDFs, approximated by their relative rankings. This allows us to aggregate them while matching user-specific preferences, allowing practitioners to meaningfully navigate and search for models in the Pareto front. We demonstrate the potential impact of our methodology in diverse areas such as LLM selection, domain generalization, and AutoML benchmarking, where classical ways to aggregate and normalize objectives fail.

[Arxiv](https://arxiv.org/abs/2503.14321)