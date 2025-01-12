# 多模态案例推理应用的通用检索增强生成框架

发布时间：2025年01月09日

`RAG

理由：这篇论文主要讨论了结合检索增强生成（RAG）的大型语言模型（LLMs）在多模态案例推理（CBR）中的应用。论文提出了一个名为MCBR-RAG的框架，该框架通过将非文本案例信息转化为文本形式，增强了LLM在检索和生成环节的表现。因此，这篇论文的核心内容与RAG技术密切相关，应归类为RAG。`

> A General Retrieval-Augmented Generation Framework for Multimodal Case-Based Reasoning Applications

# 摘要

> 基于案例的推理（CBR）是一种利用已解决案例库来应对新问题的经验驱动方法。最新研究表明，结合检索增强生成（RAG）的大型语言模型（LLMs）能够助力CBR流程中的检索与重用环节，即通过查找相似案例并作为LLM查询的补充背景。尽管多数研究聚焦于纯文本场景，但现实问题往往涉及多模态案例元素。为此，本文推出MCBR-RAG，一个专为多模态CBR设计的通用RAG框架。该框架巧妙地将非文本案例信息转化为文本形式，实现两大功能：一是构建可检索的应用专属潜在表征，二是融合所有案例要素，为LLM查询注入更丰富的上下文，从而提升生成效果。我们通过Math-24简化版及Backgammon复杂版应用的实验验证了MCBR-RAG的优越性，实证数据表明，相较于无上下文辅助的基准LLM，MCBR-RAG显著提升了生成内容的质量。

> Case-based reasoning (CBR) is an experience-based approach to problem solving, where a repository of solved cases is adapted to solve new cases. Recent research shows that Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) can support the Retrieve and Reuse stages of the CBR pipeline by retrieving similar cases and using them as additional context to an LLM query. Most studies have focused on text-only applications, however, in many real-world problems the components of a case are multimodal. In this paper we present MCBR-RAG, a general RAG framework for multimodal CBR applications. The MCBR-RAG framework converts non-text case components into text-based representations, allowing it to: 1) learn application-specific latent representations that can be indexed for retrieval, and 2) enrich the query provided to the LLM by incorporating all case components for better context. We demonstrate MCBR-RAG's effectiveness through experiments conducted on a simplified Math-24 application and a more complex Backgammon application. Our empirical results show that MCBR-RAG improves generation quality compared to a baseline LLM with no contextual information provided.

[Arxiv](https://arxiv.org/abs/2501.05030)