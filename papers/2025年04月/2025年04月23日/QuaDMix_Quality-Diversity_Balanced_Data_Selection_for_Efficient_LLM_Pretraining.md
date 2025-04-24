# **QuaDMix**: 通过质量与多样性平衡的数据选择实现高效LLM预训练

发布时间：2025年04月23日

`LLM理论` `数据科学` `人工智能`

> QuaDMix: Quality-Diversity Balanced Data Selection for Efficient LLM Pretraining

# 摘要

> 质量与多样性是大型语言模型（LLMs）训练数据的两大关键指标，对模型性能产生积极影响。现有研究通常分别优化这两个指标，通常先进行质量过滤，然后再调整数据比例。然而，这些方法忽视了质量和多样性之间固有的权衡关系，因此需要同时考虑这两个方面。在固定训练配额的情况下，评估每个数据点的质量及其对整个数据集的补充效果至关重要。本文介绍了一个名为QuaDMix的统一数据选择框架，它在平衡质量和多样性的同时，自动优化LLM预训练的数据分布。具体来说，我们首先提出多个标准来衡量数据质量，并通过领域分类来区分数据点，从而衡量整体多样性。QuaDMix随后采用一个统一的参数化数据采样函数，根据这些质量和多样性相关的标签确定每个数据点的采样概率。为了加速QuaDMix框架中相关参数的搜索，我们在较小的模型上进行模拟实验，并使用LightGBM进行参数搜索，灵感来源于RegMix方法。我们在多样化的模型和数据集上的实验表明，QuaDMix在多个基准测试中实现了平均7.2%的性能提升。这些结果优于单独的质量和多样性策略，突显了平衡数据质量和多样性的重要性和能力。

> Quality and diversity are two critical metrics for the training data of large language models (LLMs), positively impacting performance. Existing studies often optimize these metrics separately, typically by first applying quality filtering and then adjusting data proportions. However, these approaches overlook the inherent trade-off between quality and diversity, necessitating their joint consideration. Given a fixed training quota, it is essential to evaluate both the quality of each data point and its complementary effect on the overall dataset. In this paper, we introduce a unified data selection framework called QuaDMix, which automatically optimizes the data distribution for LLM pretraining while balancing both quality and diversity. Specifically, we first propose multiple criteria to measure data quality and employ domain classification to distinguish data points, thereby measuring overall diversity. QuaDMix then employs a unified parameterized data sampling function that determines the sampling probability of each data point based on these quality and diversity related labels. To accelerate the search for the optimal parameters involved in the QuaDMix framework, we conduct simulated experiments on smaller models and use LightGBM for parameters searching, inspired by the RegMix method. Our experiments across diverse models and datasets demonstrate that QuaDMix achieves an average performance improvement of 7.2% across multiple benchmarks. These results outperform the independent strategies for quality and diversity, highlighting the necessity and ability to balance data quality and diversity.

[Arxiv](https://arxiv.org/abs/2504.16511)