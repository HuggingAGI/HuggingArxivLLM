# 性能导向的多向量检索查询分解器：POQD

发布时间：2025年05月25日

`RAG

摘要中的论文专注于优化检索增强生成（RAG）系统中的查询分解过程，提出了一种新的框架POQD，以提升RAG系统的性能。因此，这篇论文属于RAG类别。` `信息检索` `问答系统`

> POQD: Performance-Oriented Query Decomposer for Multi-vector retrieval

# 摘要

> 尽管多向量检索（MVR）在信息检索领域已达到当前最佳水平，但其性能高度依赖于如何将查询分解为更小的片段，如短语或标记。然而，针对MVR性能优化查询分解的过程并非端到端可微分。更糟糕的是，同时解决这个问题并训练下游基于检索的系统（如RAG系统）可能会非常低效。为克服这些挑战，我们提出了一种全新的MVR查询分解框架——性能导向查询分解器（POQD）。POQD利用一个大型语言模型（LLM）进行查询分解，并借助基于LLM的优化器搜索最优提示。我们还提出了一种端到端训练算法，通过交替优化查询分解的提示和下游模型来提升性能。如我们的理论分析所示，该算法能够在合理的训练成本下实现更优的MVR性能。POQD可以无缝集成到任意基于检索的系统中，例如检索增强生成（RAG）系统。在具有代表性的基于RAG的问答任务上的广泛实证研究表明，POQD在检索性能和端到端问答准确性方面均优于现有的查询分解策略。POQD已在GitHub上开源，地址为https://github.com/PKU-SDS-lab/POQD-ICML25。

> Although Multi-Vector Retrieval (MVR) has achieved the state of the art on many information retrieval (IR) tasks, its performance highly depends on how to decompose queries into smaller pieces, say phrases or tokens. However, optimizing query decomposition for MVR performance is not end-to-end differentiable. Even worse, jointly solving this problem and training the downstream retrieval-based systems, say RAG systems could be highly inefficient. To overcome these challenges, we propose Performance-Oriented Query Decomposer (POQD), a novel query decomposition framework for MVR. POQD leverages one LLM for query decomposition and searches the optimal prompt with an LLM-based optimizer. We further propose an end-to-end training algorithm to alternatively optimize the prompt for query decomposition and the downstream models. This algorithm can achieve superior MVR performance at a reasonable training cost as our theoretical analysis suggests. POQD can be integrated seamlessly into arbitrary retrieval-based systems such as Retrieval-Augmented Generation (RAG) systems. Extensive empirical studies on representative RAG-based QA tasks show that POQD outperforms existing query decomposition strategies in both retrieval performance and end-to-end QA accuracy. POQD is available at https://github.com/PKU-SDS-lab/POQD-ICML25.

[Arxiv](https://arxiv.org/abs/2505.19189)