# HOPE：文本分块的跨领域自动化评估

发布时间：2025年05月04日

`RAG` `信息检索`

> A New HOPE: Domain-agnostic Automatic Evaluation of Text Chunking

# 摘要

> 文档分块对检索增强生成（RAG）的影响至关重要，因为它决定了源材料在索引前如何被分割。尽管已知大型语言模型（LLMs）对检索数据的布局和结构敏感，但目前尚无分析不同分块方法影响的框架。本文中，我们提出了一种全新的方法，从三个层次定义分块过程的本质特性：内在段落属性、外在段落属性以及段落-文档连贯性。我们引入了HOPE（整体段落评估），这是一种领域无关的自动评估指标，能够量化并汇总这些特性。我们在七个领域的实证评估表明，HOPE指标与各种RAG性能指标之间存在显著相关性（p > 0.13），揭示了段落外在和内在属性重要性的差异。段落之间的语义独立性对系统性能至关重要，可使事实正确性提升高达56.2%，答案正确性提升21.1%。相反，传统上关于保持段落内概念统一的假设显示了最小的影响。这些发现为优化分块策略提供了可操作的见解，从而改进RAG系统设计，生成更事实正确的响应。

> Document chunking fundamentally impacts Retrieval-Augmented Generation (RAG) by determining how source materials are segmented before indexing. Despite evidence that Large Language Models (LLMs) are sensitive to the layout and structure of retrieved data, there is currently no framework to analyze the impact of different chunking methods. In this paper, we introduce a novel methodology that defines essential characteristics of the chunking process at three levels: intrinsic passage properties, extrinsic passage properties, and passages-document coherence. We propose HOPE (Holistic Passage Evaluation), a domain-agnostic, automatic evaluation metric that quantifies and aggregates these characteristics. Our empirical evaluations across seven domains demonstrate that the HOPE metric correlates significantly (p > 0.13) with various RAG performance indicators, revealing contrasts between the importance of extrinsic and intrinsic properties of passages. Semantic independence between passages proves essential for system performance with a performance gain of up to 56.2% in factual correctness and 21.1% in answer correctness. On the contrary, traditional assumptions about maintaining concept unity within passages show minimal impact. These findings provide actionable insights for optimizing chunking strategies, thus improving RAG system design to produce more factually correct responses.

[Arxiv](https://arxiv.org/abs/2505.02171)