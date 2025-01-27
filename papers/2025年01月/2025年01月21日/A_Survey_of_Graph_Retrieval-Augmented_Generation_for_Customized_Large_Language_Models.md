# # 图检索增强生成在定制化大型语言模型中的应用综述

发布时间：2025年01月21日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在专业领域中的应用，特别是基于图的检索增强生成（GraphRAG）这一新范式。论文详细分析了GraphRAG如何通过图结构知识表示、高效图检索技术和结构感知知识集成算法来解决传统RAG系统的挑战。因此，这篇论文的核心内容与RAG密切相关，应归类为RAG。` `知识图谱` `专业领域`

> A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models

# 摘要

> # 摘要
大型语言模型（LLMs）在众多任务中展现了卓越能力，但在专业领域的应用仍面临挑战，主要因为需要深厚的专业知识。检索增强生成（RAG）通过无缝集成外部知识库，使LLMs能在推理时实时访问领域专业知识，为专业领域定制LLMs提供了可能。然而，传统基于平面文本检索的RAG系统面临三大挑战：专业环境中的复杂查询理解、跨分布式来源的知识集成困难以及大规模应用中的系统效率瓶颈。本调查系统分析了基于图的检索增强生成（GraphRAG），这一新范式革新了特定领域LLM应用。GraphRAG通过三大创新解决传统RAG的局限：图结构知识表示明确捕捉实体关系和领域层次结构，高效图检索技术支持多跳推理的上下文保留知识检索，结构感知知识集成算法利用检索知识实现准确且逻辑一致的LLM生成。我们系统分析了GraphRAG的技术基础，考察了其在各专业领域的当前实现，识别了关键技术挑战和有前景的研究方向。所有相关资源，包括研究论文、开源数据和项目，均收集在	extcolor{blue}{url{https://github.com/DEEP-PolyU/Awesome-GraphRAG}}中供社区使用。

> Large language models (LLMs) have demonstrated remarkable capabilities in a wide range of tasks, yet their application to specialized domains remains challenging due to the need for deep expertise. Retrieval-augmented generation (RAG) has emerged as a promising solution to customize LLMs for professional fields by seamlessly integrating external knowledge bases, enabling real-time access to domain-specific expertise during inference. Despite its potential, traditional RAG systems, based on flat text retrieval, face three critical challenges: (i) complex query understanding in professional contexts, (ii) difficulties in knowledge integration across distributed sources, and (iii) system efficiency bottlenecks at scale. This survey presents a systematic analysis of Graph-based Retrieval-Augmented Generation (GraphRAG), a new paradigm that revolutionizes domain-specific LLM applications. GraphRAG addresses traditional RAG limitations through three key innovations: (i) graph-structured knowledge representation that explicitly captures entity relationships and domain hierarchies, (ii) efficient graph-based retrieval techniques that enable context-preserving knowledge retrieval with multihop reasoning ability, and (iii) structure-aware knowledge integration algorithms that leverage retrieved knowledge for accurate and logical coherent generation of LLMs. In this survey, we systematically analyze the technical foundations of GraphRAG and examine current implementations across various professional domains, identifying key technical challenges and promising research directions. All the related resources of GraphRAG, including research papers, open-source data, and projects, are collected for the community in \textcolor{blue}{url{https://github.com/DEEP-PolyU/Awesome-GraphRAG}}.

[Arxiv](https://arxiv.org/abs/2501.13958)