# 奖励“不可能”：突破分布锐化，提升 GRPO 性能

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Rewarding the Unlikely: Lifting GRPO Beyond Distribution Sharpening

# 摘要

> 强化学习已成为训练大型语言模型在结构化语言条件任务上的有效框架。我们发现了一种广泛应用于此场景的强化学习算法——组相对策略优化（GRPO）的关键缺陷。对于需要多样本性能的任务，例如形式化定理证明，GRPO倾向于强化已有的高概率解，而忽视了稀有但正确的证明。这种隐式偏差在大样本量下会损害pass@$N$指标的性能，限制了其在训练定理证明器方面的实用性。为了解决这一问题，我们引入了不相似奖励（unlikeliness reward），这是一种简单直接的方法，旨在明确鼓励强化稀有正确的解。此外，我们发现增加PPO迭代次数可以进一步缓解这一偏差。我们的实验表明，加入不相似奖励显著提高了pass@$N$在N的广泛范围内的表现，超越了标准GRPO，并大幅提升了样本多样性。将我们的改进方案应用于Lean，我们在miniF2F-test基准测试中达到了与DeepSeek-Prover-V1.5-RL相媲美的性能。我们公开了我们的实现，提供了一个简单而有效的强化学习训练形式化定理证明器的方案。


> Reinforcement learning has emerged as an effective framework for training large language models on structured language-conditioned tasks. We identify a critical flaw of Group Relative Policy Optimization (GRPO), a widely used RL algorithm in this setting. For tasks that require multi-sample performance, such as formal theorem proving, GRPO biasedly reinforces already probable solutions and neglects rare but correct proofs. This implicit bias impairs performance on pass@$N$ metrics at large sample sizes, limiting its practicality for training theorem provers. To address this, we introduce the unlikeliness reward, a straightforward method that explicitly encourages reinforcing rare correct solutions. Additionally, we find that increasing the number of PPO epochs further mitigates this bias. Our experiments confirm that incorporating the unlikeliness reward significantly improves pass@$N$ across a large range of N, outperforming standard GRPO and substantially increasing sample diversity. Applying our revised recipe to Lean, we achieve competitive performance with DeepSeek-Prover-V1.5-RL on the miniF2F-test benchmark. We release our implementation, providing a simple yet effective recipe for training formal theorem provers with RL.

[Arxiv](https://arxiv.org/abs/2506.02355)