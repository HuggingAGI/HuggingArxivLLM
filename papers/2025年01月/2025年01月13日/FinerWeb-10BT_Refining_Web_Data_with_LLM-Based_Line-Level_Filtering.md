# FinerWeb-10BT: 基于LLM的行级过滤优化网络数据

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来提升训练数据的质量，具体提出了一种基于LLM的行级过滤方法，并通过实验验证了该方法在提升模型性能方面的有效性。这属于LLM在实际应用中的使用，因此归类为LLM应用。` `机器学习`

> FinerWeb-10BT: Refining Web Data with LLM-Based Line-Level Filtering

# 摘要

> 数据质量是训练大型语言模型（LLMs）的关键。传统启发式过滤器常会漏掉低质量文本或误删有价值内容。本文提出了一种基于LLM的行级过滤方法，旨在提升训练数据质量。我们使用GPT-4o mini对FineWeb中的20,000个文档进行行级标注，生成低质量行的描述性标签，并将其分为九大类。随后，我们训练了一个DeBERTa-v3分类器，将过滤扩展到FineWeb的10B令牌子集。通过在原始和过滤数据集上训练GPT-2模型，我们发现，使用过滤数据训练的模型在HellaSwag基准测试中表现更优，且即使数据量减少25\%，也能更快达到性能目标。这表明基于LLM的行级过滤能显著提升LLM的数据质量和训练效率。我们发布了标注数据集FinerWeb-10BT和代码库，以推动该领域的进一步研究。

> Data quality is crucial for training Large Language Models (LLMs). Traditional heuristic filters often miss low-quality text or mistakenly remove valuable content. In this paper, we introduce an LLM-based line-level filtering method to enhance training data quality. We use GPT-4o mini to label a 20,000-document sample from FineWeb at the line level, allowing the model to create descriptive labels for low-quality lines. These labels are grouped into nine main categories, and we train a DeBERTa-v3 classifier to scale the filtering to a 10B-token subset of FineWeb. To test the impact of our filtering, we train GPT-2 models on both the original and the filtered datasets. The results show that models trained on the filtered data achieve higher accuracy on the HellaSwag benchmark and reach their performance targets faster, even with up to 25\% less data. This demonstrates that LLM-based line-level filtering can significantly improve data quality and training efficiency for LLMs. We release our quality-annotated dataset, FinerWeb-10BT, and the codebase to support further work in this area.

[Arxiv](https://arxiv.org/abs/2501.07314)