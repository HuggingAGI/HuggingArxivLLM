# # 大型语言模型代理应当遵循安全原则

发布时间：2025年05月29日

`Agent` `信息安全` `智能体系统`

> LLM Agents Should Employ Security Principles

# 摘要

> 大型语言模型（LLM）代理在自动化复杂任务方面展现出巨大潜力，但多代理交互及系统对提示注入等攻击的易感性带来了隐私泄露和被利用的风险。本文主张在大规模部署LLM代理时，应采纳信息安全领域的核心设计原则，如纵深防御、最小特权、完全调解和心理可接受性。这些原则在过去五十年中一直指导着信息系统安全机制的设计，我们相信它们将为智能体系统提供坚实的安全保障。我们提出了AgentSandbox，一个嵌入这些安全原则的概念性框架，旨在为代理的整个生命周期提供保护。通过从良性效用、攻击效用和攻击成功率三个维度对当前最先进的LLM进行评估，结果表明AgentSandbox在保持高实用性的同时大幅降低了隐私风险。通过将安全设计原则融入新兴LLM代理协议的基础架构，我们致力于构建与用户隐私期望及监管要求相契合的可信智能体生态系统。

> Large Language Model (LLM) agents show considerable promise for automating complex tasks using contextual reasoning; however, interactions involving multiple agents and the system's susceptibility to prompt injection and other forms of context manipulation introduce new vulnerabilities related to privacy leakage and system exploitation. This position paper argues that the well-established design principles in information security, which are commonly referred to as security principles, should be employed when deploying LLM agents at scale. Design principles such as defense-in-depth, least privilege, complete mediation, and psychological acceptability have helped guide the design of mechanisms for securing information systems over the last five decades, and we argue that their explicit and conscientious adoption will help secure agentic systems. To illustrate this approach, we introduce AgentSandbox, a conceptual framework embedding these security principles to provide safeguards throughout an agent's life-cycle. We evaluate with state-of-the-art LLMs along three dimensions: benign utility, attack utility, and attack success rate. AgentSandbox maintains high utility for its intended functions under both benign and adversarial evaluations while substantially mitigating privacy risks. By embedding secure design principles as foundational elements within emerging LLM agent protocols, we aim to promote trustworthy agent ecosystems aligned with user privacy expectations and evolving regulatory requirements.

[Arxiv](https://arxiv.org/abs/2505.24019)