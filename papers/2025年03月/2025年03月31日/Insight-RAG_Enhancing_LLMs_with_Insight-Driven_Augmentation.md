# Insight-RAG: 基于洞察力的增强提升大型语言模型（LLMs）

发布时间：2025年03月31日

`RAG` `问答系统` `信息检索`

> Insight-RAG: Enhancing LLMs with Insight-Driven Augmentation

# 摘要

> 检索增强生成（RAG）框架在提升大型语言模型（LLMs）性能方面潜力巨大。然而，传统RAG方法仅基于表面相关性检索文档，存在三大问题：可能忽略文档中深埋的关键信息，错过跨多源的相关见解，且难以胜任问答以外的任务。本文提出全新框架——Insight-RAG，专为解决这些问题而设计。

在Insight-RAG的初始阶段，我们不使用传统检索方法，而是借助LLM分析输入查询和任务，提取潜在信息需求。随后，我们查询一个经过文档数据库训练的专用LLM，以挖掘直接针对这些见解的内容。最后，通过结合原始查询与检索到的见解，采用一个最终的LLM生成语境丰富且准确的响应。

基于两个科学论文数据集，我们创建了针对每个问题的评估基准，并将Insight-RAG与传统RAG管道进行了对比评估。实验结果表明，Insight-RAG管道成功解决了这些挑战，在大多数情况下显著超越现有方法。这些发现表明，将基于见解的检索整合到RAG框架中不仅提升了性能，还扩展了其在问答以外任务中的适用性。

> Retrieval Augmented Generation (RAG) frameworks have shown significant promise in leveraging external knowledge to enhance the performance of large language models (LLMs). However, conventional RAG methods often retrieve documents based solely on surface-level relevance, leading to many issues: they may overlook deeply buried information within individual documents, miss relevant insights spanning multiple sources, and are not well-suited for tasks beyond traditional question answering. In this paper, we propose Insight-RAG, a novel framework designed to address these issues. In the initial stage of Insight-RAG, instead of using traditional retrieval methods, we employ an LLM to analyze the input query and task, extracting the underlying informational requirements. In the subsequent stage, a specialized LLM -- trained on the document database -- is queried to mine content that directly addresses these identified insights. Finally, by integrating the original query with the retrieved insights, similar to conventional RAG approaches, we employ a final LLM to generate a contextually enriched and accurate response. Using two scientific paper datasets, we created evaluation benchmarks targeting each of the mentioned issues and assessed Insight-RAG against traditional RAG pipeline. Our results demonstrate that the Insight-RAG pipeline successfully addresses these challenges, outperforming existing methods by a significant margin in most cases. These findings suggest that integrating insight-driven retrieval within the RAG framework not only enhances performance but also broadens the applicability of RAG to tasks beyond conventional question answering.

[Arxiv](https://arxiv.org/abs/2504.00187)