# DRA-GRPO：探索感知多样性奖励调整用于大型语言模型 R1-Zero 类似训练的方法

发布时间：2025年05月13日

`LLM理论` `人工智能`

> DRA-GRPO: Exploring Diversity-Aware Reward Adjustment for R1-Zero-Like Training of Large Language Models

# 摘要

> 在语言模型后训练中，强化学习的最新进展如组相对策略优化（GRPO）在低资源环境下展现出巨大潜力。然而，GRPO依赖的解层面和标量奖励信号无法捕捉采样完成结果的语义多样性，导致多样性与质量之间的不一致问题：不同推理路径可能获得难以区分的奖励。为解决这一问题，我们提出了$	extit{多样性感知奖励调整}$（DRA），一种在奖励计算中显式纳入语义多样性的方法。DRA通过子模化互信息（SMI）降低冗余完成结果的权重，并放大对多样化完成结果的奖励。这在学习过程中促进更好的探索，同时保持对高质量样本的稳定利用。我们的方法与GRPO及其变体DR.~GRPO无缝集成，形成了$	extit{DRA-GRPO}$和$	extit{DGA-DR.~GRPO}$。我们在五个数学推理基准测试中评估了该方法，发现其性能优于最近的强基线。仅需7,000个微调样本和总计约55美元的训练成本，它便达到了58.2%的平均准确率，实现了最先进的性能。代码可在https://github.com/xiwenc1/DRA-GRPO获取。

> Recent advances in reinforcement learning for language model post-training, such as Group Relative Policy Optimization (GRPO), have shown promise in low-resource settings. However, GRPO typically relies on solution-level and scalar reward signals that fail to capture the semantic diversity among sampled completions. This leads to what we identify as a diversity-quality inconsistency, where distinct reasoning paths may receive indistinguishable rewards. To address this limitation, we propose $\textit{Diversity-aware Reward Adjustment}$ (DRA), a method that explicitly incorporates semantic diversity into the reward computation. DRA uses Submodular Mutual Information (SMI) to downweight redundant completions and amplify rewards for diverse ones. This encourages better exploration during learning, while maintaining stable exploitation of high-quality samples. Our method integrates seamlessly with both GRPO and its variant DR.~GRPO, resulting in $\textit{DRA-GRPO}$ and $\textit{DGA-DR.~GRPO}$. We evaluate our method on five mathematical reasoning benchmarks and find that it outperforms recent strong baselines. It achieves state-of-the-art performance with an average accuracy of 58.2%, using only 7,000 fine-tuning samples and a total training cost of approximately $55. The code is available at https://github.com/xiwenc1/DRA-GRPO.

[Arxiv](https://arxiv.org/abs/2505.09655)