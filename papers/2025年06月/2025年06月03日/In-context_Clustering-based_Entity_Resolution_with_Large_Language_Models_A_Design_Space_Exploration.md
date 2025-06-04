# 基于上下文聚类的实体解析：大型语言模型的设计空间探索

发布时间：2025年06月03日

`LLM应用` `数据管理` `数据集成`

> In-context Clustering-based Entity Resolution with Large Language Models: A Design Space Exploration

# 摘要

> 实体解析（ER）是一项提升数据质量的基础任务，旨在识别并链接指向同一真实世界实体的记录。传统ER方法通常依赖成对比较，这在处理大规模数据集时成本高昂。最近，大型语言模型（LLMs）在ER任务中展现出巨大潜力。然而，现有方法多专注于成对匹配，忽视了LLMs在高效、可扩展的直接聚类方面的潜力。

本文提出了一种用于ER的新型in-context聚类方法，通过直接利用LLMs进行记录聚类，显著降低了时间和金钱成本。我们系统性地探索了in-context聚类的设计空间，深入分析了记录集合大小、多样性、变体以及顺序等因素对聚类性能的影响。

基于这些研究，我们开发了LLM-CER（基于LLM的聚类驱动ER），在减少LLM API调用的同时实现了高质量的ER结果。该方法成功解决了高效聚类合并和LLM幻觉等关键挑战，为ER提供了一种可扩展且有效的解决方案。

在九个真实世界数据集上的广泛实验表明，LLM-CER显著提升了结果质量：准确率提高了150%，F值增加了10%，同时将API调用减少了5倍，而成本与最经济的基线方法相当。


> Entity Resolution (ER) is a fundamental data quality improvement task that identifies and links records referring to the same real-world entity. Traditional ER approaches often rely on pairwise comparisons, which can be costly in terms of time and monetary resources, especially with large datasets. Recently, Large Language Models (LLMs) have shown promising results in ER tasks. However, existing methods typically focus on pairwise matching, missing the potential of LLMs to perform clustering directly in a more cost-effective and scalable manner. In this paper, we propose a novel in-context clustering approach for ER, where LLMs are used to cluster records directly, reducing both time complexity and monetary costs. We systematically investigate the design space for in-context clustering, analyzing the impact of factors such as set size, diversity, variation, and ordering of records on clustering performance. Based on these insights, we develop LLM-CER (LLM-powered Clustering-based ER), which achieves high-quality ER results while minimizing LLM API calls. Our approach addresses key challenges, including efficient cluster merging and LLM hallucination, providing a scalable and effective solution for ER. Extensive experiments on nine real-world datasets demonstrate that our method significantly improves result quality, achieving up to 150% higher accuracy, 10% increase in the F-measure, and reducing API calls by up to 5 times, while maintaining comparable monetary cost to the most cost-effective baseline.

[Arxiv](https://arxiv.org/abs/2506.02509)