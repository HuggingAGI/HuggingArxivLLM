# 并非每个特征都值得关注：基于图的依赖关系学习，借助语言模型实现表格数据生成

发布时间：2025年07月24日

`LLM应用` `表格数据` `大型语言模型`

> Not All Features Deserve Attention: Graph-Guided Dependency Learning for Tabular Data Generation with Language Models

# 摘要

> 大型语言模型（LLMs）在生成表格数据方面展现出强大的潜力，尤其是在建模文本化的特征-值对时表现突出。然而，表格数据的稀疏特征依赖关系导致了LLMs自注意力机制的局限性：其注意力机制会平均分配关注所有特征对，从而削弱了对关键关系的聚焦，尤其在复杂依赖或语义模糊的数据中表现明显。为解决这一问题，我们提出了GraDe（基于图的依赖关系学习）方法，通过将稀疏依赖图显式融入LLMs的注意力机制，优化特征交互的优先级。实验结果显示，GraDe在复杂数据集上的表现超越现有方法12%，同时在合成数据质量上与前沿技术持平。作为一种侵入性极小却有效的解决方案，GraDe为基于LLMs的结构感知表格建模提供了实用的路径。

> Large Language Models (LLMs) have shown strong potential for tabular data generation by modeling textualized feature-value pairs. However, tabular data inherently exhibits sparse feature-level dependencies, where many feature interactions are structurally insignificant. This creates a fundamental mismatch as LLMs' self-attention mechanism inevitably distributes focus across all pairs, diluting attention on critical relationships, particularly in datasets with complex dependencies or semantically ambiguous features. To address this limitation, we propose GraDe (Graph-Guided Dependency Learning), a novel method that explicitly integrates sparse dependency graphs into LLMs' attention mechanism. GraDe employs a lightweight dynamic graph learning module guided by externally extracted functional dependencies, prioritizing key feature interactions while suppressing irrelevant ones. Our experiments across diverse real-world datasets demonstrate that GraDe outperforms existing LLM-based approaches by up to 12% on complex datasets while achieving competitive results with state-of-the-art approaches in synthetic data quality. Our method is minimally intrusive yet effective, offering a practical solution for structure-aware tabular data modeling with LLMs.

[Arxiv](https://arxiv.org/abs/2507.18504)