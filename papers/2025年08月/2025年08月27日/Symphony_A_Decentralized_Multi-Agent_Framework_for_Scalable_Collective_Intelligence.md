# Symphony：面向可扩展集体智能的去中心化多智能体框架

发布时间：2025年08月27日

`Agent` `基础理论`

> Symphony: A Decentralized Multi-Agent Framework for Scalable Collective Intelligence

# 摘要

> 目前大多数基于大型语言模型（LLM）的智能体框架都采用集中式编排，这带来了部署成本高昂、通信拓扑僵化以及适应性受限等问题。为应对这些挑战，我们推出了Symphony——一个去中心化多智能体系统，它能让消费级GPU上的轻量级LLM实现高效协同。Symphony引入了三大核心机制：（1）记录能力的去中心化账本；（2）用于动态任务分配的信标选择协议；（3）基于思维链（CoTs）的加权结果投票机制。这种设计打造出一种兼具隐私保护、可扩展性、容错能力且低开销的编排方案。实证研究显示，Symphony在推理基准测试中性能超越现有基线，不仅准确率大幅提升，在不同能力的模型上也都展现出优异的稳健性。

> Most existing Large Language Model (LLM)-based agent frameworks rely on centralized orchestration, incurring high deployment costs, rigid communication topologies, and limited adaptability. To address these challenges, we introduce Symphony, a decentralized multi-agent system which enables lightweight LLMs on consumer-grade GPUs to coordinate. Symphony introduces three key mechanisms: (1) a decentralized ledger that records capabilities, (2) a Beacon-selection protocol for dynamic task allocation, and (3) weighted result voting based on CoTs. This design forms a privacy-saving, scalable, and fault-tolerant orchestration with low overhead. Empirically, Symphony outperforms existing baselines on reasoning benchmarks, achieving substantial accuracy gains and demonstrating robustness across models of varying capacities.

[Arxiv](https://arxiv.org/abs/2508.20019)