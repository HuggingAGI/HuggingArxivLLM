# 精准对话专家：多智能体系统中的问答路由与规划

发布时间：2025年01月13日

`Agent

理由：这篇论文主要讨论的是如何通过多智能体系统（RopMura）来提升RAG技术在跨领域查询中的表现。论文的核心在于智能体的设计、路由器和规划器的机制，这些都是典型的智能体（Agent）研究内容。虽然涉及RAG技术，但重点在于智能体的协同工作，因此更适合归类为Agent。` `智能体系统` `跨领域查询`

> Talk to Right Specialists: Routing and Planning in Multi-agent System for Question Answering

# 摘要

> 借助大型语言模型（LLMs），智能体可以通过检索增强生成（RAG）技术整合外部知识，提升响应可靠性。然而，现有的RAG智能体通常依赖单一领域知识源，导致其在处理跨领域查询时容易出现幻觉或不准确响应。将多个知识库整合到统一的RAG智能体中面临诸多挑战，如检索开销增加和敏感数据的主权问题。为此，我们提出了RopMura，一个创新的多智能体系统，通过高效的路径选择和规划机制克服这些限制。RopMura的核心包括：一个基于知识边界智能选择最相关智能体的路由器，以及一个将复杂多跳查询分解为可管理步骤的规划器，从而实现跨领域响应的协调。实验表明，RopMura不仅能精准处理单跳查询，还能通过路由与规划机制的结合，为复杂查询提供准确的多步解决方案。

> Leveraging large language models (LLMs), an agent can utilize retrieval-augmented generation (RAG) techniques to integrate external knowledge and increase the reliability of its responses. Current RAG-based agents integrate single, domain-specific knowledge sources, limiting their ability and leading to hallucinated or inaccurate responses when addressing cross-domain queries. Integrating multiple knowledge bases into a unified RAG-based agent raises significant challenges, including increased retrieval overhead and data sovereignty when sensitive data is involved. In this work, we propose RopMura, a novel multi-agent system that addresses these limitations by incorporating highly efficient routing and planning mechanisms. RopMura features two key components: a router that intelligently selects the most relevant agents based on knowledge boundaries and a planner that decomposes complex multi-hop queries into manageable steps, allowing for coordinating cross-domain responses. Experimental results demonstrate that RopMura effectively handles both single-hop and multi-hop queries, with the routing mechanism enabling precise answers for single-hop queries and the combined routing and planning mechanisms achieving accurate, multi-step resolutions for complex queries.

[Arxiv](https://arxiv.org/abs/2501.07813)