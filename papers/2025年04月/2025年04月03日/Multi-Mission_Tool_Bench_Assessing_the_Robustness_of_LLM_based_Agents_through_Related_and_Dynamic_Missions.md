# 多任务工具基准平台：借助相关动态任务评估LLM代理的鲁棒性表现

发布时间：2025年04月03日

`Agent` `工具调用` `多任务处理`

> Multi-Mission Tool Bench: Assessing the Robustness of LLM based Agents through Related and Dynamic Missions

# 摘要

> 大型语言模型（LLMs）凭借其卓越的理解与规划能力，展现出作为工具调用代理的巨大潜力。越来越多的用户依赖这些基于LLMs的代理，通过反复交互解决复杂问题。然而，现有的基准测试大多局限于单一任务场景，难以反映现实中的复杂性。为解决这一问题，我们提出了Multi-Mission Tool Bench。在这个基准中，每个测试案例包含多个相互关联的任务，要求代理能够动态适应不断变化的需求。此外，该基准在固定任务数量内探索所有可能的任务切换模式。具体而言，我们提出了一种多代理数据生成框架来构建该基准，并引入了一种新的方法，利用动态决策树来评估代理决策的准确性和效率。在多种开源和闭源LLMs上的实验结果揭示了影响代理鲁棒性的关键因素，并为工具调用领域提供了宝贵的实践见解。

> Large language models (LLMs) demonstrate strong potential as agents for tool invocation due to their advanced comprehension and planning capabilities. Users increasingly rely on LLM-based agents to solve complex missions through iterative interactions. However, existing benchmarks predominantly access agents in single-mission scenarios, failing to capture real-world complexity. To bridge this gap, we propose the Multi-Mission Tool Bench. In the benchmark, each test case comprises multiple interrelated missions. This design requires agents to dynamically adapt to evolving demands. Moreover, the proposed benchmark explores all possible mission-switching patterns within a fixed mission number. Specifically, we propose a multi-agent data generation framework to construct the benchmark. We also propose a novel method to evaluate the accuracy and efficiency of agent decisions with dynamic decision trees. Experiments on diverse open-source and closed-source LLMs reveal critical factors influencing agent robustness and provide actionable insights to the tool invocation society.

[Arxiv](https://arxiv.org/abs/2504.02623)