# TURA：用于AI搜索的工具增强型统一检索代理

发布时间：2025年08月06日

`RAG` `搜索引擎` `对话式AI`

> TURA: Tool-Augmented Unified Retrieval Agent for AI Search

# 摘要

> 大型语言模型（LLMs）的出现正在推动搜索引擎向对话式AI搜索产品转型，主要通过网络语料库上的检索增强生成（RAG）方法实现。然而，这一范式在工业应用中存在显著局限性。传统RAG方法难以应对实时需求和涉及动态生成内容（如票务可用性或库存信息）的结构化查询。由于仅限于索引静态页面，搜索引擎无法执行处理时效性数据所需的互动查询。学术研究聚焦于优化RAG处理静态内容，却忽视了复杂意图和动态数据源（如数据库和实时API）的需求。为解决这一问题，我们推出TURA（AI搜索工具增强统一检索代理），这是一个结合RAG与工具使用代理的三阶段创新框架，能够同时访问静态内容和动态实时信息。TURA包含三个关键组件：意图感知检索模块，用于分解查询并检索以模型上下文协议（MCP）服务器封装的信息源；基于有向无环图（DAG）的任务规划器，用于建模任务依赖关系以实现最优并行执行；以及轻量级蒸馏代理执行器，用于高效工具调用。TURA是首个系统性地连接静态RAG和动态信息源的架构，致力于打造世界级AI搜索产品。它服务于千万级用户，借助代理框架提供强大、实时的答案，同时满足大规模工业系统的低延迟需求。

> The advent of Large Language Models (LLMs) is transforming search engines into conversational AI search products, primarily using Retrieval-Augmented Generation (RAG) on web corpora. However, this paradigm has significant industrial limitations. Traditional RAG approaches struggle with real-time needs and structured queries that require accessing dynamically generated content like ticket availability or inventory. Limited to indexing static pages, search engines cannot perform the interactive queries needed for such time-sensitive data. Academic research has focused on optimizing RAG for static content, overlooking complex intents and the need for dynamic sources like databases and real-time APIs. To bridge this gap, we introduce TURA (Tool-Augmented Unified Retrieval Agent for AI Search), a novel three-stage framework that combines RAG with agentic tool-use to access both static content and dynamic, real-time information. TURA has three key components: an Intent-Aware Retrieval module to decompose queries and retrieve information sources encapsulated as Model Context Protocol (MCP) Servers, a DAG-based Task Planner that models task dependencies as a Directed Acyclic Graph (DAG) for optimal parallel execution, and a lightweight Distilled Agent Executor for efficient tool calling. TURA is the first architecture to systematically bridge the gap between static RAG and dynamic information sources for a world-class AI search product. Serving tens of millions of users, it leverages an agentic framework to deliver robust, real-time answers while meeting the low-latency demands of a large-scale industrial system.

[Arxiv](https://arxiv.org/abs/2508.04604)