# HeteRAG：一种异质检索增强生成框架，采用解耦知识表示

发布时间：2025年04月12日

`RAG` `生成模型`

> HeteRAG: A Heterogeneous Retrieval-augmented Generation Framework with Decoupled Knowledge Representations

# 摘要

> 检索增强生成（RAG）方法通过巧妙结合检索到的知识块，能够显著提升大型语言模型（LLMs）的性能。然而，检索和生成步骤对知识块的要求却大相径庭：检索需要全面的信息以提高准确性，而生成则需要避免冗长的信息块，以免影响效率和效果。现有的RAG方法往往采用相同的表示方式处理两者，导致性能受限。针对这一问题，我们提出了一个异构的RAG框架（\myname），通过分别优化知识块在检索和生成中的表示方式，显著提升了LLMs的效果和效率。具体来说，我们采用短知识块来适应生成过程，并从多粒度视图利用上下文信息增强检索准确性。此外，我们还引入了一种自适应提示微调方法，以更好地支持异构的检索增强生成流程。通过大量实验验证，\myname相较于现有方法取得了显著的性能提升。

> Retrieval-augmented generation (RAG) methods can enhance the performance of LLMs by incorporating retrieved knowledge chunks into the generation process. In general, the retrieval and generation steps usually have different requirements for these knowledge chunks. The retrieval step benefits from comprehensive information to improve retrieval accuracy, whereas excessively long chunks may introduce redundant contextual information, thereby diminishing both the effectiveness and efficiency of the generation process. However, existing RAG methods typically employ identical representations of knowledge chunks for both retrieval and generation, resulting in suboptimal performance. In this paper, we propose a heterogeneous RAG framework (\myname) that decouples the representations of knowledge chunks for retrieval and generation, thereby enhancing the LLMs in both effectiveness and efficiency. Specifically, we utilize short chunks to represent knowledge to adapt the generation step and utilize the corresponding chunk with its contextual information from multi-granular views to enhance retrieval accuracy. We further introduce an adaptive prompt tuning method for the retrieval model to adapt the heterogeneous retrieval augmented generation process. Extensive experiments demonstrate that \myname achieves significant improvements compared to baselines.

[Arxiv](https://arxiv.org/abs/2504.10529)