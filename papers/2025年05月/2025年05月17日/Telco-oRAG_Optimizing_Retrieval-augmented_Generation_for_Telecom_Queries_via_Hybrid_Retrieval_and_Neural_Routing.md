# Telco-oRAG：利用混合检索与神经路由优化电信查询的检索增强生成

发布时间：2025年05月17日

`RAG` `移动网络`

> Telco-oRAG: Optimizing Retrieval-augmented Generation for Telecom Queries via Hybrid Retrieval and Neural Routing

# 摘要

> 人工智能将成为下一代移动网络（6G）的关键支柱之一，它不仅能够提供新型增值业务，还能显著提升网络性能。在这一背景下，大型语言模型凭借其意图理解、智能知识检索、编程能力和跨域编排能力，有望彻底改变电信行业的格局。本文介绍的 Telco-oRAG 是一个针对电信领域技术问题（特别是 3GPP 标准）优化的开源检索增强生成（RAG）框架。Telco-oRAG 采用了结合 3GPP 领域特定检索与网络搜索的混合检索策略，并通过 glossary 增强的查询优化和神经路由实现了内存高效的检索。实验结果显示，与基线相比，Telco-oRAG 在回答与 3GPP 相关的问题时准确率提升了 17.6%，在词汇查询方面也提高了 10.6%。此外，与基线 RAG 相比，通过针对相关 3GPP 系列的定向检索，Telco-oRAG 将内存使用量减少了 45%，并使开源 LLM 在电信基准测试中达到了 GPT-4 级别的准确率。

> Artificial intelligence will be one of the key pillars of the next generation of mobile networks (6G), as it is expected to provide novel added-value services and improve network performance. In this context, large language models have the potential to revolutionize the telecom landscape through intent comprehension, intelligent knowledge retrieval, coding proficiency, and cross-domain orchestration capabilities. This paper presents Telco-oRAG, an open-source Retrieval-Augmented Generation (RAG) framework optimized for answering technical questions in the telecommunications domain, with a particular focus on 3GPP standards. Telco-oRAG introduces a hybrid retrieval strategy that combines 3GPP domain-specific retrieval with web search, supported by glossary-enhanced query refinement and a neural router for memory-efficient retrieval. Our results show that Telco-oRAG improves the accuracy in answering 3GPP-related questions by up to 17.6% and achieves a 10.6% improvement in lexicon queries compared to baselines. Furthermore, Telco-oRAG reduces memory usage by 45% through targeted retrieval of relevant 3GPP series compared to baseline RAG, and enables open-source LLMs to reach GPT-4-level accuracy on telecom benchmarks.

[Arxiv](https://arxiv.org/abs/2505.11856)