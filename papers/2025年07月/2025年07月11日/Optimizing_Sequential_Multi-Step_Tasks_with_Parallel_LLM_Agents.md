# # 优化顺序多步骤任务：并行LLM代理的新方法

发布时间：2025年07月11日

`Agent` `多智能体系统` `系统优化`

> Optimizing Sequential Multi-Step Tasks with Parallel LLM Agents

# 摘要

> 基于大型语言模型（LLM）的多智能体系统在处理复杂任务时展现出非凡的潜力，它们通过分解任务为子任务并进行迭代规划、执行、观察和优化来实现这一目标。然而，尽管这些系统表现出色，但现实世界的问题往往需要多个迭代周期的推理步骤，导致系统常常面临高延迟问题。为了解决这一挑战，我们提出了一种名为M1-Parallel的框架，该框架能够并行运行多个多智能体团队，以探索不同的解决方案路径。通过采用基于事件驱动的通信模型和异步消息传递，M1-Parallel能够有效利用有效计划的内在多样性，从而降低端到端延迟或提高任务完成率。我们在复杂任务上的实验表明，带有早期终止的M1-Parallel可实现高达【数学公式】的速度提升，同时保持准确性；而带有聚合的M1-Parallel则能实现更高的任务完成率。我们进一步研究了鼓励多样化执行计划的策略，但发现与重复采样相比并未带来额外的性能提升。总体而言，这些发现凸显了并行计划执行在优化多智能体系统以应对现实世界复杂推理任务中的潜力。

> Large language model (LLM)-based multi-agent systems have demonstrated remarkable promise for tackling complex tasks by breaking them down into subtasks that are iteratively planned, executed, observed, and refined. Despite their effectiveness, these systems often incur high latency because real-world problems frequently demand multiple iterative cycles of reasoning steps. To address this challenge, we propose M1-Parallel, a framework that concurrently runs multiple multi-agent teams in parallel to uncover distinct solution paths. By leveraging an event-driven communication model with asynchronous messaging, M1-Parallel efficiently capitalizes on the inherent diversity of valid plans to either reduce end-to-end latency or boost task completion rates. Our experiments on complex tasks show that M1-Parallel with early termination achieves up to $2.2\times$ speedup while preserving accuracy, and that M1-Parallel with aggregation yields higher task completion rates. We further investigate strategies aimed at encouraging diverse execution plans but observe no additional performance gains over repeated sampling. Overall, these findings underscore the potential of parallel plan execution for optimizing multi-agent systems for real-world, high-complexity reasoning tasks.

[Arxiv](https://arxiv.org/abs/2507.08944)