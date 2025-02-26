# LevelRAG：基于多跳逻辑规划的检索增强生成优化方法，实现重写增强的搜索器。

发布时间：2025年02月25日

`RAG` `信息检索` `问答系统`

> LevelRAG: Enhancing Retrieval-Augmented Generation with Multi-hop Logic Planning over Rewriting Augmented Searchers

# 摘要

> 检索增强生成（RAG）是缓解大型语言模型幻觉现象、整合外部知识到模型输出的关键方法。目前的RAG方法大多通过改写查询来明确用户意图并管理多跳逻辑，同时借助混合检索扩大搜索范围。然而，查询改写与密集检索器的强耦合限制了其在混合检索中的应用，成为RAG性能提升的瓶颈。为突破这一限制，我们提出了一种全新的高层次搜索器，能够将复杂查询分解为原子查询，且无需依赖特定检索器的优化。同时，我们开发了一种基于Lucene语法的稀疏搜索器，旨在充分利用稀疏检索器在精准关键词检索方面的优势，从而提升整体检索准确性。这些组件与网页和密集搜索器协同工作，共同构成了我们的方法——	extbf{LevelRAG}。在LevelRAG框架下，高层次搜索器负责统筹检索逻辑，而低层次搜索器（稀疏、网页和密集）则对查询进行优化，以实现最佳检索效果。这种设计不仅显著提升了检索的完整性和准确性，还有效解决了现有查询改写技术在混合检索场景中的局限性。我们在涵盖单跳和多跳问答任务的五个数据集上进行了实证实验，结果表明LevelRAG相较于现有RAG方法表现更为优异。特别值得一提的是，LevelRAG甚至超越了当前最先进的专有模型GPT4o，充分证明了其创新价值和对RAG领域的深远影响。

> Retrieval-Augmented Generation (RAG) is a crucial method for mitigating hallucinations in Large Language Models (LLMs) and integrating external knowledge into their responses. Existing RAG methods typically employ query rewriting to clarify the user intent and manage multi-hop logic, while using hybrid retrieval to expand search scope. However, the tight coupling of query rewriting to the dense retriever limits its compatibility with hybrid retrieval, impeding further RAG performance improvements. To address this challenge, we introduce a high-level searcher that decomposes complex queries into atomic queries, independent of any retriever-specific optimizations. Additionally, to harness the strengths of sparse retrievers for precise keyword retrieval, we have developed a new sparse searcher that employs Lucene syntax to enhance retrieval accuracy.Alongside web and dense searchers, these components seamlessly collaborate within our proposed method, \textbf{LevelRAG}. In LevelRAG, the high-level searcher orchestrates the retrieval logic, while the low-level searchers (sparse, web, and dense) refine the queries for optimal retrieval. This approach enhances both the completeness and accuracy of the retrieval process, overcoming challenges associated with current query rewriting techniques in hybrid retrieval scenarios. Empirical experiments conducted on five datasets, encompassing both single-hop and multi-hop question answering tasks, demonstrate the superior performance of LevelRAG compared to existing RAG methods. Notably, LevelRAG outperforms the state-of-the-art proprietary model, GPT4o, underscoring its effectiveness and potential impact on the RAG field.

[Arxiv](https://arxiv.org/abs/2502.18139)