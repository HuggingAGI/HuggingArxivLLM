# 打造智能体友好型REST API：从OpenAPI到模型上下文协议服务，助力工具增强型LLM

发布时间：2025年07月21日

`LLM应用` `软件开发`

> Making REST APIs Agent-Ready: From OpenAPI to Model Context Protocol Servers for Tool-Augmented LLMs

# 摘要

> 大型语言模型 (LLMs) 正从被动的文本生成器向能够主动调用外部工具的智能代理演进。为支持这一变革，构建工具集成的可扩展协议变得尤为重要。Anthropic 于 2024 年提出的模型上下文协议 (MCP) 提供了基于模式驱动的动态工具发现与调用标准。然而，目前构建 MCP 服务器仍需手动重复劳动，开发人员不得不编写粘合代码、处理身份验证并手动配置模式，这与 MCP 旨在消除的集成重复工作并无二致。

本研究探讨了能否实现 MCP 服务器构建的自动化。我们首先分析了 MCP 的采用趋势：在发布后六个月内创建的 22,000 多个 MCP 标记的 GitHub 仓库中，仅不到 5% 包含服务器实现，且这些项目多为小型、单一维护者的简单脚手架代码。为填补这一空白，我们推出了 AutoMCP —— 一款从 OpenAPI 2.0/3.0 规范自动生成 MCP 服务器的编译器。AutoMCP 能够解析 REST API 定义，自动生成完整的服务器实现，包括模式注册与身份验证处理。

我们对涵盖 10 多个领域、包含 5,066 个端点的 50 个真实世界 API 进行了 AutoMCP 的全面评估。在 1,023 个分层采样的工具调用中，76.5% 的调用开箱即用成功。通过手动故障分析，我们发现五个常见问题，所有问题均源于 OpenAPI 合同中的不一致或遗漏。经过平均每 API 19 行规范更改的 minor 修复后，AutoMCP 实现了 99.9% 的成功率。

我们的研究贡献包括：(i) 对 MCP 的采用情况进行了深入分析，并量化了手动服务器开发的成本，(ii) 证明 OpenAPI 规范尽管存在质量问题，但仍可实现近乎完整的 MCP 服务器自动化，(iii) 提供了一个包含 5,066 个可调用工具的语料库，并分享了修复常见规范缺陷的实用见解。

> Large Language Models (LLMs) are evolving from passive text generators into active agents that invoke external tools. To support this shift, scalable protocols for tool integration are essential. The Model Context Protocol (MCP), introduced by Anthropic in 2024, offers a schema-driven standard for dynamic tool discovery and invocation. Yet, building MCP servers remains manual and repetitive, requiring developers to write glue code, handle authentication, and configure schemas by hand-replicating much of the integration effort MCP aims to eliminate.
  This paper investigates whether MCP server construction can be meaningfully automated. We begin by analyzing adoption trends: among 22,000+ MCP-tagged GitHub repositories created within six months of release, fewer than 5% include servers, typically small, single-maintainer projects dominated by repetitive scaffolding. To address this gap, we present AutoMCP, a compiler that generates MCP servers from OpenAPI 2.0/3.0 specifications. AutoMCP parses REST API definitions and produces complete server implementations, including schema registration and authentication handling.
  We evaluate AutoMCP on 50 real-world APIs spanning 5,066 endpoints across over 10 domains. From a stratified sample of 1,023 tool calls, 76.5% succeeded out of the box. Manual failure analysis revealed five recurring issues, all attributable to inconsistencies or omissions in the OpenAPI contracts. After minor fixes, averaging 19 lines of spec changes per API, AutoMCP achieved 99.9% success.
  Our findings (i) analyze MCP adoption and quantify the cost of manual server development, (ii) demonstrate that OpenAPI specifications, despite quality issues, enable near-complete MCP server automation, and (iii) contribute a corpus of 5,066 callable tools along with insights on repairing common specification flaws.

[Arxiv](https://arxiv.org/abs/2507.16044)