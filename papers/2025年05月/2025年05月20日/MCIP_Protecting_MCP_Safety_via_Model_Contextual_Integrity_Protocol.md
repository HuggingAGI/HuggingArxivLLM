# # MCIP：通过模型上下文完整性协议保护MCP安全

发布时间：2025年05月20日

`其他

其他` `计算机科学`

> MCIP: Protecting MCP Safety via Model Contextual Integrity Protocol

# 摘要

> 模型上下文协议 (MCP) 为用户和开发者提供了一个易于使用的生态系统，但同时也带来了尚未充分探索的安全风险。其分散式架构，将客户端和服务器分离，给系统安全性分析带来了独特挑战。本文提出了一种增强 MCP 安全性的新框架。基于 MAESTRO 框架，我们首先分析了 MCP 中缺失的安全机制，并在此基础上提出了改进版的模型上下文完整性协议 (MCIP)，弥补了这些空白。随后，我们开发了一个细致的分类法，涵盖了在 MCP 场景中观察到的各种不安全行为。基于此分类法，我们创建了基准和训练数据，支持对 LLM 在识别 MCP 交互中的安全风险方面的能力进行评估和改进。利用这些基准和训练数据，我们在最先进的 LLM 上进行了广泛实验。结果显示，LLM 在 MCP 交互中存在显著脆弱性，而我们的方法有效提升了其安全性能。

> As Model Context Protocol (MCP) introduces an easy-to-use ecosystem for users and developers, it also brings underexplored safety risks. Its decentralized architecture, which separates clients and servers, poses unique challenges for systematic safety analysis. This paper proposes a novel framework to enhance MCP safety. Guided by the MAESTRO framework, we first analyze the missing safety mechanisms in MCP, and based on this analysis, we propose the Model Contextual Integrity Protocol (MCIP), a refined version of MCP that addresses these gaps.Next, we develop a fine-grained taxonomy that captures a diverse range of unsafe behaviors observed in MCP scenarios. Building on this taxonomy, we develop benchmark and training data that support the evaluation and improvement of LLMs' capabilities in identifying safety risks within MCP interactions. Leveraging the proposed benchmark and training data, we conduct extensive experiments on state-of-the-art LLMs. The results highlight LLMs' vulnerabilities in MCP interactions and demonstrate that our approach substantially improves their safety performance.

[Arxiv](https://arxiv.org/abs/2505.14590)