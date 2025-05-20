# 电信-oRAG：通过混合检索与神经路由优化电信领域的检索增强生成

发布时间：2025年05月17日

`RAG` `移动网络`

> Telco-oRAG: Optimizing Retrieval-augmented Generation for Telecom Queries via Hybrid Retrieval and Neural Routing

# 摘要

> 人工智能将成为下一代移动网络（6G）的关键支柱之一，它不仅能够提供新型增值业务，还能显著提升网络性能。在这一背景下，大型语言模型凭借其强大的意图理解、智能知识检索、编码能力和跨领域编排能力，有望彻底改变电信行业的格局。本文介绍了 Telco-oRAG，一个专为电信领域技术问题（尤其是 3GPP 标准相关问题）优化的开源增强型检索生成（RAG）框架。Telco-oRAG 采用了结合 3GPP 域特定检索与网络搜索的混合检索策略，并通过基于 glossary 的查询优化和神经路由实现高效的内存检索。实验结果表明，与基线模型相比，Telco-oRAG 在回答 3GPP 相关问题时的准确率提高了 17.6%，在词汇查询方面提升了 10.6%。此外，与基线 RAG 模型相比，Telco-oRAG 通过针对性检索相关 3GPP 系列标准，将内存使用量减少了 45%，并使开源大语言模型在电信基准测试中的准确率达到了与 GPT-4 相当的水平。

> Artificial intelligence will be one of the key pillars of the next generation of mobile networks (6G), as it is expected to provide novel added-value services and improve network performance. In this context, large language models have the potential to revolutionize the telecom landscape through intent comprehension, intelligent knowledge retrieval, coding proficiency, and cross-domain orchestration capabilities. This paper presents Telco-oRAG, an open-source Retrieval-Augmented Generation (RAG) framework optimized for answering technical questions in the telecommunications domain, with a particular focus on 3GPP standards. Telco-oRAG introduces a hybrid retrieval strategy that combines 3GPP domain-specific retrieval with web search, supported by glossary-enhanced query refinement and a neural router for memory-efficient retrieval. Our results show that Telco-oRAG improves the accuracy in answering 3GPP-related questions by up to 17.6% and achieves a 10.6% improvement in lexicon queries compared to baselines. Furthermore, Telco-oRAG reduces memory usage by 45% through targeted retrieval of relevant 3GPP series compared to baseline RAG, and enables open-source LLMs to reach GPT-4-level accuracy on telecom benchmarks.

[Arxiv](https://arxiv.org/abs/2505.11856)