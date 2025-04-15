# MCP桥接器：一个轻量级、支持多种LLM的RESTful代理，用于模型上下文协议服务器

发布时间：2025年04月11日

`LLM应用` `移动计算` `边缘计算`

> MCP Bridge: A Lightweight, LLM-Agnostic RESTful Proxy for Model Context Protocol Servers

# 摘要

> 大型语言模型（LLMs）正通过标准化接口（如MCP）实现与外部工具的无缝协作。然而，现有MCP方案存在局限：它们依赖本地进程执行，难以在移动设备、网页浏览器和边缘计算等资源受限场景中应用。为此，我们推出MCP Bridge——一款轻量级RESTful代理，它能够连接多个MCP服务器并提供统一API访问。与现有方案不同，MCP Bridge完全独立于LLM，支持任何厂商的后端服务。该系统采用基于风险的执行模型，提供标准执行、确认工作流和Docker隔离三种安全级别，同时保持对标准MCP客户端的兼容性。此外，我们开发了基于Python的MCP Gemini代理，支持自然语言与MCP工具交互。实证表明，MCP Bridge不仅解决了直接MCP连接的限制，还提供了增强的安全控制和跨平台兼容性，为复杂LLM应用在以前无法触及的环境中部署提供了可能。

> Large Language Models (LLMs) are increasingly augmented with external tools through standardized interfaces like the Model Context Protocol (MCP). However, current MCP implementations face critical limitations: they typically require local process execution through STDIO transports, making them impractical for resource-constrained environments like mobile devices, web browsers, and edge computing. We present MCP Bridge, a lightweight RESTful proxy that connects to multiple MCP servers and exposes their capabilities through a unified API. Unlike existing solutions, MCP Bridge is fully LLM-agnostic, supporting any backend regardless of vendor. The system implements a risk-based execution model with three security levels standard execution, confirmation workflow, and Docker isolation while maintaining backward compatibility with standard MCP clients. Complementing this server-side infrastructure is a Python based MCP Gemini Agent that facilitates natural language interaction with MCP tools. The evaluation demonstrates that MCP Bridge successfully addresses the constraints of direct MCP connections while providing enhanced security controls and cross-platform compatibility, enabling sophisticated LLM-powered applications in previously inaccessible environments

[Arxiv](https://arxiv.org/abs/2504.08999)