# BifrostRAG：连接双知识图谱，助力建筑安全领域的多跳问答

发布时间：2025年07月17日

`RAG` `建筑行业` `法律合规`

> BifrostRAG: Bridging Dual Knowledge Graphs for Multi-Hop Question Answering in Construction Safety

# 摘要

> 从安全法规中进行信息检索和问答是实现自动化建筑合规检查的关键，但这一过程面临着语言和结构复杂性带来的挑战。许多合规相关的问题需要跨相关条款进行信息综合，属于多跳推理问题。这对传统的检索增强生成（RAG）系统提出了挑战。为了解决这一问题，我们引入了BifrostRAG：一个双图集成的RAG系统，通过实体网络图显式建模语言关系，通过文档导航图显式建模文档结构。这种架构支持一种结合图遍历和基于向量的语义搜索的混合检索机制，使大型语言模型能够对文本的意义和结构进行推理。在多跳问题数据集上的评估显示，BifrostRAG实现了92.8%的精确率，85.5%的召回率，以及87.3%的F1分数。这些结果显著优于仅使用向量和仅使用图的RAG基线，而这些基线代表了当前的领先方法。错误分析进一步凸显了我们混合方法相对于单模态RAG的优势。这些发现确立了BifrostRAG作为LLM驱动合规检查的稳健知识引擎。其双图、混合检索机制为跨知识密集型工程领域导航复杂技术文档提供了一个可转移的蓝图。

> Information retrieval and question answering from safety regulations are essential for automated construction compliance checking but are hindered by the linguistic and structural complexity of regulatory text. Many compliance-related queries are multi-hop, requiring synthesis of information across interlinked clauses. This poses a challenge for traditional retrieval-augmented generation (RAG) systems. To overcome this, we introduce BifrostRAG: a dual-graph RAG-integrated system that explicitly models both linguistic relationships (via an Entity Network Graph) and document structure (via a Document Navigator Graph). This architecture powers a hybrid retrieval mechanism that combines graph traversal with vector-based semantic search, enabling large language models to reason over both the meaning and the structure of the text. Evaluation on a multi-hop question dataset shows that BifrostRAG achieves 92.8 percent precision, 85.5 percent recall, and an F1 score of 87.3 percent. These results significantly outperform vector-only and graph-only RAG baselines that represent current leading approaches. Error analysis further highlights the comparative advantages of our hybrid method over single-modality RAGs. These findings establish BifrostRAG as a robust knowledge engine for LLM-driven compliance checking. Its dual-graph, hybrid retrieval mechanism offers a transferable blueprint for navigating complex technical documents across knowledge-intensive engineering domains.

[Arxiv](https://arxiv.org/abs/2507.13625)