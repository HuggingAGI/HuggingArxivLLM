# 从数据-centric到样本-centric：通过渐进式优化增强LLM推理能力

发布时间：2025年07月09日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的优化方法，特别是通过强化学习和渐进式优化框架（LPPO）来提升模型的推理能力。它关注的是模型的训练策略和算法改进，属于LLM理论的研究范畴。` `人工智能`

> From Data-Centric to Sample-Centric: Enhancing LLM Reasoning via Progressive Optimization

# 摘要

> 可验证奖励的强化学习 (RLVR) 近期显著提升了大型语言模型 (LLMs) 的推理能力。不同于以往研究集中于算法设计、数据整理和奖励塑造，我们从样本为中心的视角重新审视 RLVR，提出了 LPPO（学习进展和前缀引导优化）这一渐进式优化框架。我们的研究聚焦于一个关键问题：如何高效利用少量优质演示样本，而非盲目扩充数据规模。首先，受到提示如何助力人类解题的启发，我们提出了前缀引导采样，一种通过整合专家演示中的部分解题思路来优化策略的在线数据增强方法，尤其在处理难题时效果显著。其次，借鉴人类专注于与其能力相匹配重要问题的学习机制，我们引入了学习进展加权策略，通过动态调整训练样本的影响，促进有助于学习的样本，弱化停滞不前的样本。基于每样本通过率的指数移动平均，我们实现了样本级别的学习进展评估。实验结果表明，我们的方法在数学推理基准测试中显著超越现有基线，不仅收敛速度更快，且达到了更高的性能上限。

> Reinforcement learning with verifiable rewards (RLVR) has recently advanced the reasoning capabilities of large language models (LLMs). While prior work has emphasized algorithmic design, data curation, and reward shaping, we investigate RLVR from a sample-centric perspective and introduce LPPO (Learning-Progress and Prefix-guided Optimization), a framework of progressive optimization techniques. Our work addresses a critical question: how to best leverage a small set of trusted, high-quality demonstrations, rather than simply scaling up data volume. First, motivated by how hints aid human problem-solving, we propose prefix-guided sampling, an online data augmentation method that incorporates partial solution prefixes from expert demonstrations to guide the policy, particularly for challenging instances. Second, inspired by how humans focus on important questions aligned with their current capabilities, we introduce learning-progress weighting, a dynamic strategy that adjusts each training sample's influence based on model progression. We estimate sample-level learning progress via an exponential moving average of per-sample pass rates, promoting samples that foster learning and de-emphasizing stagnant ones. Experiments on mathematical-reasoning benchmarks demonstrate that our methods outperform strong baselines, yielding faster convergence and a higher performance ceiling.

[Arxiv](https://arxiv.org/abs/2507.06573)