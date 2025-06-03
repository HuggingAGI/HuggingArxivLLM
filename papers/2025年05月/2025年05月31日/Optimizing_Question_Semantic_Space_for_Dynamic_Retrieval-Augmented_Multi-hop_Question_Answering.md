# 优化问题语义空间，提升动态检索增强的多跳问答效果

发布时间：2025年05月31日

`RAG` `问答系统`

> Optimizing Question Semantic Space for Dynamic Retrieval-Augmented Multi-hop Question Answering

# 摘要

> 检索增强生成（RAG）通常被集成到大型语言模型（LLMs）中，以缓解幻觉问题和知识过时现象。然而，传统的单步检索-阅读方法在多跳问答任务中表现不足，面临检索语义不匹配和处理相互依赖子问题的高昂成本。本文提出了一种针对动态检索增强多跳问答的优化问题语义空间方法——Q-DREAM。Q-DREAM包含三个关键模块：（1）问题分解模块（QDM），将多跳问题分解为细粒度的子问题；（2）子问题依赖优化模块（SDOM），建模子问题之间的相互依赖关系以更好地理解问题；（3）动态篇章检索模块（DPRM），通过优化语义嵌入将子问题与相关篇章对齐。在多个基准测试中的实验结果表明，Q-DREAM显著优于现有的RAG方法，在域内和跨域设置下均达到最先进性能。值得注意的是，与近期的基线方法相比，Q-DREAM在保持高准确率的同时，还显著提高了检索效率。

> Retrieval-augmented generation (RAG) is usually integrated into large language models (LLMs) to mitigate hallucinations and knowledge obsolescence. Whereas,conventional one-step retrieve-and-read methods are insufficient for multi-hop question answering, facing challenges of retrieval semantic mismatching and the high cost in handling interdependent subquestions. In this paper, we propose Optimizing Question Semantic Space for Dynamic Retrieval-Augmented Multi-hop Question Answering (Q-DREAM). Q-DREAM consists of three key modules: (1) the Question Decomposition Module (QDM), which decomposes multi-hop questions into fine-grained subquestions; (2) the Subquestion Dependency Optimizer Module (SDOM), which models the interdependent relations of subquestions for better understanding; and (3) the Dynamic Passage Retrieval Module (DPRM), which aligns subquestions with relevant passages by optimizing the semantic embeddings. Experimental results across various benchmarks demonstrate that Q-DREAM significantly outperforms existing RAG methods, achieving state-of-the-art performance in both in-domain and out-of-domain settings. Notably, Q-DREAM also improves retrieval efficiency while maintaining high accuracy compared with recent baselines.

[Arxiv](https://arxiv.org/abs/2506.00491)