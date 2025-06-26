# LLM生成数据的关键：多样性及其对模型微调的影响

发布时间：2025年06月23日

`LLM应用` `机器学习`

> What Matters in LLM-generated Data: Diversity and Its Effect on Model Fine-Tuning

# 摘要

> 大型语言模型（LLMs）的卓越生成能力使其成为缓解特定领域数据稀缺性和减少标注工作时间的理想工具。然而，近期研究表明，基于自动生成数据的迭代训练会导致模型性能随时间下降的“模型坍塌”现象。尽管已有大量研究探讨了LLM生成数据的潜在影响，但数据多样性这一关键因素往往被忽视。本研究聚焦于LLM生成数据的多样性对下游模型性能的影响。我们发现，适度多样化的生成数据能够在标注数据不足时提升模型性能，而高度多样化的生成数据则可能产生负面影响。这些发现为未来研究提供了宝贵的指导，特别是在LLMs作为数据生成器的应用方面。

> With the remarkable generative capabilities of large language models (LLMs), using LLM-generated data to train downstream models has emerged as a promising approach to mitigate data scarcity in specific domains and reduce time-consuming annotations. However, recent studies have highlighted a critical issue: iterative training on self-generated data results in model collapse, where model performance degrades over time. Despite extensive research on the implications of LLM-generated data, these works often neglect the importance of data diversity, a key factor in data quality. In this work, we aim to understand the implications of the diversity of LLM-generated data on downstream model performance. Specifically, we explore how varying levels of diversity in LLM-generated data affect downstream model performance. Additionally, we investigate the performance of models trained on data that mixes different proportions of LLM-generated data, which we refer to as synthetic data. Our experimental results show that, with minimal distribution shift, moderately diverse LLM-generated data can enhance model performance in scenarios with insufficient labeled data, whereas highly diverse generated data has a negative impact. We hope our empirical findings will offer valuable guidance for future studies on LLMs as data generators.

[Arxiv](https://arxiv.org/abs/2506.19262)