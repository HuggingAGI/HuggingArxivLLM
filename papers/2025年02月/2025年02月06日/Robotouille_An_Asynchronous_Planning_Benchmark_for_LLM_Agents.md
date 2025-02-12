# Robotouille：面向 LLM 代理的异步规划基准

发布时间：2025年02月06日

`Agent` `机器人` `智能体`

> Robotouille: An Asynchronous Planning Benchmark for LLM Agents

# 摘要

> 要让智能体在考虑时间延迟、处理多样化长周期任务以及与其他智能体协作时表现出色，必须具备有效的异步规划能力，即能够高效地对必须并行或顺序进行的状态和动作进行推理和规划。虽然大型语言模型（LLM）智能体在高层次任务规划方面显示出潜力，但现有的基准测试主要关注短周期任务，未能评估其在异步规划方面的能力。我们推出了Robotouille，这是一个极具挑战性的基准测试环境，专为评估LLM智能体在处理长周期异步场景时的能力而设计。我们的同步和异步数据集涵盖了超越现有基准的日益复杂的规划挑战，要求智能体不仅要处理重叠任务，还要应对各种中断。实验结果显示，ReAct（gpt4-o）在同步任务中达到了47%的性能，但在异步任务中仅达到11%，这表明现有模型在异步规划方面仍有巨大提升空间。我们进一步分析了失败模式，证明了LLM智能体在任务执行过程中需要更好地整合长周期反馈和自我审核推理。相关代码已开源，地址为https://github.com/portal-cornell/robotouille。

> Effective asynchronous planning, or the ability to efficiently reason and plan over states and actions that must happen in parallel or sequentially, is essential for agents that must account for time delays, reason over diverse long-horizon tasks, and collaborate with other agents. While large language model (LLM) agents show promise in high-level task planning, current benchmarks focus primarily on short-horizon tasks and do not evaluate such asynchronous planning capabilities. We introduce Robotouille, a challenging benchmark environment designed to test LLM agents' ability to handle long-horizon asynchronous scenarios. Our synchronous and asynchronous datasets capture increasingly complex planning challenges that go beyond existing benchmarks, requiring agents to manage overlapping tasks and interruptions. Our results show that ReAct (gpt4-o) achieves 47% on synchronous tasks but only 11% on asynchronous tasks, highlighting significant room for improvement. We further analyze failure modes, demonstrating the need for LLM agents to better incorporate long-horizon feedback and self-audit their reasoning during task execution. Code is available at https://github.com/portal-cornell/robotouille.

[Arxiv](https://arxiv.org/abs/2502.05227)