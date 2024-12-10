# 多字段自适应检索

发布时间：2024年10月25日

`LLM应用` `文档检索` `结构化数据`

> Multi-Field Adaptive Retrieval

# 摘要

> 对于像搜索和检索增强生成这类任务的文档检索，通常会涉及非结构化的数据集：即每个文档都是没有明确内部结构的自由格式文本。不过，文档也可以是结构化的，包含诸如文章标题、消息正文或者 HTML 标题之类的字段。为了弥补这一差距，我们推出了多字段自适应检索（MFAR），这是一个灵活的框架，能够适配结构化数据上的任意数量和任意类型的文档索引。我们的框架包含两个主要步骤：（1）把现有文档分解成字段，每个字段通过密集和词汇方法分别独立索引；（2）学习一个模型，该模型依据文档查询来适应性地预测字段的重要性，从而能够实时对最有可能的字段进行加权。我们发现，我们的方法能够在不同字段类型上优化使用密集表示和词汇表示，在文档排名上明显优于许多现有的检索器，并在多字段结构化数据方面达到了顶尖水平。

> Document retrieval for tasks such as search and retrieval-augmented generation typically involves datasets that are unstructured: free-form text without explicit internal structure in each document. However, documents can have a structured form, consisting of fields such as an article title, message body, or HTML header. To address this gap, we introduce Multi-Field Adaptive Retrieval (MFAR), a flexible framework that accommodates any number of and any type of document indices on structured data. Our framework consists of two main steps: (1) the decomposition of an existing document into fields, each indexed independently through dense and lexical methods, and (2) learning a model which adaptively predicts the importance of a field by conditioning on the document query, allowing on-the-fly weighting of the most likely field(s). We find that our approach allows for the optimized use of dense versus lexical representations across field types, significantly improves in document ranking over a number of existing retrievers, and achieves state-of-the-art performance for multi-field structured data.

[Arxiv](https://arxiv.org/abs/2410.20056)