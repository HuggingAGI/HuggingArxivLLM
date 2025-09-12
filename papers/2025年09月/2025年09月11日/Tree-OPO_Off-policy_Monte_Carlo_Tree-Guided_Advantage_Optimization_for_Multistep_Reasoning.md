# Tree-OPO：用于多步推理的离策略蒙特卡洛树引导优势优化

发布时间：2025年09月11日

`强化学习` `基础理论`

> Tree-OPO: Off-policy Monte Carlo Tree-Guided Advantage Optimization for Multistep Reasoning

# 摘要

> 大型语言模型（LLMs）在推理领域的最新进展显示，蒙特卡洛树搜索（MCTS）能有效生成高质量中间轨迹，尤其在数学和符号领域表现突出。受此启发，我们研究了传统用于训练价值或奖励模型的MCTS生成轨迹如何被重新赋能，以提升基于偏好的强化学习（RL）中的策略优化效果。具体来说，我们聚焦于组相对策略优化（GRPO）——一种无需价值网络即可实现偏好一致策略学习的最新算法。我们提出了一种分阶段GRPO训练范式，该范式通过部分揭示的MCTS展开生成补全内容，为优势估计构建了新颖的树状结构场景。这一过程生成了丰富的前缀条件奖励信号，我们对其进行了理论与实证双重分析。初步结果显示，结构化优势估计虽能稳定更新并更精准地反映组合推理质量，但仍面临优势饱和与奖励信号崩溃等问题。为此，我们提出启发式与统计解决方案以缓解这些问题，并探讨了在分阶段或树状奖励结构下学习的开放性挑战。

> Recent advances in reasoning with large language models (LLMs) have shown the effectiveness of Monte Carlo Tree Search (MCTS) for generating high-quality intermediate trajectories, particularly in math and symbolic domains. Inspired by this, we explore how MCTS-derived trajectories, traditionally used for training value or reward models, can be repurposed to improve policy optimization in preference-based reinforcement learning (RL). Specifically, we focus on Group Relative Policy Optimization (GRPO), a recent algorithm that enables preference-consistent policy learning without value networks. We propose a staged GRPO training paradigm where completions are derived from partially revealed MCTS rollouts, introducing a novel tree-structured setting for advantage estimation. This leads to a rich class of prefix-conditioned reward signals, which we analyze theoretically and empirically. Our initial results indicate that while structured advantage estimation can stabilize updates and better reflect compositional reasoning quality, challenges such as advantage saturation and reward signal collapse remain. We propose heuristic and statistical solutions to mitigate these issues and discuss open challenges for learning under staged or tree-like reward structures.

[Arxiv](https://arxiv.org/abs/2509.09284)