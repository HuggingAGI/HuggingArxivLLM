# # LLM生成数据的关键要素：多样性如何影响模型微调效果

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）生成的数据在训练下游模型中的应用及其效果。研究重点在于数据多样性和生成数据比例对模型性能的影响，属于LLM的实际应用研究。` `数据科学` `机器学习`

> What Matters in LLM-generated Data: Diversity and Its Effect on Model Fine-Tuning

# 摘要

> 大型语言模型（LLMs）强大的生成能力为缓解特定领域数据稀缺问题并减少标注时间提供了一种有前景的方法——利用LLM生成的数据训练下游模型。然而，近期研究揭示了一个关键问题：在自动生成的数据上进行迭代训练会导致模型性能随时间下降。尽管关于LLM生成数据影响的研究众多，但这些研究往往忽视了数据多样性这一影响数据质量的关键因素。本研究旨在探讨LLM生成数据的多样性对下游模型性能的影响。具体而言，我们研究了LLM生成数据中不同多样性水平如何影响下游模型性能。此外，我们还考察了在不同比例的LLM生成数据（我们称之为合成数据）混合下训练的模型性能。实验结果表明，在分布偏移最小的情况下，适度多样化的LLM生成数据能在标注数据不足的情况下提升模型性能，而高度多样化的生成数据则会产生负面影响。我们希望本研究的经验发现能为未来关于LLMs作为数据生成器的研究提供宝贵的指导。

> With the remarkable generative capabilities of large language models (LLMs), using LLM-generated data to train downstream models has emerged as a promising approach to mitigate data scarcity in specific domains and reduce time-consuming annotations. However, recent studies have highlighted a critical issue: iterative training on self-generated data results in model collapse, where model performance degrades over time. Despite extensive research on the implications of LLM-generated data, these works often neglect the importance of data diversity, a key factor in data quality. In this work, we aim to understand the implications of the diversity of LLM-generated data on downstream model performance. Specifically, we explore how varying levels of diversity in LLM-generated data affect downstream model performance. Additionally, we investigate the performance of models trained on data that mixes different proportions of LLM-generated data, which we refer to as synthetic data. Our experimental results show that, with minimal distribution shift, moderately diverse LLM-generated data can enhance model performance in scenarios with insufficient labeled data, whereas highly diverse generated data has a negative impact. We hope our empirical findings will offer valuable guidance for future studies on LLMs as data generators.

[Arxiv](https://arxiv.org/abs/2506.19262)