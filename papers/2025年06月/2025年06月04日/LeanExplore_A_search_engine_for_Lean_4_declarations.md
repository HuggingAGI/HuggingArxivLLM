# LeanExplore：专为 Lean 4 声明设计的搜索引擎

发布时间：2025年06月04日

`LLM应用` `搜索技术` `人工智能`

> LeanExplore: A search engine for Lean 4 declarations

# 摘要

> 随着 Lean 4 生态系统的不断扩展，导航其庞大的库带来了新的挑战。本文介绍了一款名为 LeanExplore 的搜索引擎，专注于 Lean 4 声明的高效检索。通过整合多源语义嵌入模型、BM25+ 关键词匹配以及基于 PageRank 的重要性评分，LeanExplore 提供了精准且智能的搜索体验。用户可以通过官方网站（https://www.leanexplore.com/）或 Python API（https://github.com/justincasher/lean-explore）轻松访问这一工具，甚至可以下载数据库自行托管服务。此外，LeanExplore 还支持与大型语言模型 (LLMs) 的深度集成，为用户带来全新可能性：无论是与 AI 助手讨论 Lean 声明，还是构建智能定理证明代理，都变得触手可及。本文将深入探讨 LeanExplore 的技术架构、数据处理机制及其功能，并展望其在提升 Lean 4 工作流效率和推动 AI 驱动数学研究中的重要作用。

> The expanding Lean 4 ecosystem poses challenges for navigating its vast libraries. This paper introduces LeanExplore, a search engine for Lean 4 declarations. LeanExplore enables users to semantically search for statements, both formally and informally, across select Lean 4 packages (including Batteries, Init, Lean, Mathlib, PhysLean, and Std). This search capability is powered by a hybrid ranking strategy, integrating scores from a multi-source semantic embedding model (capturing conceptual meaning from formal Lean code, docstrings, AI-generated informal translations, and declaration titles), BM25+ for keyword-based lexical relevance, and a PageRank-based score reflecting declaration importance and interconnectedness. The search engine is accessible via a dedicated website (https://www.leanexplore.com/) and a Python API (https://github.com/justincasher/lean-explore). Furthermore, the database can be downloaded, allowing users to self-host the service. LeanExplore integrates easily with LLMs via the model context protocol (MCP), enabling users to chat with an AI assistant about Lean declarations or utilize the search engine for building theorem-proving agents. This work details LeanExplore's architecture, data processing, functionalities, and its potential to enhance Lean 4 workflows and AI-driven mathematical research

[Arxiv](https://arxiv.org/abs/2506.11085)