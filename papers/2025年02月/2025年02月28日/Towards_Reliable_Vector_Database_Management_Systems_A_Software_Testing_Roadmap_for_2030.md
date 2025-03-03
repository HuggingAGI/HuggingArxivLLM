# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月28日

`LLM应用

理由：这篇论文探讨了向量数据库管理系统（VDBMS）在支持大型语言模型（LLMs）应用中的关键作用，特别是检索增强生成（RAG）、长期记忆和缓存机制。虽然它讨论了测试挑战，但这些挑战是针对支持LLM应用的VDBMS，因此属于LLM应用类别。` `数据库管理` `人工智能`

> Towards Reliable Vector Database Management Systems: A Software Testing Roadmap for 2030

# 摘要

> 大型语言模型 (LLMs) 和 AI 应用的飞速发展，让向量数据库管理系统 (VDBMS) 成为了关键基础设施中的明星角色。VDBMS 专注于处理密集向量嵌入的存储、索引和查询，为 LLM 提供了检索增强生成、长期记忆和缓存机制等高级功能。然而，VDBMS 的快速普及速度，已经超出了为其量身定制的严格软件测试方法的发展步伐。与优化结构化数据的传统数据库不同，VDBMS 面临着来自向量数据高维特性、向量搜索模糊语义以及动态数据扩展和混合查询处理需求的独特测试挑战。在本文中，我们首先通过实证研究 VDBMS 的缺陷，识别出测试输入生成、 oracle 定义和测试评估中的关键挑战。基于这些发现，我们提出了首个针对 VDBMS 开发有效测试方法的全面研究路线图。通过解决这些挑战，软件测试社区将能够推动更可靠、更值得信赖的 VDBMS 的发展，从而充分释放 LLM 和数据密集型 AI 应用的潜力。

> The rapid growth of Large Language Models (LLMs) and AI-driven applications has propelled Vector Database Management Systems (VDBMSs) into the spotlight as a critical infrastructure component. VDBMS specializes in storing, indexing, and querying dense vector embeddings, enabling advanced LLM capabilities such as retrieval-augmented generation, long-term memory, and caching mechanisms. However, the explosive adoption of VDBMS has outpaced the development of rigorous software testing methodologies tailored for these emerging systems. Unlike traditional databases optimized for structured data, VDBMS face unique testing challenges stemming from the high-dimensional nature of vector data, the fuzzy semantics in vector search, and the need to support dynamic data scaling and hybrid query processing. In this paper, we begin by conducting an empirical study of VDBMS defects and identify key challenges in test input generation, oracle definition, and test evaluation. Drawing from these insights, we propose the first comprehensive research roadmap for developing effective testing methodologies tailored to VDBMS. By addressing these challenges, the software testing community can contribute to the development of more reliable and trustworthy VDBMS, enabling the full potential of LLMs and data-intensive AI applications.

[Arxiv](https://arxiv.org/abs/2502.20812)