# RRO: 利用递增奖励轨迹优化 LLM 智能体

发布时间：2025年05月27日

`Agent` `人工智能` `软件工程`

> RRO: LLM Agent Optimization Through Rising Reward Trajectories

# 摘要

> 大型语言模型（LLMs）在多种任务中展现出非凡的能力，但在解决复杂多步骤任务时仍面临挑战。实际中，智能体对某些关键步骤的结果敏感，微小的规划错误可能导致任务失败。近期研究通过强化学习校准推理过程，对每一步推理给予奖励或惩罚，即过程奖励模型（PRMs）。然而，PRMs在扩展到大量候选动作时计算成本高昂。为此，我们提出关注连续推理步骤中的奖励趋势，保持奖励递增，称为奖励递增优化（RRO）。我们逐步增强过程监督，识别奖励递增的步骤，动态扩展搜索空间，高效捕获高质量数据。我们在WebShop和InterCode-SQL基准上验证了RRO的优越性能，同时显著降低了探索成本。

> Large language models (LLMs) have exhibited extraordinary performance in a variety of tasks while it remains challenging for them to solve complex multi-step tasks as agents. In practice, agents sensitive to the outcome of certain key steps which makes them likely to fail the task because of a subtle mistake in the planning trajectory. Recent approaches resort to calibrating the reasoning process through reinforcement learning. They reward or penalize every reasoning step with process supervision, as known as Process Reward Models (PRMs). However, PRMs are difficult and costly to scale up with a large number of next action candidates since they require extensive computations to acquire the training data through the per-step trajectory exploration. To mitigate this issue, we focus on the relative reward trend across successive reasoning steps and propose maintaining an increasing reward in the collected trajectories for process supervision, which we term Reward Rising Optimization (RRO). Specifically, we incrementally augment the process supervision until identifying a step exhibiting positive reward differentials, i.e. rising rewards, relative to its preceding iteration. This method dynamically expands the search space for the next action candidates, efficiently capturing high-quality data. We provide mathematical groundings and empirical results on the WebShop and InterCode-SQL benchmarks, showing that our proposed RRO achieves superior performance while requiring much less exploration cost.

[Arxiv](https://arxiv.org/abs/2505.20737)