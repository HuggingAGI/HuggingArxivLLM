# 太级：基于MCP的多模态数据湖分析方案

发布时间：2025年05月16日

`LLM应用` `企业应用` `数据管理`

> TAIJI: MCP-based Multi-Modal Data Analytics on Data Lakes

# 摘要

> 数据湖中的多模态数据分析面临三大挑战：数据科学家需同时处理结构化、半结构化和非结构化数据；现有自然语言和SQL-like查询语言难以精准捕捉用户需求；单一LLM处理多模态数据效率低下；此外，数据湖中的数据可能不完整或过时，需外部知识补充。
    本文提出了一种全新的多模态数据分析系统。该系统基于模型上下文协议（MCP），创新性地构建了一个协作式架构。我们设计了专门针对数据湖多模态数据的语义操作符层级，并开发了AI驱动的NL2Operator翻译器，实现了用户意图与分析执行的无缝衔接。系统采用MCP执行框架，每个节点运行特定优化的基础模型，兼顾准确性和效率，支持模块化扩展。最后，我们引入深度学习和机器遗忘技术，构建动态更新机制，平衡数据新鲜度与推理效率，为多模态数据分析提供了全新解决方案。
    

> The variety of data in data lakes presents significant challenges for data analytics, as data scientists must simultaneously analyze multi-modal data, including structured, semi-structured, and unstructured data. While Large Language Models (LLMs) have demonstrated promising capabilities, they still remain inadequate for multi-modal data analytics in terms of accuracy, efficiency, and freshness. First, current natural language (NL) or SQL-like query languages may struggle to precisely and comprehensively capture users' analytical intent. Second, relying on a single unified LLM to process diverse data modalities often leads to substantial inference overhead. Third, data stored in data lakes may be incomplete or outdated, making it essential to integrate external open-domain knowledge to generate timely and relevant analytics results.
  In this paper, we envision a new multi-modal data analytics system. Specifically, we propose a novel architecture built upon the Model Context Protocol (MCP), an emerging paradigm that enables LLMs to collaborate with knowledgeable agents. First, we define a semantic operator hierarchy tailored for querying multi-modal data in data lakes and develop an AI-agent-powered NL2Operator translator to bridge user intent and analytical execution. Next, we introduce an MCP-based execution framework, in which each MCP server hosts specialized foundation models optimized for specific data modalities. This design enhances both accuracy and efficiency, while supporting high scalability through modular deployment. Finally, we propose a updating mechanism by harnessing the deep research and machine unlearning techniques to refresh the data lakes and LLM knowledges, with the goal of balancing the data freshness and inference efficiency.

[Arxiv](https://arxiv.org/abs/2505.11270)