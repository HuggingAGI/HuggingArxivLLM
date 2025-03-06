# 优化开放领域问答：基于图的检索增强生成方法

发布时间：2025年03月04日

`RAG

理由：论文主要讨论了基于图的检索增强生成（RAG）系统，提出了一种创新的解决方案TREX，结合图和向量检索技术，以提升开放领域问答的性能。因此，它属于RAG分类。` `问答系统` `技术支持`

> Optimizing open-domain question answering with graph-based retrieval augmented generation

# 摘要

> 我们对基于图的检索增强生成（RAG）系统进行了全面基准测试，涵盖从基于事实到主题性的多种查询类型，以应对开放领域问答的复杂需求。传统RAG方法在处理多文档合成任务时表现有限。通过将知识结构化为图，我们能够更高效地检索具有深度语义的上下文，从而提升语言模型性能。我们深入研究了基于图的RAG方法，并提出了TREX——一种结合图和向量检索技术的创新且经济高效的解决方案。在四个多样化数据集上的测试结果表明，TREX在处理多种开放领域问答类型中表现出色，同时揭示了现有评估方法的局限性。在一项真实的技术支持案例研究中，我们展示了TREX如何在从异构数据源中高效合成信息方面超越传统基于向量的RAG方法。我们的研究结果强调了增强大型语言模型的高级检索和编排能力，推动基于图的可扩展AI解决方案发展的潜力。

> In this work, we benchmark various graph-based retrieval-augmented generation (RAG) systems across a broad spectrum of query types, including OLTP-style (fact-based) and OLAP-style (thematic) queries, to address the complex demands of open-domain question answering (QA). Traditional RAG methods often fall short in handling nuanced, multi-document synthesis tasks. By structuring knowledge as graphs, we can facilitate the retrieval of context that captures greater semantic depth and enhances language model operations. We explore graph-based RAG methodologies and introduce TREX, a novel, cost-effective alternative that combines graph-based and vector-based retrieval techniques. Our benchmarking across four diverse datasets highlights the strengths of different RAG methodologies, demonstrates TREX's ability to handle multiple open-domain QA types, and reveals the limitations of current evaluation methods.
  In a real-world technical support case study, we demonstrate how TREX solutions can surpass conventional vector-based RAG in efficiently synthesizing data from heterogeneous sources. Our findings underscore the potential of augmenting large language models with advanced retrieval and orchestration capabilities, advancing scalable, graph-based AI solutions.

[Arxiv](https://arxiv.org/abs/2503.02922)