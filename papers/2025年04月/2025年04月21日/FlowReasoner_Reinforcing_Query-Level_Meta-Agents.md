# FlowReasoner：强化查询级元代理

发布时间：2025年04月21日

`Agent

摘要中提到的FlowReasoner是一种元代理，专注于设计和优化多智能体系统。它使用强化学习和奖励函数来提升性能，属于智能体设计和优化的范畴，因此归类为Agent。` `人工智能` `系统设计`

> FlowReasoner: Reinforcing Query-Level Meta-Agents

# 摘要

> 本文提出了一种名为FlowReasoner的查询级元代理，旨在为每个用户查询自动化设计相应的多智能体系统。我们的核心思路是通过外部执行反馈来激励基于推理的元代理。具体而言，通过对DeepSeek R1进行蒸馏，我们首先赋予FlowReasoner生成多智能体系统的基本推理能力。随后，我们通过基于外部执行反馈的强化学习（RL）进一步提升其能力。设计了一个多用途奖励函数，从性能、复杂性和效率三个方面引导RL训练。以此方式，FlowReasoner能够通过审慎推理为每个用户查询生成个性化的多智能体系统。在工程和竞赛代码基准上的实验结果证明了FlowReasoner的优越性。值得注意的是，它在三个基准上比o1-mini高出10.52%的准确率。代码可在https://github.com/sail-sg/FlowReasoner获取。

> This paper proposes a query-level meta-agent named FlowReasoner to automate the design of query-level multi-agent systems, i.e., one system per user query. Our core idea is to incentivize a reasoning-based meta-agent via external execution feedback. Concretely, by distilling DeepSeek R1, we first endow the basic reasoning ability regarding the generation of multi-agent systems to FlowReasoner. Then, we further enhance it via reinforcement learning (RL) with external execution feedback. A multi-purpose reward is designed to guide the RL training from aspects of performance, complexity, and efficiency. In this manner, FlowReasoner is enabled to generate a personalized multi-agent system for each user query via deliberative reasoning. Experiments on both engineering and competition code benchmarks demonstrate the superiority of FlowReasoner. Remarkably, it surpasses o1-mini by 10.52% accuracy across three benchmarks. The code is available at https://github.com/sail-sg/FlowReasoner.

[Arxiv](https://arxiv.org/abs/2504.15257)