# SRFT：结合监督与强化微调的单阶段推理方法

发布时间：2025年06月24日

`LLM理论` `机器学习`

> SRFT: A Single-Stage Method with Supervised and Reinforcement Fine-Tuning for Reasoning

# 摘要

> 大型语言模型（LLMs）在推理任务中表现卓越，但如何将监督微调（SFT）与强化学习（RL）有机结合仍是一个关键挑战。我们从熵的角度深入分析了令牌分布、学习动态及整合机制，揭示了SFT与RL的本质区别：SFT对LLM策略分布进行全局粗粒度调整，而RL则进行局部精细优化，熵在此过程中成为评估训练效果的重要指标。基于这些发现，我们提出了一种单阶段方法——监督强化微调（SRFT），通过熵感知的加权机制将SFT与RL有机统一。与传统的两阶段方法不同，SRFT同时运用SFT和RL，直接利用演示和自我探索轨迹优化LLM。实验结果表明，SRFT在五个数学推理基准测试中平均准确率达到59.1%，较零RL方法提升了9.0%，在三个分布外基准测试中更是提升了10.9%。

> Large language models (LLMs) have achieved remarkable progress in reasoning tasks, yet the optimal integration of Supervised Fine-Tuning (SFT) and Reinforcement Learning (RL) remains a fundamental challenge. Through comprehensive analysis of token distributions, learning dynamics, and integration mechanisms from entropy-based perspectives, we reveal key differences between these paradigms: SFT induces coarse-grained global changes to LLM policy distributions, while RL performs fine-grained selective optimizations, with entropy serving as a critical indicator of training effectiveness. Building on these observations, we propose Supervised Reinforcement Fine-Tuning (SRFT), a single-stage method that unifies both fine-tuning paradigms through entropy-aware weighting mechanisms. Our approach simultaneously applies SFT and RL to directly optimize the LLM using demonstrations and self-exploration rollouts rather than through two-stage sequential methods. Extensive experiments show that SRFT achieves 59.1% average accuracy, outperforming zero-RL methods by 9.0% on five mathematical reasoning benchmarks and 10.9% on three out-of-distribution benchmarks.

[Arxiv](https://arxiv.org/abs/2506.19767)