# Dynamic ReAct：大规模MCP环境中的可扩展工具选择

发布时间：2025年09月22日

`Agent` `基础理论`

> Dynamic ReAct: Scalable Tool Selection for Large-Scale MCP Environments

# 摘要

> 我们提出Dynamic ReAct——一种新颖方法，旨在让ReAct智能体高效使用规模庞大的模型控制协议（MCP）工具集，这些工具集已超出大型语言模型的上下文记忆容量。该方法解决了核心难题：在存在数百甚至数千种可用工具的环境中，同时加载所有工具计算上难以实现，而工具选择正是关键挑战。我们提出并评估了五种不同架构，它们逐步完善工具选择流程，最终构建出一种搜索-加载机制，能以极低的计算开销实现智能工具选择。实验结果显示，该方法在保证任务完成精度的同时，工具加载量减少高达50%，为打造能动态适应多样任务环境的真正通用人工智能智能体迈出了重要一步。

> We present Dynamic ReAct, a novel approach for enabling ReAct agents to ef- ficiently operate with extensive Model Control Protocol (MCP) tool sets that exceed the contextual memory limitations of large language models. Our approach addresses the fundamental challenge of tool selection in environments containing hundreds or thousands of available tools, where loading all tools simultaneously is computationally infeasible. We propose and evaluate five distinct architectures that progressively refine the tool selection process, culminating in a search-and-load mechanism that achieves intelligent tool selection with minimal computational overhead. Our experimental results demonstrate that the proposed approach reduces tool loading by up to 50% while maintaining task completion accuracy, advancing the path towards truly general-purpose AI agents capable of dynamically adapting to diverse task environments.

[Arxiv](https://arxiv.org/abs/2509.20386)