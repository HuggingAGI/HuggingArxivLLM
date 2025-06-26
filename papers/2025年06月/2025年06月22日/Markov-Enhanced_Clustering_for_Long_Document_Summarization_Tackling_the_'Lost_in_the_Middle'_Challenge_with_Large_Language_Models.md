# # **马尔可夫增强聚类用于长文档摘要**：借助大型语言模型应对“迷失在中间”的挑战

发布时间：2025年06月22日

`LLM应用` `文本摘要`

> Markov-Enhanced Clustering for Long Document Summarization: Tackling the 'Lost in the Middle' Challenge with Large Language Models

# 摘要

> 随着信息来源的多样化和爆炸式增长，对有效自动文本摘要的需求日益迫切。自动文本摘要技术能够将文档压缩为更短且连贯的文本。摘要方法主要分为两类：抽取式摘要从原文中提取关键片段，而生成式摘要则通过重新表述内容生成连贯的摘要。大型语言模型推动了生成式摘要技术的发展，但它们需要大量计算资源，并且在处理长篇文档时容易出现“迷失在中间”的问题，即难以有效保留关键信息。为了解决这些问题，我们提出了一种结合抽取式和生成式技术的混合摘要方法。该方法将文档分割为更小的文本块，对它们的向量嵌入进行聚类，为每个聚类生成一个摘要片段，代表文档中的一个关键思想，最后通过依赖马尔可夫链图来选择思想的语义顺序，从而构建最终摘要。

> The rapid expansion of information from diverse sources has heightened the need for effective automatic text summarization, which condenses documents into shorter, coherent texts. Summarization methods generally fall into two categories: extractive, which selects key segments from the original text, and abstractive, which generates summaries by rephrasing the content coherently. Large language models have advanced the field of abstractive summarization, but they are resourceintensive and face significant challenges in retaining key information across lengthy documents, which we call being "lost in the middle". To address these issues, we propose a hybrid summarization approach that combines extractive and abstractive techniques. Our method splits the document into smaller text chunks, clusters their vector embeddings, generates a summary for each cluster that represents a key idea in the document, and constructs the final summary by relying on a Markov chain graph when selecting the semantic order of ideas.

[Arxiv](https://arxiv.org/abs/2506.18036)