# 奖励模型关注的并非因果关系，而是模型输出的一致性特征。

发布时间：2025年02月20日

`LLM理论` `人工智能` `机器学习`

> Reward Models Identify Consistency, Not Causality

# 摘要

> 奖励模型（RMs）在使大型语言模型（LLMs）与人类偏好对齐以及提升推理质量方面扮演着关键角色。然而，传统上 RMs 通过评估候选输出的正确性和连贯性对其进行排序的思路，正面临一系列令人惊讶的发现的挑战。我们的研究揭示，最先进的奖励模型更重视结构上的连贯性，而非因果上的正确性。具体而言，移除问题陈述对奖励分数的影响微乎其微，而改变数值或扰乱推理流程则会对 RMs 的输出产生显著影响。此外，RMs 对完整的推理轨迹表现出强烈的依赖性——截断或不完整的推理步骤会导致奖励分配产生显著差异，这表明 RMs 主要依赖于学习到的推理模式，而非对问题的明确理解。这些发现适用于多种架构、数据集和任务，为我们带来了三个关键启示：（1）RMs 主要评估连贯性，而非真实的推理质量；（2）对问题的明确理解在奖励分配中的作用被夸大了；（3）现有的 RMs 可能在对响应进行排序方面比验证逻辑有效性更为有效。我们的研究结果揭示了现有奖励建模方法的根本性局限性，强调了转向因果感知奖励模型的必要性，这种模型应超越基于一致性的评估框架，以实现更全面的评估能力。

> Reward models (RMs) play a crucial role in aligning large language models (LLMs) with human preferences and enhancing reasoning quality. Traditionally, RMs are trained to rank candidate outputs based on their correctness and coherence. However, in this work, we present several surprising findings that challenge common assumptions about RM behavior. Our analysis reveals that state-of-the-art reward models prioritize structural consistency over causal correctness. Specifically, removing the problem statement has minimal impact on reward scores, whereas altering numerical values or disrupting the reasoning flow significantly affects RM outputs. Furthermore, RMs exhibit a strong dependence on complete reasoning trajectories truncated or incomplete steps lead to significant variations in reward assignments, indicating that RMs primarily rely on learned reasoning patterns rather than explicit problem comprehension. These findings hold across multiple architectures, datasets, and tasks, leading to three key insights: (1) RMs primarily assess coherence rather than true reasoning quality; (2) The role of explicit problem comprehension in reward assignment is overstated; (3) Current RMs may be more effective at ranking responses than verifying logical validity. Our results suggest a fundamental limitation in existing reward modeling approaches, emphasizing the need for a shift toward causality-aware reward models that go beyond consistency-driven evaluation.

[Arxiv](https://arxiv.org/abs/2502.14619)