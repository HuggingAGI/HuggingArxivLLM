# PEO：通过训练后策略外推提升双因子偏好对齐

发布时间：2025年03月03日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）与人类价值观对齐的挑战，提出了新的训练方法（PEO），并进行了理论分析，属于理论层面的研究。` `人工智能`

> PEO: Improving Bi-Factorial Preference Alignment with Post-Training Policy Extrapolation

# 摘要

> 大型语言模型与人类价值观的对齐是一个关键挑战，特别是在平衡有用性和无害性等相互冲突的目标时。现有的方法，如从人类反馈中进行强化学习（RLHF）和直接偏好优化（DPO），都面临着显著的局限性：RLHF在多目标优化中存在不稳定和低效的问题，而DPO缺乏动态权衡的机制。为了解决这些挑战，我们提出了训练后外推优化（PEO），这是一种新颖且高效的双因素对齐框架。PEO通过一个三阶段的流水线在单次训练过程中生成一组帕累托最优策略：（1）特定方面的学习，（2）通过插值进行通用初始化，（3）通过外推进行训练后优化。PEO能够在推理时动态适应不同的用户偏好，而无需重新训练。我们在多个大型语言模型上的全面实验表明，与基线方法相比，PEO实现了更优越的帕累托前沿，提供了更高的灵活性和计算效率。理论分析进一步突显了PEO在克服优化瓶颈方面的潜力，为可扩展的个性化对齐铺平了道路。

> The alignment of large language models with human values presents a critical challenge, particularly when balancing conflicting objectives like helpfulness and harmlessness. Existing approaches, such as Reinforcement Learning from Human Feedback (RLHF) and Direct Preference Optimization (DPO), face notable limitations: RLHF suffers from instability and inefficiency in multi-objective optimization, while DPO lacks mechanisms for dynamic trade-offs. To address these challenges, we propose Post-Training Extrapolation Optimization (PEO), a novel and efficient framework for bi-factorial alignment. PEO generates a family of Pareto-optimal policies in a single training pass by leveraging a three-phase pipeline: (1) aspect-specific learning, (2) generalist initialization via interpolation, and (3) post-training optimization via extrapolation. PEO enables dynamic adaptation to diverse user preferences at inference time without retraining. Our comprehensive experiments across multiple LLMs demonstrate that PEO achieves superior Pareto fronts compared to baselines, offering improved flexibility and computational efficiency. Theoretical analyses further highlight PEO's capacity to overcome optimization bottlenecks, paving the way for scalable, personalized alignment.

[Arxiv](https://arxiv.org/abs/2503.01233)