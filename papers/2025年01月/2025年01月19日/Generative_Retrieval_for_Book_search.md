# 书籍搜索的生成式检索

发布时间：2025年01月19日

`RAG

理由：这篇论文提出了一个生成式书籍搜索框架（GBS），该框架通过数据增强和面向大纲的书籍编码来改进书籍搜索的效果。这种方法涉及到将语料库信息整合到单一模型中，并生成与查询相关的文档标识符，这与RAG（Retrieval-Augmented Generation）的概念相符。RAG通常涉及从外部知识源检索信息并将其整合到生成过程中，以提高生成内容的相关性和准确性。因此，这篇论文可以被归类为RAG。` `书籍搜索` `信息检索`

> Generative Retrieval for Book search

# 摘要

> 在书籍搜索中，查询应返回相关书籍信息。书籍包含元数据、大纲和正文等多面信息，其中大纲提供了章节间的层次结构。生成式检索（GR）是一种新范式，它将语料库信息整合到单一模型中，生成与查询相关的文档标识符。然而，将GR直接应用于书籍搜索面临挑战：模型需保留书籍的复杂信息，增加了对标注数据的需求；将书籍信息分割为独立片段可能导致层次信息丢失。为此，我们提出了生成式书籍搜索框架（GBS），包含数据增强和面向大纲的书籍编码两大组件。数据增强方面，GBS基于大纲和书籍内容构建多个查询-书籍对，并通过多样化伪查询模拟真实检索场景，包括促进覆盖的标识符增强和增强多样性的查询增强，分别提升模型的索引和检索能力。面向大纲的书籍编码则通过双层位置编码和保留注意力机制，改进长序列的上下文保持能力。在百度专有数据集上的实验表明，GBS在MRR@20指标上比当前最优的RIPOR方法提升了9.8%。

> In book search, relevant book information should be returned in response to a query. Books contain complex, multi-faceted information such as metadata, outlines, and main text, where the outline provides hierarchical information between chapters and sections. Generative retrieval (GR) is a new retrieval paradigm that consolidates corpus information into a single model to generate identifiers of documents that are relevant to a given query. How can GR be applied to book search? Directly applying GR to book search is a challenge due to the unique characteristics of book search: The model needs to retain the complex, multi-faceted information of the book, which increases the demand for labeled data. Splitting book information and treating it as a collection of separate segments for learning might result in a loss of hierarchical information. We propose an effective Generative retrieval framework for Book Search (GBS) that features two main components: data augmentation and outline-oriented book encoding. For data augmentation, GBS constructs multiple query-book pairs for training; it constructs multiple book identifiers based on the outline, various forms of book contents, and simulates real book retrieval scenarios with varied pseudo-queries. This includes coverage-promoting book identifier augmentation, allowing the model to learn to index effectively, and diversity-enhanced query augmentation, allowing the model to learn to retrieve effectively. Outline-oriented book encoding improves length extrapolation through bi-level positional encoding and retentive attention mechanisms to maintain context over long sequences. Experiments on a proprietary Baidu dataset demonstrate that GBS outperforms strong baselines, achieving a 9.8\% improvement in terms of MRR@20, over the state-of-the-art RIPOR method...

[Arxiv](https://arxiv.org/abs/2501.11034)