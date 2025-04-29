# # 防御工具劫持，保护生成式AI多智能体系统：基于零信任注册表的安全方法

发布时间：2025年04月28日

`Agent

这篇论文主要探讨了生成式AI多智能体系统中的安全问题，特别是工具劫持威胁，并提出了解决方案。因此，它属于Agent类别。` `多智能体系统`

> Securing GenAI Multi-Agent Systems Against Tool Squatting: A Zero Trust Registry-Based Approach

# 摘要

> 生成式AI多智能体系统（MAS）的崛起，要求建立标准化协议以实现智能体与外部工具的发现与交互。然而，这些协议也带来了新的安全挑战，特别是“工具劫持”——对工具的欺骗性注册或表示。本文在新兴互操作性标准（如模型上下文协议（MCP）或智能体间无缝通信协议）的背景下，深入分析了工具劫持威胁，并提出了一套全面的工具注册系统，以有效缓解这些风险。我们建议的以安全为核心架构，包含管理员控制的注册机制、中心化的工具发现功能、通过专用智能体和工具注册服务实施的细粒度访问策略、基于工具版本控制和已知漏洞的动态信任评分机制，以及即时凭证供应功能。基于其设计理念，本提案的注册框架不仅能够有效防范常见的工具劫持攻击途径，还能够保持多智能体系统的灵活性和强大功能。这项研究填补了快速发展的生成式AI生态系统中的关键安全空白，并为生产环境中的安全工具集成提供了坚实基础。

> The rise of generative AI (GenAI) multi-agent systems (MAS) necessitates standardized protocols enabling agents to discover and interact with external tools. However, these protocols introduce new security challenges, particularly; tool squatting; the deceptive registration or representation of tools. This paper analyzes tool squatting threats within the context of emerging interoperability standards, such as Model Context Protocol (MCP) or seamless communication between agents protocols. It introduces a comprehensive Tool Registry system designed to mitigate these risks. We propose a security-focused architecture featuring admin-controlled registration, centralized tool discovery, fine grained access policies enforced via dedicated Agent and Tool Registry services, a dynamic trust scoring mechanism based on tool versioning and known vulnerabilities, and just in time credential provisioning. Based on its design principles, the proposed registry framework aims to effectively prevent common tool squatting vectors while preserving the flexibility and power of multi-agent systems. This work addresses a critical security gap in the rapidly evolving GenAI ecosystem and provides a foundation for secure tool integration in production environments.

[Arxiv](https://arxiv.org/abs/2504.19951)