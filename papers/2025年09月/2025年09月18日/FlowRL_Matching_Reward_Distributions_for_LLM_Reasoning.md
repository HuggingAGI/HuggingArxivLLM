# FlowRL：面向LLM推理的奖励分布匹配

发布时间：2025年09月18日

`强化学习` `基础理论`

> FlowRL: Matching Reward Distributions for LLM Reasoning

# 摘要

> 我们提出FlowRL：在大型语言模型（LLM）强化学习（RL）中不再追求奖励最大化，而是通过流平衡来匹配完整的奖励分布。当前主流的先进推理模型多采用奖励最大化方法（如PPO、GRPO），这类方法往往过度优化主导奖励信号，却忽略了那些虽不常见但有效的推理路径，导致多样性下降。与之不同，我们借助可学习的配分函数将标量奖励转化为归一化的目标分布，再最小化策略与目标分布间的反向KL散度。我们将这一思路转化为流平衡优化方法，以促进多样化探索和具备泛化能力的推理轨迹。我们在数学和代码推理任务上开展实验：在数学基准测试中，FlowRL相比GRPO平均显著提升[数学公式]，较PPO平均显著提升[数学公式]；在代码推理任务上，其表现也持续更优。这些结果表明，奖励分布匹配是LLM强化学习中实现高效探索与多样化推理的关键一环。

> We propose FlowRL: matching the full reward distribution via flow balancing instead of maximizing rewards in large language model (LLM) reinforcement learning (RL). Recent advanced reasoning models adopt reward-maximizing methods (\eg, PPO and GRPO), which tend to over-optimize dominant reward signals while neglecting less frequent but valid reasoning paths, thus reducing diversity. In contrast, we transform scalar rewards into a normalized target distribution using a learnable partition function, and then minimize the reverse KL divergence between the policy and the target distribution. We implement this idea as a flow-balanced optimization method that promotes diverse exploration and generalizable reasoning trajectories. We conduct experiments on math and code reasoning tasks: FlowRL achieves a significant average improvement of $10.0\%$ over GRPO and $5.1\%$ over PPO on math benchmarks, and performs consistently better on code reasoning tasks. These results highlight reward distribution-matching as a key step toward efficient exploration and diverse reasoning in LLM reinforcement learning.

[Arxiv](https://arxiv.org/abs/2509.15207)