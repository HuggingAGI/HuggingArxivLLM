# 从实践中汲取经验：LLM代理的记录与回放功能

发布时间：2025年05月23日

`Agent

论文摘要讨论了AI代理的发展，特别是如何利用LLMs和通信协议使代理能够执行复杂任务。它提出了一种新的AgentRR范式，专注于记录和重放机制，以解决代理在任务执行中的挑战。因此，这篇论文主要关注AI代理的开发和应用，属于Agent类别。` `AI代理`

> Get Experience from Practice: LLM Agents with Record & Replay

# 摘要

> AI代理借助LLMs和通信协议（如MCP和A2A）快速从聊天机器人进化为能执行复杂多步骤任务的自主实体，展现出巨大潜力。然而，LLMs的固有不确定性和高计算资源需求为开发安全高效代理带来了四大挑战：可靠性、隐私、成本和性能。现有方法如模型对齐、工作流约束和设备端部署虽能部分缓解问题，但未能根本解决。

本文提出AgentRR（Agent Record & Replay）新范式，将经典记录与重放机制引入AI代理框架。其核心思路包括：1. 记录代理在任务执行中的环境交互轨迹和内部决策过程，2. 将轨迹总结为结构化“经验”以封装工作流和约束，3. 在后续相似任务中重放经验以指导行为。我们详细介绍了AgentRR的多级经验抽象方法和检查函数机制：前者平衡经验的特异性和通用性，后者作为信任基准确保重放过程的完整性和安全性。此外，我们探索了AgentRR的多种应用模式，包括用户记录的任务演示、大小模型协作以及隐私感知的代理执行，并设想了一个经验仓库，用于知识共享和复用以进一步降低成本。

> AI agents, empowered by Large Language Models (LLMs) and communication protocols such as MCP and A2A, have rapidly evolved from simple chatbots to autonomous entities capable of executing complex, multi-step tasks, demonstrating great potential. However, the LLMs' inherent uncertainty and heavy computational resource requirements pose four significant challenges to the development of safe and efficient agents: reliability, privacy, cost and performance. Existing approaches, like model alignment, workflow constraints and on-device model deployment, can partially alleviate some issues but often with limitations, failing to fundamentally resolve these challenges.
  This paper proposes a new paradigm called AgentRR (Agent Record & Replay), which introduces the classical record-and-replay mechanism into AI agent frameworks. The core idea is to: 1. Record an agent's interaction trace with its environment and internal decision process during task execution, 2. Summarize this trace into a structured "experience" encapsulating the workflow and constraints, and 3. Replay these experiences in subsequent similar tasks to guide the agent's behavior. We detail a multi-level experience abstraction method and a check function mechanism in AgentRR: the former balances experience specificity and generality, while the latter serves as a trust anchor to ensure completeness and safety during replay. In addition, we explore multiple application modes of AgentRR, including user-recorded task demonstration, large-small model collaboration and privacy-aware agent execution, and envision an experience repository for sharing and reusing knowledge to further reduce deployment cost.

[Arxiv](https://arxiv.org/abs/2505.17716)