# 利用最优优势回归加速强化学习在大语言模型推理中的应用

发布时间：2025年05月26日

`LLM理论

摘要讨论了强化学习在优化大型语言模型推理能力中的应用，提出了一种新的策略优化框架，并提供了理论分析和实验结果，属于LLM的理论研究。`

> Accelerating RL for LLM Reasoning with Optimal Advantage Regression

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）复杂推理能力方面表现出巨大潜力。然而，现有策略优化方法的高计算开销和内存消耗问题亟待解决，主要源于每个提示需多次生成及对批评网络或优势估计的依赖。为此，我们提出了一种名为$A$*-PO的创新两阶段策略优化框架，通过直接逼近最优优势函数，为推理任务的LLMs训练提供高效解决方案。在第一阶段，我们借助参考策略的离线采样，成功估计了最优价值函数$V$*，从而避免了昂贵的在线价值估计。第二阶段则采用简单的最小二乘回归损失，仅需每个提示一次生成即可完成策略更新。理论分析表明，$A$*-PO不仅建立了性能保证，还证明了KL正则化强化学习目标可在无需复杂探索策略的情况下实现优化。实验结果进一步验证了$A$*-PO的卓越性能：在广泛使用的数学推理基准测试中，其表现优于PPO、GRPO和REBEL，同时将训练时间缩短至原来的1/2，峰值内存使用量降低30%以上。更多细节可访问我们的GitHub仓库：https://github.com/ZhaolinGao/A-PO。

> Reinforcement learning (RL) has emerged as a powerful tool for fine-tuning large language models (LLMs) to improve complex reasoning abilities. However, state-of-the-art policy optimization methods often suffer from high computational overhead and memory consumption, primarily due to the need for multiple generations per prompt and the reliance on critic networks or advantage estimates of the current policy. In this paper, we propose $A$*-PO, a novel two-stage policy optimization framework that directly approximates the optimal advantage function and enables efficient training of LLMs for reasoning tasks. In the first stage, we leverage offline sampling from a reference policy to estimate the optimal value function $V$*, eliminating the need for costly online value estimation. In the second stage, we perform on-policy updates using a simple least-squares regression loss with only a single generation per prompt. Theoretically, we establish performance guarantees and prove that the KL-regularized RL objective can be optimized without requiring complex exploration strategies. Empirically, $A$*-PO achieves competitive performance across a wide range of mathematical reasoning benchmarks, while reducing training time by up to 2$\times$ and peak memory usage by over 30% compared to PPO, GRPO, and REBEL. Implementation of $A$*-PO can be found at https://github.com/ZhaolinGao/A-PO.

[Arxiv](https://arxiv.org/abs/2505.20686)