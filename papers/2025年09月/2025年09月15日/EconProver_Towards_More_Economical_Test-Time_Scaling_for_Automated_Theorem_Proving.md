# EconProver：致力于自动定理证明更经济的测试时扩展

发布时间：2025年09月15日

`强化学习` `基础理论`

> EconProver: Towards More Economical Test-Time Scaling for Automated Theorem Proving

# 摘要

> 大型语言模型（LLMs）近期在自动定理证明（ATP）领域取得了显著进展——借助广泛采用的测试时扩展策略（尤其是反思性思维链（CoT）推理和增加采样次数），模型性能大幅提升。然而，这些策略均会给推理过程带来巨大计算开销。更关键的是，现有成本分析往往只关注采样次数的调控，却忽略了不同扩展策略所导致的采样成本差异。本文中，我们系统对比了ATP模型各类测试时扩展策略的效率，揭示了当前最先进（SOTA）开源方法的低效问题。在此基础上，我们探索了在保持原始性能的同时，大幅降低token消耗与采样次数的解决方案。具体而言，我们提出两种互补方法并整合为统一的EconRL流水线，以实现收益叠加：（1）动态CoT切换机制，精准减少不必要的token消耗；（2）带可训练前缀的多样化并行扩展强化学习（RL），在有限采样次数下有效提升通过率。在miniF2F和ProofNet数据集上的实验显示，我们的EconProver仅用12%的计算成本，便能达到基线方法的性能水平。这项研究为部署轻量级ATP模型提供了切实可行的思路，无需以性能为代价。

> Large Language Models (LLMs) have recently advanced the field of Automated Theorem Proving (ATP), attaining substantial performance gains through widely adopted test-time scaling strategies, notably reflective Chain-of-Thought (CoT) reasoning and increased sampling passes. However, they both introduce significant computational overhead for inference. Moreover, existing cost analyses typically regulate only the number of sampling passes, while neglecting the substantial disparities in sampling costs introduced by different scaling strategies. In this paper, we systematically compare the efficiency of different test-time scaling strategies for ATP models and demonstrate the inefficiency of the current state-of-the-art (SOTA) open-source approaches. We then investigate approaches to significantly reduce token usage and sample passes while maintaining the original performance. Specifically, we propose two complementary methods that can be integrated into a unified EconRL pipeline for amplified benefits: (1) a dynamic Chain-of-Thought (CoT) switching mechanism designed to mitigate unnecessary token consumption, and (2) Diverse parallel-scaled reinforcement learning (RL) with trainable prefixes to enhance pass rates under constrained sampling passes. Experiments on miniF2F and ProofNet demonstrate that our EconProver achieves comparable performance to baseline methods with only 12% of the computational cost. This work provides actionable insights for deploying lightweight ATP models without sacrificing performance.

[Arxiv](https://arxiv.org/abs/2509.12603)