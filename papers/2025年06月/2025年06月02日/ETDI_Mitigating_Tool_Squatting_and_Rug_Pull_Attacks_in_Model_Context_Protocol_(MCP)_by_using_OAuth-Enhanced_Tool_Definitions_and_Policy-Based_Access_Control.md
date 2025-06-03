# ETDI：通过OAuth增强的工具定义和基于策略的访问控制，有效缓解模型上下文协议（MCP）中的工具劫持攻击与跑路攻击。

发布时间：2025年06月02日

`LLM应用`

> ETDI: Mitigating Tool Squatting and Rug Pull Attacks in Model Context Protocol (MCP) by using OAuth-Enhanced Tool Definitions and Policy-Based Access Control

# 摘要

> 模型上下文协议 (MCP) 在扩展大型语言模型 (LLMs) 的能力方面发挥着关键作用，支持与外部工具和数据源的无缝集成。然而，标准 MCP 存在严重安全漏洞，尤其是工具中毒 (Tool Poisoning) 和 Rug Pull 攻击。本文提出增强工具定义接口 (ETDI)，这是一个专为强化 MCP 安全性设计的扩展方案。ETDI 采用加密身份验证、不可变版本的工具定义以及显式的权限管理，通常结合 OAuth 2.0 使用。我们进一步建议通过细粒度、基于策略的访问控制扩展 MCP，借助专用策略引擎，在运行时上下文中动态评估工具能力，超越静态 OAuth 范围。这种分层方法旨在构建一个更安全、更可信且更可控的生态系统，支持 AI 应用与 LLM 和外部工具的高效交互。

> The Model Context Protocol (MCP) plays a crucial role in extending the capabilities of Large Language Models (LLMs) by enabling integration with external tools and data sources. However, the standard MCP specification presents significant security vulnerabilities, notably Tool Poisoning and Rug Pull attacks. This paper introduces the Enhanced Tool Definition Interface (ETDI), a security extension designed to fortify MCP. ETDI incorporates cryptographic identity verification, immutable versioned tool definitions, and explicit permission management, often leveraging OAuth 2.0. We further propose extending MCP with fine-grained, policy-based access control, where tool capabilities are dynamically evaluated against explicit policies using a dedicated policy engine, considering runtime context beyond static OAuth scopes. This layered approach aims to establish a more secure, trustworthy, and controllable ecosystem for AI applications interacting with LLMs and external tools.

[Arxiv](https://arxiv.org/abs/2506.01333)