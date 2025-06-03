# COALESCE：团队中自主LLM代理基于技能的任务外包经济与安全动态

发布时间：2025年06月02日

`Agent` `资源管理` `市场机制`

> COALESCE: Economic and Security Dynamics of Skill-Based Task Outsourcing Among Team of Autonomous LLM Agents

# 摘要

> # 摘要
大型语言模型（LLM）代理的迅猛崛起和广泛应用，为各个领域带来了巨大潜力。然而，随着对计算资源尤其是图形处理器（GPU）需求的激增，其部署正面临越来越大的限制。本文聚焦于解决大型语言模型代理系统中资源利用率优化这一关键问题。

我们提出了COALESCE框架，该框架旨在让自主LLM代理能够动态地将特定子任务外包给专业化、成本效益高的第三方LLM代理。COALESCE整合了混合技能表示、动态技能发现、自动化任务分解、统一成本模型（用于比较内部执行成本与外部外包价格）、简化的市场决策算法以及标准化的代理间通信协议。

通过239次理论模拟的全面验证，我们发现COALESCE具有41.8%的成本削减潜力；而在240个真实LLM任务上的大规模实证验证表明，通过适当配置epsilon-greedy探索策略，COALESCE可实现20.3%的成本节省，充分证明了其理论可行性和实际有效性。

Google的Agent2Agent（A2A）协议等开放标准的出现，进一步凸显了像COALESCE这样的框架的重要性，这些框架能够利用此类标准实现高效代理交互。通过构建动态能力市场，利用A2A等协议实现通信，COALESCE的目标是大幅降低运营成本、提升系统扩展性，并促进专业化代理经济的形成，使复杂的LLM代理功能更加触手可及且经济可行。

> The meteoric rise and proliferation of autonomous Large Language Model (LLM) agents promise significant capabilities across various domains. However, their deployment is increasingly constrained by substantial computational demands, specifically for Graphics Processing Unit (GPU) resources. This paper addresses the critical problem of optimizing resource utilization in LLM agent systems. We introduce COALESCE (Cost-Optimized and Secure Agent Labour Exchange via Skill-based Competence Estimation), a novel framework designed to enable autonomous LLM agents to dynamically outsource specific subtasks to specialized, cost-effective third-party LLM agents. The framework integrates mechanisms for hybrid skill representation, dynamic skill discovery, automated task decomposition, a unified cost model comparing internal execution costs against external outsourcing prices, simplified market-based decision-making algorithms, and a standardized communication protocol between LLM agents. Comprehensive validation through 239 theoretical simulations demonstrates 41.8\% cost reduction potential, while large-scale empirical validation across 240 real LLM tasks confirms 20.3\% cost reduction with proper epsilon-greedy exploration, establishing both theoretical viability and practical effectiveness. The emergence of proposed open standards like Google's Agent2Agent (A2A) protocol further underscores the need for frameworks like COALESCE that can leverage such standards for efficient agent interaction. By facilitating a dynamic market for agent capabilities, potentially utilizing protocols like A2A for communication, COALESCE aims to significantly reduce operational costs, enhance system scalability, and foster the emergence of specialized agent economies, making complex LLM agent functionalities more accessible and economically viable.

[Arxiv](https://arxiv.org/abs/2506.01900)