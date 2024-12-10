# KG-Retriever：为检索增强型大型语言模型打造的高效知识索引

发布时间：2024年12月07日

`RAG` `知识图谱` `问答系统`

> KG-Retriever: Efficient Knowledge Indexing for Retrieval-Augmented Large Language Models

# 摘要

> 在具有检索增强生成的大型语言模型中，复杂的检索任务（如多跳问答）是个关键挑战，这要求模型遍历多个文档，并依据零散信息生成全面回答。为应对此挑战，我们推出了一种新颖的基于知识图谱的 RAG 框架，带有分层知识检索器，名为 KG-Retriever。KG-Retriever 的检索索引构建于分层索引图上，包含知识图谱层和协作文档层。充分利用图结构的关联特性，加强了文档内和文档间的连通性，从根本上减轻了信息碎片化问题，同时提升了 LLM 跨文档检索的效率。凭借来自相邻文档的粗粒度协作信息和知识图谱的简洁信息，KG-Retriever 在五个公共 QA 数据集上有显著提升，展现了我们所提 RAG 框架的有效性与高效性。

> Large language models with retrieval-augmented generation encounter a pivotal challenge in intricate retrieval tasks, e.g., multi-hop question answering, which requires the model to navigate across multiple documents and generate comprehensive responses based on fragmented information. To tackle this challenge, we introduce a novel Knowledge Graph-based RAG framework with a hierarchical knowledge retriever, termed KG-Retriever. The retrieval indexing in KG-Retriever is constructed on a hierarchical index graph that consists of a knowledge graph layer and a collaborative document layer. The associative nature of graph structures is fully utilized to strengthen intra-document and inter-document connectivity, thereby fundamentally alleviating the information fragmentation problem and meanwhile improving the retrieval efficiency in cross-document retrieval of LLMs. With the coarse-grained collaborative information from neighboring documents and concise information from the knowledge graph, KG-Retriever achieves marked improvements on five public QA datasets, showing the effectiveness and efficiency of our proposed RAG framework.

[Arxiv](https://arxiv.org/abs/2412.05547)