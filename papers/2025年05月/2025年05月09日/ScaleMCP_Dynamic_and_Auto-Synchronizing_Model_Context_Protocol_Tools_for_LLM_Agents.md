# # ScaleMCP: 专为大语言模型代理打造的动态自动同步模型上下文协议工具

发布时间：2025年05月09日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）与模型上下文协议（MCP）的结合，旨在提升LLM代理与外部工具及API的交互能力。它提出了一种新的工具选择方法ScaleMCP，并通过实验验证了其在工具检索和代理调用性能上的提升。这属于LLM在实际应用中的优化和扩展，因此归类为LLM应用。` `工具管理` `自动化`

> ScaleMCP: Dynamic and Auto-Synchronizing Model Context Protocol Tools for LLM Agents

# 摘要

> 大型语言模型（LLMs）的最新进展与模型上下文协议（MCP）的引入，大大提升了LLM代理与外部工具及API动态交互的能力。然而，现有工具选择框架未能集成MCP服务器，仍依赖容易出错的手动更新单体本地工具仓库，导致重复、不一致和低效问题。此外，当前方法在调用LLM代理前完成工具选择，限制了其自主性，影响了多轮交互中的动态重新查询能力。为解决这些问题，我们提出了一种新型工具选择方法ScaleMCP。该方法通过动态为LLM代理配备MCP工具检索器，赋予代理自主添加工具到记忆中的能力。同时，ScaleMCP通过与MCP服务器进行创建、读取、更新、删除（CRUD）操作，构建了一个自动同步的工具存储系统管道，以MCP服务器作为唯一数据源。我们还提出了一种新型嵌入策略——工具文档加权平均（TDWA），旨在在嵌入过程中有选择地强调工具文档的关键部分（如工具名称或合成问题）。我们在一个包含5,000个财务指标MCP服务器的自建数据集上进行了全面评估，涵盖10种LLM模型、5种嵌入模型和5种检索器类型，结果显示在工具检索和代理调用性能方面有显著提升。这充分证明了ScaleMCP在可扩展、动态工具选择和调用方面的有效性。

> Recent advancements in Large Language Models (LLMs) and the introduction of the Model Context Protocol (MCP) have significantly expanded LLM agents' capability to interact dynamically with external tools and APIs. However, existing tool selection frameworks do not integrate MCP servers, instead relying heavily on error-prone manual updates to monolithic local tool repositories, leading to duplication, inconsistencies, and inefficiencies. Additionally, current approaches abstract tool selection before the LLM agent is invoked, limiting its autonomy and hindering dynamic re-querying capabilities during multi-turn interactions. To address these issues, we introduce ScaleMCP, a novel tool selection approach that dynamically equips LLM agents with a MCP tool retriever, giving agents the autonomy to add tools into their memory, as well as an auto-synchronizing tool storage system pipeline through CRUD (create, read, update, delete) operations with MCP servers as the single source of truth. We also propose a novel embedding strategy, Tool Document Weighted Average (TDWA), designed to selectively emphasize critical components of tool documents (e.g. tool name or synthetic questions) during the embedding process. Comprehensive evaluations conducted on a created dataset of 5,000 financial metric MCP servers, across 10 LLM models, 5 embedding models, and 5 retriever types, demonstrate substantial improvements in tool retrieval and agent invocation performance, emphasizing ScaleMCP's effectiveness in scalable, dynamic tool selection and invocation.

[Arxiv](https://arxiv.org/abs/2505.06416)