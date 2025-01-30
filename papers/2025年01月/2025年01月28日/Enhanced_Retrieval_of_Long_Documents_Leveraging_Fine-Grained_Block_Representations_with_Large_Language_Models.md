# 长文档检索增强：基于大型语言模型的细粒度块表示

发布时间：2025年01月28日

`RAG

**理由**：该论文提出了一种细粒度的方法来提升长文档相关性评分的准确性，这与检索增强生成（RAG）框架密切相关。RAG框架通常用于信息检索任务，而该论文的方法通过将长文档分割为多个块并与查询表示匹配，进一步优化了RAG框架的性能。因此，该论文应被分类为RAG。` `信息检索`

> Enhanced Retrieval of Long Documents: Leveraging Fine-Grained Block Representations with Large Language Models

# 摘要

> 近年来，大型语言模型（LLMs）在信息检索等多个领域展现了强大的能力。传统方法通常为每个查询、段落或文档生成单一嵌入，如检索增强生成（RAG）框架所示。然而，这种粗粒度表示难以捕捉文档级文本的复杂细节。为此，我们提出了一种细粒度方法，旨在提升长文档相关性评分的准确性。该方法将长文档分割为多个块，每个块通过LLM嵌入后与查询表示匹配。相关性分数通过加权求和聚合查询-块分数，生成查询与文档的综合评分。实验表明，该方法不仅优于标准表示方法，还显著降低了嵌入生成延迟。此外，通过优化成对损失函数，我们进一步提升了性能。

> In recent years, large language models (LLMs) have demonstrated exceptional power in various domains, including information retrieval. Most of the previous practices involve leveraging these models to create a single embedding for each query, each passage, or each document individually, a strategy exemplified and used by the Retrieval-Augmented Generation (RAG) framework. While this method has proven effective, we argue that it falls short in fully capturing the nuanced intricacies of document-level texts due to its reliance on a relatively coarse-grained representation. To address this limitation, we introduce a novel, fine-grained approach aimed at enhancing the accuracy of relevance scoring for long documents. Our methodology firstly segments a long document into blocks, each of which is embedded using an LLM, for matching with the query representation. When calculating the relevance score, we aggregate the query-block relevance scores through a weighted sum method, yielding a comprehensive score for the query with the entire document. Despite its apparent simplicity, our experimental findings reveal that this approach outperforms standard representation methods and achieves a significant reduction in embedding generation latency. Moreover, by carefully optimizing pairwise loss functions, superior performances have been achieved.

[Arxiv](https://arxiv.org/abs/2501.17039)