# GVPO：针对大型语言模型后训练的组方差策略优化

发布时间：2025年04月28日

`LLM理论` `人工智能` `机器学习`

> GVPO: Group Variance Policy Optimization for Large Language Model Post-Training

# 摘要

> 后训练在精调和对齐大型语言模型以满足特定任务和人类偏好方面起着关键作用。尽管最近的后训练技术如组相对策略优化 (GRPO) 通过利用增加的采样和相对奖励评分取得了更好的性能，但这些方法通常会遇到训练不稳定的问题，这限制了它们的实际应用。为了解决这一挑战，我们提出了组方差策略优化 (GVPO)。GVPO将KL约束奖励最大化的解析解直接整合到其梯度权重中，确保与最优策略保持一致。该方法提供了直观的物理解释：其梯度反映了隐含奖励与实际奖励之间中心距离的均方误差。GVPO具有两个关键优势：（1）它保证了唯一的最优解，正好是KL约束奖励最大化的目标；（2）它支持灵活的采样分布，避免了在策略和重要性采样的限制。通过将理论保证与实际适应性相结合，GVPO为可靠且灵活的大型语言模型后训练确立了新的范式。

> Post-training plays a crucial role in refining and aligning large language models to meet specific tasks and human preferences. While recent advancements in post-training techniques, such as Group Relative Policy Optimization (GRPO), leverage increased sampling with relative reward scoring to achieve superior performance, these methods often suffer from training instability that limits their practical adoption. To address this challenge, we present Group Variance Policy Optimization (GVPO). GVPO incorporates the analytical solution to KL-constrained reward maximization directly into its gradient weights, ensuring alignment with the optimal policy. The method provides intuitive physical interpretations: its gradient mirrors the mean squared error between the central distance of implicit rewards and that of actual rewards. GVPO offers two key advantages: (1) it guarantees a unique optimal solution, exactly the KL-constrained reward maximization objective, (2) it supports flexible sampling distributions that avoids on-policy and importance sampling limitations. By unifying theoretical guarantees with practical adaptability, GVPO establishes a new paradigm for reliable and versatile LLM post-training.

[Arxiv](https://arxiv.org/abs/2504.19599)