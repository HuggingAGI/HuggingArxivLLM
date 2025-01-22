# 基于动态标签模式集成的开源LLMs自动标注

发布时间：2025年01月21日

`RAG

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）进行数据标注，并提出了一种称为检索增强分类（RAC）的方法。RAC通过检索和集成标签描述来提升标注任务的性能，这与检索增强生成（RAG）的概念密切相关。RAG通常涉及从外部知识源检索信息以增强模型的生成或分类能力。因此，这篇论文更适合归类为RAG。` `机器学习` `数据标注`

> Automatic Labelling with Open-source LLMs using Dynamic Label Schema Integration

# 摘要

> 在现实世界的机器学习项目中，获取高质量的标注数据仍然成本高昂。最近，大型语言模型（LLMs），尤其是GPT-4，在数据标注方面展现了极高的准确性。然而，隐私和成本问题限制了GPT-4的广泛应用。本研究探索了如何有效利用开源模型进行自动标注。我们发现，集成标签模式是一种有前景的技术，但简单地使用标签描述进行分类在高基数任务上表现不佳。为此，我们提出了检索增强分类（RAC），LLM通过相应的标签模式逐个推理标签，从最相关的标签开始迭代，直到选定一个标签。我们的方法动态集成标签描述，显著提升了标注任务的性能。此外，通过聚焦最有希望的标签，RAC能够在标签质量和覆盖率之间灵活权衡，这一特性被我们用于自动标注内部数据集。

> Acquiring labelled training data remains a costly task in real world machine learning projects to meet quantity and quality requirements. Recently Large Language Models (LLMs), notably GPT-4, have shown great promises in labelling data with high accuracy. However, privacy and cost concerns prevent the ubiquitous use of GPT-4. In this work, we explore effectively leveraging open-source models for automatic labelling. We identify integrating label schema as a promising technology but found that naively using the label description for classification leads to poor performance on high cardinality tasks. To address this, we propose Retrieval Augmented Classification (RAC) for which LLM performs inferences for one label at a time using corresponding label schema; we start with the most related label and iterates until a label is chosen by the LLM. We show that our method, which dynamically integrates label description, leads to performance improvements in labelling tasks. We further show that by focusing only on the most promising labels, RAC can trade off between label quality and coverage - a property we leverage to automatically label our internal datasets.

[Arxiv](https://arxiv.org/abs/2501.12332)