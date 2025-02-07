# 基于检索增强的大型语言模型实现可扩展的表格数据上下文学习

发布时间：2025年02月05日

`RAG

理由：这篇论文提出了一种针对表格数据定制的检索增强型LLM方法，结合了定制检索模块和检索引导的指令调优。这种方法属于检索增强生成（Retrieval-Augmented Generation, RAG）的范畴，因为它通过检索模块来增强LLM的能力，使其能够更高效地利用大规模数据集。因此，这篇论文应被分类为RAG。` `数据科学` `机器学习`

> Scalable In-Context Learning on Tabular Data via Retrieval-Augmented Large Language Models

# 摘要

> 近期研究表明，大型语言模型（LLMs）经过表格数据的后训练定制后，能够掌握通用的表格上下文学习（TabICL）能力，并能在不同数据模式和任务领域间有效迁移。然而，现有基于LLM的TabICL方法受限于LLM的序列长度，仅适用于少样本场景，因为纯文本表示的表格实例会消耗大量token。为突破这一限制，实现任意数据规模的可扩展TabICL，我们提出了针对表格数据定制的检索增强型LLM。该方法结合了定制检索模块和检索引导的指令调优，使LLM能够高效利用大规模数据集，在69个知名数据集上显著提升性能，并展现出良好的扩展性。与顶尖表格模型的广泛对比显示，尽管基于LLM的TabICL在整体性能上仍不及精心调优的数值模型，但它在有限上下文中展现了强大的算法能力，增强了集成多样性，并在特定数据集上表现优异。这些独特优势凸显了语言作为可扩展表格数据学习的通用接口的巨大潜力。

> Recent studies have shown that large language models (LLMs), when customized with post-training on tabular data, can acquire general tabular in-context learning (TabICL) capabilities. These models are able to transfer effectively across diverse data schemas and different task domains. However, existing LLM-based TabICL approaches are constrained to few-shot scenarios due to the sequence length limitations of LLMs, as tabular instances represented in plain text consume substantial tokens. To address this limitation and enable scalable TabICL for any data size, we propose retrieval-augmented LLMs tailored to tabular data. Our approach incorporates a customized retrieval module, combined with retrieval-guided instruction-tuning for LLMs. This enables LLMs to effectively leverage larger datasets, achieving significantly improved performance across 69 widely recognized datasets and demonstrating promising scaling behavior. Extensive comparisons with state-of-the-art tabular models reveal that, while LLM-based TabICL still lags behind well-tuned numeric models in overall performance, it uncovers powerful algorithms under limited contexts, enhances ensemble diversity, and excels on specific datasets. These unique properties underscore the potential of language as a universal and accessible interface for scalable tabular data learning.

[Arxiv](https://arxiv.org/abs/2502.03147)