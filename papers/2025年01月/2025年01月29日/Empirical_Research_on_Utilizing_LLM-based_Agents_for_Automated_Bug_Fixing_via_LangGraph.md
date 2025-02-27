# # 实证研究：通过LangGraph利用基于LLM的代理实现自动化漏洞修复

发布时间：2025年01月29日

`LLM应用` `软件开发`

> Empirical Research on Utilizing LLM-based Agents for Automated Bug Fixing via LangGraph

# 摘要

> 本文提出了一种用于自动化代码生成和调试的创新性框架，旨在提升软件开发中的准确性、效率和可扩展性。该系统整合了三个核心组件LangGraph、GLM4 Flash和ChromaDB，并通过一个四步迭代工作流实现稳健性能和无缝功能。

LangGraph作为基于图的任务编排库，提供精确的控制和执行，同时维护统一的状态对象以实现动态更新和一致性。它支持多代理、分层和顺序化流程，使其能够高度适应复杂的软件工程工作流。GLM4 Flash作为一种大型语言模型，凭借其在自然语言理解、上下文推理和多语言支持方面的先进能力，能够根据用户提示生成准确的代码片段。ChromaDB则作为语义搜索和上下文记忆存储的向量数据库，能够基于历史数据识别模式并生成上下文感知的修复方案。

该系统通过一个结构化的四步流程运行：(1) 代码生成，将自然语言描述转化为可执行代码；(2) 代码执行，通过识别运行时错误和不一致来验证代码；(3) 代码修复，利用ChromaDB的记忆能力和LangGraph的状态跟踪功能迭代优化错误代码；(4) 代码更新，通过迭代修改确保代码满足功能和性能要求。


> This paper presents a novel framework for automated code generation and debugging, designed to improve accuracy, efficiency, and scalability in software development. The proposed system integrates three core components LangGraph, GLM4 Flash, and ChromaDB within a four step iterative workflow to deliver robust performance and seamless functionality.
  LangGraph serves as a graph-based library for orchestrating tasks, providing precise control and execution while maintaining a unified state object for dynamic updates and consistency. It supports multi-agent, hierarchical, and sequential processes, making it highly adaptable to complex software engineering workflows. GLM4 Flash, a large language model, leverages its advanced capabilities in natural language understanding, contextual reasoning, and multilingual support to generate accurate code snippets based on user prompts. ChromaDB acts as a vector database for semantic search and contextual memory storage, enabling the identification of patterns and the generation of context-aware bug fixes based on historical data.
  The system operates through a structured four-step process: (1) Code Generation, which translates natural language descriptions into executable code; (2) Code Execution, which validates the code by identifying runtime errors and inconsistencies; (3) Code Repair, which iteratively refines buggy code using ChromaDB's memory capabilities and LangGraph's state tracking; and (4) Code Update, which ensures the code meets functional and performance requirements through iterative modifications.

[Arxiv](https://arxiv.org/abs/2502.18465)