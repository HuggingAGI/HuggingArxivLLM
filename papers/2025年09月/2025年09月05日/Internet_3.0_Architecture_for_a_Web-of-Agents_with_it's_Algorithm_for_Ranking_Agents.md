# 互联网3.0：智能体网络架构及其智能体排序算法

发布时间：2025年09月05日

`Agent` `基础理论`

> Internet 3.0: Architecture for a Web-of-Agents with it's Algorithm for Ranking Agents

# 摘要

> AI 智能体——借助具备推理能力的大型语言模型（LLMs）驱动，并整合了工具、数据与网络搜索功能——正推动互联网向\emph{智能体网络}转型：这是一个机器原生的生态系统，自主智能体可在此大规模交互、协作并执行任务。要实现这一愿景，\emph{智能体排名}至关重要——选择智能体时，不仅要看其宣称的能力，更要依据其已验证的近期表现。与 Web 1.0 的 PageRank 不同，当前缺乏全局透明的智能体交互网络，使用信号分散且私密，若无协调，排名便无从谈起。
  为此，我们提出	extbf{DOVIS}——一种五层操作协议（\emph{发现、编排、验证、激励、语义}），它能收集生态系统中最小化且隐私保护的使用与性能聚合数据。基于此，我们开发了	extbf{AgentRank-UC}，这是一种动态、信任感知的算法，可将使用情况（选择频率）与能力表现（结果质量、成本、安全性、延迟）整合为统一排名。我们通过模拟结果及关于收敛性、鲁棒性和抗女巫攻击的理论保证，证实了协调协议与性能感知排名在构建可扩展、可信智能体网络中的可行性。

> AI agents -- powered by reasoning-capable large language models (LLMs) and integrated with tools, data, and web search -- are poised to transform the internet into a \emph{Web of Agents}: a machine-native ecosystem where autonomous agents interact, collaborate, and execute tasks at scale. Realizing this vision requires \emph{Agent Ranking} -- selecting agents not only by declared capabilities but by proven, recent performance. Unlike Web~1.0's PageRank, a global, transparent network of agent interactions does not exist; usage signals are fragmented and private, making ranking infeasible without coordination.
  We propose \textbf{DOVIS}, a five-layer operational protocol (\emph{Discovery, Orchestration, Verification, Incentives, Semantics}) that enables the collection of minimal, privacy-preserving aggregates of usage and performance across the ecosystem. On this substrate, we implement \textbf{AgentRank-UC}, a dynamic, trust-aware algorithm that combines \emph{usage} (selection frequency) and \emph{competence} (outcome quality, cost, safety, latency) into a unified ranking. We present simulation results and theoretical guarantees on convergence, robustness, and Sybil resistance, demonstrating the viability of coordinated protocols and performance-aware ranking in enabling a scalable, trustworthy Agentic Web.

[Arxiv](https://arxiv.org/abs/2509.04979)