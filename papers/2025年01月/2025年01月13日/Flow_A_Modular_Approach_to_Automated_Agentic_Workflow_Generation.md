# Flow: 模块化智能体工作流自动生成方案

发布时间：2025年01月13日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）驱动的多智能体框架在自动化规划和任务执行中的应用，特别是智能体工作流的动态调整和优化。论文的核心内容围绕多智能体系统的设计和实现，强调了智能体之间的协作、任务分配和工作流优化。因此，这篇论文应归类为Agent。` `自动化` `任务规划`

> Flow: A Modular Approach to Automated Agentic Workflow Generation

# 摘要

> # 摘要
大型语言模型（LLMs）驱动的多智能体框架在自动化规划和任务执行中表现出色。然而，执行过程中智能体工作流的动态调整尚未得到深入研究。有效的工作流调整至关重要，因为现实场景中，初始计划需实时应对突发挑战和变化，以确保复杂任务的高效执行。本文中，我们将工作流定义为顶点活动图（AOV），并通过基于历史性能和先前的AOV与LLM智能体动态调整任务分配，持续优化工作流。为提升系统性能，我们基于并行性和依赖复杂性的测量，强调工作流设计的模块化。我们提出的多智能体框架实现了高效的子任务并发执行、目标达成和容错能力。实证结果表明，通过动态工作流更新和模块化，多智能体框架的效率显著提升。

> Multi-agent frameworks powered by large language models (LLMs) have demonstrated great success in automated planning and task execution. However, the effective adjustment of Agentic workflows during execution has not been well-studied. A effective workflow adjustment is crucial, as in many real-world scenarios, the initial plan must adjust to unforeseen challenges and changing conditions in real-time to ensure the efficient execution of complex tasks. In this paper, we define workflows as an activity-on-vertex (AOV) graphs. We continuously refine the workflow by dynamically adjusting task allocations based on historical performance and previous AOV with LLM agents. To further enhance system performance, we emphasize modularity in workflow design based on measuring parallelism and dependence complexity. Our proposed multi-agent framework achieved efficient sub-task concurrent execution, goal achievement, and error tolerance. Empirical results across different practical tasks demonstrate dramatic improvements in the efficiency of multi-agent frameworks through dynamic workflow updating and modularization.

[Arxiv](https://arxiv.org/abs/2501.07834)