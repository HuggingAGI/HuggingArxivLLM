# CAISSON：概念增强型自组织神经网络推理套装

发布时间：2024年12月03日

`RAG` `信息检索`

> CAISSON: Concept-Augmented Inference Suite of Self-Organizing Neural Networks

# 摘要

> 我们推出了 CAISSON，这是一种用于检索增强生成（RAG）的全新分层式方法，它把传统的单向量搜索转化成了多视图聚类框架。CAISSON 的核心在于利用双重自组织映射（SOM）创建文档空间的互补组织视图，每个视图通过特定嵌入捕捉文档关系的不同层面。第一个视图处理组合的文本和元数据嵌入，第二个视图则处理融入概念嵌入的元数据，实现了全面的多视图分析，既能捕捉到细粒度的语义关系，又能涵盖高级的概念模式。这种双视图方式通过整合来自不同组织视角的证据，实现了更精细的文档挖掘。为评估 CAISSON，我们开发了 SynFAQA，这是一个用于生成合成金融分析师笔记和问答对的框架，能系统地测试信息检索能力的各个方面。借鉴 HotPotQA 构建多步推理问题的办法，SynFAQA 生成受控测试案例，每个问题都与包含其真实答案的一组笔记相匹配，从简单的单实体查询发展到涉及多个实体和概念的复杂多跳检索任务。我们的实验结果显示，与基本和增强的 RAG 实现相比有显著提升，尤其在复杂的多实体查询方面，同时还保持了适用于交互式应用的实际响应时间。

> We present CAISSON, a novel hierarchical approach to Retrieval-Augmented Generation (RAG) that transforms traditional single-vector search into a multi-view clustering framework. At its core, CAISSON leverages dual Self-Organizing Maps (SOMs) to create complementary organizational views of the document space, where each view captures different aspects of document relationships through specialized embeddings. The first view processes combined text and metadata embeddings, while the second operates on metadata enriched with concept embeddings, enabling a comprehensive multi-view analysis that captures both fine-grained semantic relationships and high-level conceptual patterns. This dual-view approach enables more nuanced document discovery by combining evidence from different organizational perspectives. To evaluate CAISSON, we develop SynFAQA, a framework for generating synthetic financial analyst notes and question-answer pairs that systematically tests different aspects of information retrieval capabilities. Drawing on HotPotQA's methodology for constructing multi-step reasoning questions, SynFAQA generates controlled test cases where each question is paired with the set of notes containing its ground-truth answer, progressing from simple single-entity queries to complex multi-hop retrieval tasks involving multiple entities and concepts. Our experimental results demonstrate substantial improvements over both basic and enhanced RAG implementations, particularly for complex multi-entity queries, while maintaining practical response times suitable for interactive applications.

[Arxiv](https://arxiv.org/abs/2412.02835)