# MultiAgentBench：评估LLM智能体间的协作与竞争

发布时间：2025年03月03日

`Agent` `多智能体系统` `交互智能`

> MultiAgentBench: Evaluating the Collaboration and Competition of LLM agents

# 摘要

> 大型语言模型（LLMs）作为自主代理展现出了非凡的能力，但现有基准测试或专注于单智能体任务，或局限于狭窄领域，未能捕捉多智能体协调与竞争的动态。本文引入MultiAgentBench，一个全面的基准测试框架，旨在评估基于LLMs的多智能体系统在各种交互场景中的表现。我们的框架不仅衡量任务完成情况，还通过基于里程碑的关键性能指标评估协作与竞争的质量。此外，我们评估了多种协调协议（包括星型、链式、树状和图结构）以及创新策略，如群体讨论和认知规划。值得注意的是，gpt-4o-mini在任务得分中表现最佳，在研究场景中，图结构在协调协议中表现最优，而认知规划将里程碑达成率提升了3%。代码和数据集可在https://github.com/MultiagentBench/MARBLE公开获取。

> Large Language Models (LLMs) have shown remarkable capabilities as autonomous agents, yet existing benchmarks either focus on single-agent tasks or are confined to narrow domains, failing to capture the dynamics of multi-agent coordination and competition. In this paper, we introduce MultiAgentBench, a comprehensive benchmark designed to evaluate LLM-based multi-agent systems across diverse, interactive scenarios. Our framework measures not only task completion but also the quality of collaboration and competition using novel, milestone-based key performance indicators. Moreover, we evaluate various coordination protocols (including star, chain, tree, and graph topologies) and innovative strategies such as group discussion and cognitive planning. Notably, gpt-4o-mini reaches the average highest task score, graph structure performs the best among coordination protocols in the research scenario, and cognitive planning improves milestone achievement rates by 3%. Code and datasets are public available at https://github.com/MultiagentBench/MARBLE.

[Arxiv](https://arxiv.org/abs/2503.01935)