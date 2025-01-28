# CG-RAG: 基于引用图检索增强的LLMs实现研究问题解答

发布时间：2025年01月24日

`RAG

理由：这篇论文提出了一种新的框架——上下文图检索增强生成（CG-RAG），旨在通过融合稀疏与密集检索信号来提升检索效率并改善生成质量。该框架结合了引用图的上下文图表示、词汇-语义图检索（LeSeGR）以及上下文感知生成策略，显著提升了研究问题回答的检索准确性和生成质量。这些内容明显属于检索增强生成（RAG）领域的研究和应用。` `研究问题回答` `信息检索`

> CG-RAG: Research Question Answering by Citation Graph Retrieval-Augmented LLMs

# 摘要

> # 摘要
研究问题回答依赖于对科学文献的精准检索和上下文理解。然而，现有的检索增强生成（RAG）方法在复杂文档关系与精确信息检索之间往往难以兼顾。本文提出了一种新颖的框架——上下文图检索增强生成（CG-RAG），通过在图结构中融合稀疏与密集检索信号，提升检索效率，进而改善生成质量。首先，我们设计了引用图的上下文图表示，有效捕捉文档内外的显隐连接。接着，我们提出了词汇-语义图检索（LeSeGR），将稀疏与密集检索信号与图编码无缝结合，填补了引用图检索中词汇精确性与语义理解之间的鸿沟，并展示了其对现有图检索和混合检索方法的通用性。最后，我们引入了一种上下文感知生成策略，利用检索到的图结构信息，借助大型语言模型（LLMs）生成精准且富含上下文的回答。在多个领域的研究问题回答基准测试中，CG-RAG框架显著优于结合了多种先进检索方法的RAG方法，展现出卓越的检索准确性和生成质量。

> Research question answering requires accurate retrieval and contextual understanding of scientific literature. However, current Retrieval-Augmented Generation (RAG) methods often struggle to balance complex document relationships with precise information retrieval. In this paper, we introduce Contextualized Graph Retrieval-Augmented Generation (CG-RAG), a novel framework that integrates sparse and dense retrieval signals within graph structures to enhance retrieval efficiency and subsequently improve generation quality for research question answering. First, we propose a contextual graph representation for citation graphs, effectively capturing both explicit and implicit connections within and across documents. Next, we introduce Lexical-Semantic Graph Retrieval (LeSeGR), which seamlessly integrates sparse and dense retrieval signals with graph encoding. It bridges the gap between lexical precision and semantic understanding in citation graph retrieval, demonstrating generalizability to existing graph retrieval and hybrid retrieval methods. Finally, we present a context-aware generation strategy that utilizes the retrieved graph-structured information to generate precise and contextually enriched responses using large language models (LLMs). Extensive experiments on research question answering benchmarks across multiple domains demonstrate that our CG-RAG framework significantly outperforms RAG methods combined with various state-of-the-art retrieval approaches, delivering superior retrieval accuracy and generation quality.

[Arxiv](https://arxiv.org/abs/2501.15067)