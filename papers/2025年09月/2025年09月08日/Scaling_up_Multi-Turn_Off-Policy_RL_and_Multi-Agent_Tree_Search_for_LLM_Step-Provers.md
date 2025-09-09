# 面向LLM分步证明器的多轮离线策略强化学习与多智能体树搜索扩展

发布时间：2025年09月08日

`强化学习` `基础理论`

> Scaling up Multi-Turn Off-Policy RL and Multi-Agent Tree Search for LLM Step-Provers

# 摘要

> 大型语言模型（LLMs）与自动定理证明的融合展现出巨大潜力，但从根本上受限于训练时强化学习（RL）和推理时计算的双重扩展难题。本文推出	exttt{BFS-Prover-V2}系统，专门应对这一挑战，并带来两项核心创新。第一项创新是一种新颖的多轮离线强化学习框架，旨在训练阶段持续提升LLM分步证明器的性能。该框架借鉴AlphaZero的核心原理，构建多阶段专家迭代流水线，通过自适应策略级数据过滤与周期性重训练机制，有效突破了基于LLM的智能体在长期强化学习中常遇到的性能瓶颈。第二项创新是规划器增强的多智能体搜索架构，专注于在推理阶段提升推理能力的扩展性。该架构引入通用推理模型作为高层规划器，通过迭代将复杂定理分解为一系列简单子目标。这种分层策略显著缩小了搜索空间，使得多个并行证明智能体能够借助共享证明缓存实现高效协作。实验表明，这种双重扩展方案在主流形式化数学基准测试中表现卓越：	exttt{BFS-Prover-V2}在MiniF2F和ProofNet测试集上的准确率分别达到95.08%和41.4%。尽管本文在形式化数学领域验证了相关技术，但所提出的强化学习与推理方法具有更广泛的适用性，有望应用于其他需要长程多轮推理和复杂搜索的领域。

> The integration of Large Language Models (LLMs) into automated theorem proving has shown immense promise, yet is fundamentally constrained by challenges in scaling up both training-time reinforcement learning (RL) and inference-time compute. This paper introduces \texttt{BFS-Prover-V2}, a system designed to address this dual scaling problem. We present two primary innovations. The first is a novel multi-turn off-policy RL framework for continually improving the performance of LLM step-prover at training time. This framework, inspired by the principles of AlphaZero, utilizes a multi-stage expert iteration pipeline featuring adaptive tactic-level data filtering and periodic retraining to surmount the performance plateaus that typically curtail long-term RL in LLM-based agents. The second innovation is a planner-enhanced multi-agent search architecture that scales reasoning capabilities at inference time. This architecture employs a general reasoning model as a high-level planner to iteratively decompose complex theorems into a sequence of simpler subgoals. This hierarchical approach substantially reduces the search space, enabling a team of parallel prover agents to collaborate efficiently by leveraging a shared proof cache. We demonstrate that this dual approach to scaling yields state-of-the-art results on established formal mathematics benchmarks. \texttt{BFS-Prover-V2} achieves 95.08\% and 41.4\% on the MiniF2F and ProofNet test sets respectively. While demonstrated in the domain of formal mathematics, the RL and inference techniques presented in this work are of broader interest and may be applied to other domains requiring long-horizon multi-turn reasoning and complex search.

[Arxiv](https://arxiv.org/abs/2509.06493)