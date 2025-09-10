# ΔL归一化：再思考RLVR中的损失聚合

发布时间：2025年09月09日

`强化学习` `基础理论`

> $ΔL$ Normalization: Rethink Loss Aggregation in RLVR

# 摘要

> 我们提出了$ΔL$归一化方法——一种简单却高效的损失聚合方法，专为带可验证奖励的强化学习（RLVR）中动态生成长度的特性量身定制。近年来，RLVR在提升大型语言模型（LLMs）推理能力方面成效显著，但训练时响应长度的显著差异却带来了棘手问题：梯度方差过高导致优化过程极不稳定。尽管GRPO、DAPO、Dr. GRPO等现有方法尝试通过引入不同损失归一化项解决这一难题，却要么产生有偏估计，要么仍受困于高梯度方差。为此，我们从理论与实证双重视角分析了长度变化对策略损失的影响，并将该问题转化为寻找最小方差无偏估计量。所提$ΔL$归一化方法不仅能对真实策略损失进行无偏估计，还在理论上实现了梯度方差的最小化。大量实验验证，该方法在不同模型规模、最大长度及任务中均持续表现卓越。相关代码将公开于https://github.com/zerolllin/Delta-L-Normalization。

> We propose $ΔL$ Normalization, a simple yet effective loss aggregation method tailored to the characteristic of dynamic generation lengths in Reinforcement Learning with Verifiable Rewards (RLVR). Recently, RLVR has demonstrated strong potential in improving the reasoning capabilities of large language models (LLMs), but a major challenge lies in the large variability of response lengths during training, which leads to high gradient variance and unstable optimization. Although previous methods such as GRPO, DAPO, and Dr. GRPO introduce different loss normalization terms to address this issue, they either produce biased estimates or still suffer from high gradient variance. By analyzing the effect of varying lengths on policy loss both theoretically and empirically, we reformulate the problem as finding a minimum-variance unbiased estimator. Our proposed $ΔL$ Normalization not only provides an unbiased estimate of the true policy loss but also minimizes gradient variance in theory. Extensive experiments show that it consistently achieves superior results across different model sizes, maximum lengths, and tasks. Our code will be made public at https://github.com/zerolllin/Delta-L-Normalization.

[Arxiv](https://arxiv.org/abs/2509.07558)