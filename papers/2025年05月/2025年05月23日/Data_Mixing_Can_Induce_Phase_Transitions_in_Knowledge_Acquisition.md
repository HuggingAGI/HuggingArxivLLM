# # 数据混合可诱发知识获取中的相变效应

发布时间：2025年05月23日

`LLM理论` `人工智能` `机器学习`

> Data Mixing Can Induce Phase Transitions in Knowledge Acquisition

# 摘要

> 大型语言模型（LLMs）的训练通常依赖于数据混合：大部分数据来自网络爬取，而一小部分则经过精心筛选，来自包含密集领域知识的高质量来源。在本文中，我们发现，与仅使用知识密集型数据（arXiv:2404.05405）进行训练不同，从知识密集型数据集中获取知识的过程并不总是遵循平滑的缩放定律。相反，这一过程可能会随着数据混合比例和模型规模的变化而发生相变。通过在合成传记数据集与网络爬取数据混合的实验中，我们揭示了两个关键现象：(1) 当模型规模增加到临界值时，模型会突然从记住很少的传记内容转变为记住大部分传记内容；(2) 在临界混合比例以下，模型即使经过大量训练也几乎无法记住任何内容，但超过这一阈值后，它会迅速提升对传记内容的记忆能力。我们发现，这些相变源于容量分配现象：一个具有有限容量的模型必须像解决背包问题一样，通过最小化整体测试损失来分配资源。随着模型规模或混合比例的变化，跨数据集的最优分配可能会发生不连续的变化。我们通过信息论框架形式化了这一直觉，并揭示这些相变是可以预测的，其中临界混合比例与模型规模遵循幂律关系。我们的研究结果强调了一个重要现象：适合大型模型的良好混合配方可能并不适用于小型模型，反之亦然。

> Large Language Models (LLMs) are typically trained on data mixtures: most data come from web scrapes, while a small portion is curated from high-quality sources with dense domain-specific knowledge. In this paper, we show that when training LLMs on such data mixtures, knowledge acquisition from knowledge-dense datasets, unlike training exclusively on knowledge-dense data (arXiv:2404.05405), does not always follow a smooth scaling law but can exhibit phase transitions with respect to the mixing ratio and model size. Through controlled experiments on a synthetic biography dataset mixed with web-scraped data, we demonstrate that: (1) as we increase the model size to a critical value, the model suddenly transitions from memorizing very few to most of the biographies; (2) below a critical mixing ratio, the model memorizes almost nothing even with extensive training, but beyond this threshold, it rapidly memorizes more biographies. We attribute these phase transitions to a capacity allocation phenomenon: a model with bounded capacity must act like a knapsack problem solver to minimize the overall test loss, and the optimal allocation across datasets can change discontinuously as the model size or mixing ratio varies. We formalize this intuition in an information-theoretic framework and reveal that these phase transitions are predictable, with the critical mixing ratio following a power-law relationship with the model size. Our findings highlight a concrete case where a good mixing recipe for large models may not be optimal for small models, and vice versa.

[Arxiv](https://arxiv.org/abs/2505.18091)