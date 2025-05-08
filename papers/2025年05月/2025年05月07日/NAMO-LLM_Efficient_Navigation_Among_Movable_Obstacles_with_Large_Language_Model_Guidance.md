# NAMO-LLM：借助大型语言模型实现可移动障碍物间的高效导航

发布时间：2025年05月07日

`Agent

理由：这篇论文专注于机器人路径规划问题，特别是当机器人需要重新配置环境以导航时。虽然它使用了大型语言模型（LLM）作为工具来辅助规划过程，但论文的核心主题是机器人如何通过推理和重新配置环境来解决导航问题。因此，它更符合Agent类别，因为它涉及机器人智能体的行为和决策。` `机器人学` `自主导航`

> NAMO-LLM: Efficient Navigation Among Movable Obstacles with Large Language Model Guidance

# 摘要

> 在机器人路径规划问题中，已有多种方法能够计算出避开障碍物并到达目标区域的路径。然而，当所有通向目标的路径都被阻挡时，现有方法将无法奏效。此时，机器人需要推理如何通过重新配置环境来访问任务相关区域——这一问题被称为可移动障碍物中的导航（NAMO）。尽管针对此问题已有多种解决方案，但它们往往难以应对高度杂乱的场景。为了解决这一挑战，我们提出了NAMO-LLM，这是一种基于采样的规划器，通过搜索机器人和障碍物的配置来计算可行计划，明确需要移动哪些障碍物、移动到何处以及移动顺序。其核心创新在于引入了一种由大型语言模型（LLMs）引导的非均匀采样策略，使规划过程更倾向于探索更可能找到解决方案的方向。我们证明了NAMO-LLM在概率上是完整的，并通过实验验证了它能够高效地处理杂乱环境，无论是在运行时间还是计划质量方面，均显著优于现有方法。

> Several planners have been proposed to compute robot paths that reach desired goal regions while avoiding obstacles. However, these methods fail when all pathways to the goal are blocked. In such cases, the robot must reason about how to reconfigure the environment to access task-relevant regions - a problem known as Navigation Among Movable Objects (NAMO). While various solutions to this problem have been developed, they often struggle to scale to highly cluttered environments. To address this, we propose NAMO-LLM, a sampling-based planner that searches over robot and obstacle configurations to compute feasible plans specifying which obstacles to move, where, and in what order. Its key novelty is a non-uniform sampling strategy guided by Large Language Models (LLMs) biasing the tree construction toward directions more likely to yield a solution. We show that NAMO-LLM is probabilistically complete and demonstrate through experiments that it efficiently scales to cluttered environments, outperforming related works in both runtime and plan quality.

[Arxiv](https://arxiv.org/abs/2505.04141)