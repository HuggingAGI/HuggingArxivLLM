# 伪知识图谱——元路径引导的检索与图内文本，赋能 RAG 驱动的 LLM

发布时间：2025年02月28日

`RAG` `知识图谱` `信息检索`

> Pseudo-Knowledge Graph: Meta-Path Guided Retrieval and In-Graph Text for RAG-Equipped LLM

# 摘要

> 大型语言模型（LLMs）的出现彻底改变了自然语言处理领域。然而，这些模型在从海量数据集中检索精确信息时仍面临挑战。为了结合LLMs与外部信息检索系统以提高响应的准确性和上下文关联性，检索增强生成（RAG）应运而生。尽管有所改进，但RAG在处理大规模、低信息密度的数据库时仍难以实现全面检索，并且缺乏关联意识，导致答案碎片化。

为了解决这些问题，本文提出了一种名为伪知识图谱（PKG）的框架，通过整合元路径检索、图内文本与向量检索到LLMs中，旨在克服现有局限。PKG通过保留自然语言文本并运用多种检索技术，提供了更丰富的知识表示，从而提升了信息检索的准确性。借助Open Compass和MultiHop-RAG基准的广泛评估，该框架在处理海量数据和复杂关系方面展现出显著的有效性。

> The advent of Large Language Models (LLMs) has revolutionized natural language processing. However, these models face challenges in retrieving precise information from vast datasets. Retrieval-Augmented Generation (RAG) was developed to combining LLMs with external information retrieval systems to enhance the accuracy and context of responses. Despite improvements, RAG still struggles with comprehensive retrieval in high-volume, low-information-density databases and lacks relational awareness, leading to fragmented answers.
  To address this, this paper introduces the Pseudo-Knowledge Graph (PKG) framework, designed to overcome these limitations by integrating Meta-path Retrieval, In-graph Text and Vector Retrieval into LLMs. By preserving natural language text and leveraging various retrieval techniques, the PKG offers a richer knowledge representation and improves accuracy in information retrieval. Extensive evaluations using Open Compass and MultiHop-RAG benchmarks demonstrate the framework's effectiveness in managing large volumes of data and complex relationships.

[Arxiv](https://arxiv.org/abs/2503.00309)