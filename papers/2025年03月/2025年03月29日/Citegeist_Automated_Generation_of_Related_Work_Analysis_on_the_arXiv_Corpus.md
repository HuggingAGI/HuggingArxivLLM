# # Citegeist：基于 arXiv 语料库的自动化相关工作分析生成

发布时间：2025年03月29日

`RAG` `学术出版` `学术研究支持`

> Citegeist: Automated Generation of Related Work Analysis on the arXiv Corpus

# 摘要

> 大型语言模型为高质量书面作品的生成带来了重大机遇。然而，生成虚假来源和无法直接访问相关科学文章的知识库限制了它们在研究社区中的应用。为此，我们推出了Citegeist：一个基于arXiv语料库的动态检索增强生成（RAG）应用 pipeline，用于生成相关工作部分及其他有引用支持的输出。我们采用了基于嵌入的相似性匹配、总结和多阶段过滤的混合方法。为了适应文档库的持续增长，我们还提出了一种优化方法来整合新论文和修改后的论文。为了便于科学界使用，我们发布了网站（https://citegeist.org）以及与多种大型语言模型实现兼容的实现框架。

> Large Language Models provide significant new opportunities for the generation of high-quality written works. However, their employment in the research community is inhibited by their tendency to hallucinate invalid sources and lack of direct access to a knowledge base of relevant scientific articles. In this work, we present Citegeist: An application pipeline using dynamic Retrieval Augmented Generation (RAG) on the arXiv Corpus to generate a related work section and other citation-backed outputs. For this purpose, we employ a mixture of embedding-based similarity matching, summarization, and multi-stage filtering. To adapt to the continuous growth of the document base, we also present an optimized way of incorporating new and modified papers. To enable easy utilization in the scientific community, we release both, a website (https://citegeist.org), as well as an implementation harness that works with several different LLM implementations.

[Arxiv](https://arxiv.org/abs/2503.23229)