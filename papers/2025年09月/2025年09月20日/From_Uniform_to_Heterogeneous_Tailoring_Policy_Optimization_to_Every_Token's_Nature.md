# 从均一到异构：为每个token的本质定制策略优化

发布时间：2025年09月20日

`强化学习` `基础理论`

> From Uniform to Heterogeneous: Tailoring Policy Optimization to Every Token's Nature

# 摘要

> 强化学习已成为提升大型语言模型（LLMs）推理能力的核心技术。然而，现有算法对所有token采用统一优化策略，却忽略了它们在推理过程中的不同作用。为解决这一问题，我们提出异构自适应策略优化（Heterogeneous Adaptive Policy Optimization, HAPO）——一种全面的token感知算法，能基于token熵动态调整优化策略。在轨迹采样环节，我们提出自适应温度采样法（Adaptive Temperature Sampling），实时调整采样温度：在高熵token处促进探索，在低熵token处确保连贯性。在优势函数计算环节，我们引入token级组平均法（Token Level Group Average），在token级别对优势值进行归一化，既能像token平均损失那样兼顾序列长度，又能保持无偏处理。接着，我们提出差异优势重分配（Differential Advantage Redistribution），利用熵和重要性比率调节具有明确信号的token的奖励调整更新幅度。在裁剪损失环节，我们设计非对称自适应裁剪法（Asymmetric Adaptive Clipping），允许对噪声低熵token大幅降低概率，同时为高熵token创造探索空间。通过系统研究熵与训练动态特性的关系，我们将token级处理融入各个环节，实现了细粒度控制。大量实验结果表明，在不同模型规模下，HAPO均持续优于DAPO。相关代码已开源至https://github.com/starriver030515/HAPO。

> Reinforcement Learning has emerged as the fundamental technique for enhancing reasoning in LLMs. However, existing algorithms apply uniform optimization to all tokens, ignoring their different roles in reasoning process. To address this limitation, we introduce Heterogeneous Adaptive Policy Optimization (HAPO), a comprehensive token-aware algorithm that dynamically adapts optimization based on token entropy. For rollout sampling, we propose Adaptive Temperature Sampling, which adjusts sampling temperature in real time, promoting exploration at high-entropy tokens while preserving coherence at low-entropy ones. For advantage calculation, we introduce Token Level Group Average that normalizes advantages at token level, jointly accounting for sequence-length as in token-mean loss while preserving non-biased treatment. We then develop Differential Advantage Redistribution that leverages entropy and importance ratios to modulate rewards-adjusting updates for tokens with clear signals. For clipping loss, we design Asymmetric Adaptive Clipping, allowing aggressive probability reduction for noisy low-entropy tokens while enabling exploration for high-entropy tokens. Through systematic investigation between entropy and training dynamics, we embedded token-level treatment into every stages to achieve fine-grained control. Extensive experiments demonstrate that HAPO consistently outperforms DAPO across multiple model scales. Our code can be found in https://github.com/starriver030515/HAPO.

[Arxiv](https://arxiv.org/abs/2509.16591)