# 奖励引导的推测解码：提升LLM推理效率

发布时间：2025年01月31日

`LLM应用

**理由**：该论文提出了一个名为奖励引导的推测解码（RSD）的框架，旨在提升大型语言模型（LLMs）的推理效率。该框架通过结合轻量级草稿模型和强大的目标模型，并引入受控偏差来优先选择高奖励输出，从而在计算成本和输出质量之间找到最佳平衡。这一工作直接针对LLMs的应用场景，特别是资源密集型场景中的部署效率问题，因此应归类为LLM应用。` `人工智能`

> Reward-Guided Speculative Decoding for Efficient LLM Reasoning

# 摘要

> 我们提出了奖励引导的推测解码（RSD），这是一个旨在提升大型语言模型（LLMs）推理效率的创新框架。RSD 巧妙地将轻量级草稿模型与强大的目标模型结合，通过引入受控偏差来优先选择高奖励输出，与现有强制无偏的推测解码方法形成鲜明对比。RSD 利用过程奖励模型评估中间解码步骤，并动态决定是否调用目标模型，从而在计算成本和输出质量之间找到最佳平衡。我们从理论上证明，基于阈值的混合策略能够实现资源利用与性能的最优平衡。在包括奥林匹克级别任务在内的复杂推理基准测试中，RSD 在仅使用目标模型时显著提升了效率（FLOPs 减少高达 4.4 倍），同时在平均准确率上大幅超越并行解码方法（提升高达 +3.5）。这些结果表明，RSD 是一种在资源密集型场景中部署 LLMs 的高效且经济的方法。

> We introduce Reward-Guided Speculative Decoding (RSD), a novel framework aimed at improving the efficiency of inference in large language models (LLMs). RSD synergistically combines a lightweight draft model with a more powerful target model, incorporating a controlled bias to prioritize high-reward outputs, in contrast to existing speculative decoding methods that enforce strict unbiasedness. RSD employs a process reward model to evaluate intermediate decoding steps and dynamically decide whether to invoke the target model, optimizing the trade-off between computational cost and output quality. We theoretically demonstrate that a threshold-based mixture strategy achieves an optimal balance between resource utilization and performance. Extensive evaluations on challenging reasoning benchmarks, including Olympiad-level tasks, show that RSD delivers significant efficiency gains against decoding with the target model only (up to 4.4x fewer FLOPs), while achieving significant better accuracy than parallel decoding method on average (up to +3.5). These results highlight RSD as a robust and cost-effective approach for deploying LLMs in resource-intensive scenarios.

[Arxiv](https://arxiv.org/abs/2501.19324)