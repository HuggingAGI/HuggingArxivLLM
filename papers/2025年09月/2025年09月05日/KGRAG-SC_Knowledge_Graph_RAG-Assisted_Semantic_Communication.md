# KGRAG-SC：知识图谱RAG辅助语义通信

发布时间：2025年09月05日

`RAG` `基础理论`

> KGRAG-SC: Knowledge Graph RAG-Assisted Semantic Communication

# 摘要

> 当前主流的语义通信（SC）方案大多依赖端到端深度学习框架，但这类框架不仅可解释性差，在噪声环境下也难以实现稳健的语义选择与重建。为此，本文提出KGRAG-SC——一种基于检索增强生成原理的知识图谱辅助SC框架。KGRAG-SC引入多维知识图谱，借助社区引导的实体链接与GraphRAG辅助处理，可高效完成语义提取。发射机构建能捕获核心语义关系的最小连通子图，仅传输紧凑的实体索引，而非完整文本或语义三元组。该框架还采用重要性感知自适应传输策略，基于结构中心性指标提供不等错误保护，在信道条件恶劣时优先保障关键语义元素。接收机端则利用共享知识图谱作为结构化上下文，通过大型语言模型进行知识驱动的文本重建，即便部分信息丢失仍能实现稳健的语义恢复。实验结果显示，KGRAG-SC在低信噪比（SNR）环境下语义保真度更优，且相比传统通信方法大幅降低了传输开销，充分证明了将结构化知识表示与生成式语言模型集成应用于SC系统的有效性。

> The state-of-the-art semantic communication (SC) schemes typically rely on end-to-end deep learning frameworks that lack interpretability and struggle with robust semantic selection and reconstruction under noisy conditions. To address this issue, this paper presents KGRAG-SC, a knowledge graph-assisted SC framework that leverages retrieval-augmented generation principles. KGRAG-SC employs a multi-dimensional knowledge graph, enabling efficient semantic extraction through community-guided entity linking and GraphRAG-assisted processing. The transmitter constructs minimal connected subgraphs that capture essential semantic relationships and transmits only compact entity indices rather than full text or semantic triples. An importance-aware adaptive transmission strategy provides unequal error protection based on structural centrality metrics, prioritizing critical semantic elements under adverse channel conditions. At the receiver, large language models perform knowledge-driven text reconstruction using the shared knowledge graph as structured context, ensuring robust semantic recovery even with partial information loss. Experimental results demonstrate that KGRAG-SC achieves superior semantic fidelity in low Signal-to-Noise Ratio (SNR) conditions while significantly reducing transmission overhead compared to traditional communication methods, highlighting the effectiveness of integrating structured knowledge representation with generative language models for SC systems.

[Arxiv](https://arxiv.org/abs/2509.04801)