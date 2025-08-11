# # 大规模推荐系统中MLLM对齐性的度量方法

发布时间：2025年08月06日

`LLM应用` `推荐系统` `内容推荐`

> A Metric for MLLM Alignment in Large-scale Recommendation

# 摘要

> 多模态推荐已成为现代推荐系统的核心技术，它借助先进的多模态大型语言模型（MLLMs）的内容表示来提升推荐效果。为了让这些表示更好地与推荐系统协同工作，我们需要解决三个关键挑战：静态基准的不准确性、大规模在线评估的高昂成本以及传统指标在表示效果不佳时的失效。为此，我们提出了一种全新的指标——泄漏影响评分（LIS），它不直接评估 MLLMs，而是通过衡量偏好数据的上限来间接评估。我们还分享了如何在实际应用中有效部署 MLLMs 的实用见解。在小红书“发现”页的内容流和展示广告上进行的线上 A/B 测试结果表明，我们的方法显著提升了用户体验和广告价值。

> Multimodal recommendation has emerged as a critical technique in modern recommender systems, leveraging content representations from advanced multimodal large language models (MLLMs). To ensure these representations are well-adapted, alignment with the recommender system is essential. However, evaluating the alignment of MLLMs for recommendation presents significant challenges due to three key issues: (1) static benchmarks are inaccurate because of the dynamism in real-world applications, (2) evaluations with online system, while accurate, are prohibitively expensive at scale, and (3) conventional metrics fail to provide actionable insights when learned representations underperform. To address these challenges, we propose the Leakage Impact Score (LIS), a novel metric for multimodal recommendation. Rather than directly assessing MLLMs, LIS efficiently measures the upper bound of preference data. We also share practical insights on deploying MLLMs with LIS in real-world scenarios. Online A/B tests on both Content Feed and Display Ads of Xiaohongshu's Explore Feed production demonstrate the effectiveness of our proposed method, showing significant improvements in user spent time and advertiser value.

[Arxiv](https://arxiv.org/abs/2508.04963)