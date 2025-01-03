# HAICOSYSTEM: 人类与AI交互中的安全风险隔离生态系统

发布时间：2024年10月21日

`Agent

理由：这篇论文主要讨论了AI代理在与人类用户和工具交互中的安全性问题，并提出了一个用于评估AI代理安全性的框架（HAICOSYSTEM）。论文的核心关注点是AI代理的行为和安全性，特别是在复杂社会交互中的表现。因此，这篇论文应归类为Agent。` `AI安全` `社会交互`

> HAICOSYSTEM: An Ecosystem for Sandboxing Safety Risks in Human-AI Interactions

# 摘要

> AI 代理在与人类用户和工具的交互中越来越自主，这也带来了更高的交互安全风险。我们推出了 HAICOSYSTEM，这是一个用于在复杂多样的社会交互中评估 AI 代理安全性的框架。HAICOSYSTEM 包含一个模块化的沙盒环境，能够模拟人类用户与 AI 代理之间的多轮交互，AI 代理配备了多种工具（如患者管理平台）以应对不同场景（如用户试图访问其他患者的个人资料）。为了评估这些交互中的安全性，我们开发了一个多维度的评估框架，涵盖操作、内容、社会和法律风险。通过在医疗、金融、教育等七个领域的 92 个场景中运行 1840 次模拟，我们验证了 HAICOSYSTEM 能够真实模拟用户与 AI 的交互以及 AI 代理的复杂工具使用。实验表明，无论是专有还是开源的最先进 LLM，在超过 50% 的情况下都存在安全风险，尤其是在与模拟的恶意用户交互时，风险更高。我们的研究揭示了构建能够安全应对复杂交互的 AI 代理的挑战，尤其是在面对恶意用户时。为了推动 AI 代理安全生态的发展，我们发布了一个代码平台，供从业者创建自定义场景、模拟交互并评估其代理的安全性和性能。

> AI agents are increasingly autonomous in their interactions with human users and tools, leading to increased interactional safety risks. We present HAICOSYSTEM, a framework examining AI agent safety within diverse and complex social interactions. HAICOSYSTEM features a modular sandbox environment that simulates multi-turn interactions between human users and AI agents, where the AI agents are equipped with a variety of tools (e.g., patient management platforms) to navigate diverse scenarios (e.g., a user attempting to access other patients' profiles). To examine the safety of AI agents in these interactions, we develop a comprehensive multi-dimensional evaluation framework that uses metrics covering operational, content-related, societal, and legal risks. Through running 1840 simulations based on 92 scenarios across seven domains (e.g., healthcare, finance, education), we demonstrate that HAICOSYSTEM can emulate realistic user-AI interactions and complex tool use by AI agents. Our experiments show that state-of-the-art LLMs, both proprietary and open-sourced, exhibit safety risks in over 50\% cases, with models generally showing higher risks when interacting with simulated malicious users. Our findings highlight the ongoing challenge of building agents that can safely navigate complex interactions, particularly when faced with malicious users. To foster the AI agent safety ecosystem, we release a code platform that allows practitioners to create custom scenarios, simulate interactions, and evaluate the safety and performance of their agents.

[Arxiv](https://arxiv.org/abs/2409.16427)