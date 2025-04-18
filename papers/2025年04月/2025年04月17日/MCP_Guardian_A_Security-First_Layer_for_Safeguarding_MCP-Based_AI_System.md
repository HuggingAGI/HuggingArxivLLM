# # MCP 守护者：安全优先层，保护基于 MCP 的 AI 系统

发布时间：2025年04月17日

`Agent` `AI服务` `企业服务`

> MCP Guardian: A Security-First Layer for Safeguarding MCP-Based AI System

# 摘要

> 随着Agent AI的普及，行业在模型能力方面投入巨大，推理能力和质量实现了快速飞跃。然而，这些系统仍大多困在数据孤岛中，每次新整合都需要定制逻辑，难以实现规模化。模型上下文协议（MCP）通过定义一个通用的开放标准，解决了这一挑战，该标准可安全连接基于AI的应用程序（MCP客户端）与数据源（MCP服务器）。然而，MCP的灵活性也带来了新的风险，包括恶意工具服务器和数据完整性的破坏。我们推出MCP Guardian框架，通过认证、限流、日志记录、跟踪和Web应用防火墙（WAF）扫描，强化基于MCP的通信。通过真实场景和实证测试，我们展示了MCP Guardian如何有效抵御攻击，确保稳健监管，且开销极小。我们的方法为AI助手提供了安全、可扩展的数据访问，强调了深度防御的重要性，这使得在AI驱动的环境中实现更安全、更透明的创新成为可能。

> As Agentic AI gain mainstream adoption, the industry invests heavily in model capabilities, achieving rapid leaps in reasoning and quality. However, these systems remain largely confined to data silos, and each new integration requires custom logic that is difficult to scale. The Model Context Protocol (MCP) addresses this challenge by defining a universal, open standard for securely connecting AI-based applications (MCP clients) to data sources (MCP servers). However, the flexibility of the MCP introduces new risks, including malicious tool servers and compromised data integrity. We present MCP Guardian, a framework that strengthens MCP-based communication with authentication, rate-limiting, logging, tracing, and Web Application Firewall (WAF) scanning. Through real-world scenarios and empirical testing, we demonstrate how MCP Guardian effectively mitigates attacks and ensures robust oversight with minimal overheads. Our approach fosters secure, scalable data access for AI assistants, underscoring the importance of a defense-in-depth approach that enables safer and more transparent innovation in AI-driven environments.

[Arxiv](https://arxiv.org/abs/2504.12757)