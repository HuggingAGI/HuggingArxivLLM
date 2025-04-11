# FG-RAG: 利用上下文感知的细粒度图 RAG 提升基于查询的摘要效果

发布时间：2025年03月13日

`RAG` `信息检索` `问答系统`

> FG-RAG: Enhancing Query-Focused Summarization with Context-Aware Fine-Grained Graph RAG

# 摘要

> 检索增强生成（RAG）让大型语言模型通过整合外部知识生成更精准相关的回答。在查询聚焦式摘要任务（QFS）中，基于GraphRAG的方法显著提升了生成回答的全面性和多样性。然而，现有GraphRAG方法主要关注粗粒度信息摘要，且缺乏对具体查询的感知，导致检索内容缺乏足够上下文信息以生成全面回答。为解决现有RAG系统的不足，我们提出上下文感知细粒度图RAG（FG-RAG），以提升QFS任务性能。FG-RAG通过上下文感知实体扩展扩大图检索中实体覆盖范围，为检索内容提供充足上下文信息。同时，FG-RAG利用查询级别细粒度摘要在生成回答时融入细粒度细节，增强生成摘要的查询感知能力。我们的评估表明，FG-RAG在处理QFS任务时，全面性、多样性和赋能能力的多项指标均优于其他RAG系统。代码实现可访问https://github.com/BuptWululu/FG-RAG。

> Retrieval-Augmented Generation (RAG) enables large language models to provide more precise and pertinent responses by incorporating external knowledge. In the Query-Focused Summarization (QFS) task, GraphRAG-based approaches have notably enhanced the comprehensiveness and diversity of generated responses. However, existing GraphRAG-based approaches predominantly focus on coarse-grained information summarization without being aware of the specific query, and the retrieved content lacks sufficient contextual information to generate comprehensive responses. To address the deficiencies of current RAG systems, we propose Context-Aware Fine-Grained Graph RAG (FG-RAG) to enhance the performance of the QFS task. FG-RAG employs Context-Aware Entity Expansion in graph retrieval to expand the coverage of retrieved entities in the graph, thus providing enough contextual information for the retrieved content. Furthermore, FG-RAG utilizes Query-Level Fine-Grained Summarization to incorporate fine-grained details during response generation, enhancing query awareness for the generated summarization. Our evaluation demonstrates that FG-RAG outperforms other RAG systems in multiple metrics of comprehensiveness, diversity, and empowerment when handling the QFS task. Our implementation is available at https://github.com/BuptWululu/FG-RAG.

[Arxiv](https://arxiv.org/abs/2504.07103)