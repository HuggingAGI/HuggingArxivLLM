# EFRame：一种通过探索-过滤-重放强化学习框架实现更深入推理的方法

发布时间：2025年06月27日

`Agent` `人工智能`

> EFRame: Deeper Reasoning via Exploration-Filtering-Replay Reinforcement Learning Framework

# 摘要

> 强化学习（RL）的最新进展显著提升了大型语言模型（LLMs）的推理能力。虽然组相对策略优化（GRPO）作为PPO的一种高效变体，通过降低计算成本，但其仍面临探索有限、采样效率低和不稳定等问题，限制了在复杂推理任务中的表现。为解决这些局限，我们提出了EFRame框架，通过探索-过滤-回放机制，从三个关键维度全面增强GRPO。EFRame通过额外的轨迹探索、在线过滤噪声样本以及经验回放机制，构建了一个完整且稳定的训练循环，引导模型从探索阶段顺利过渡到收敛状态。实验结果表明，EFRame不仅提升了训练的鲁棒性和效率，还解锁了 vanilla GRPO 难以实现的深层推理能力。此外，EFRame实现了对训练样本的更精细分类，为分析不同样本类型对强化学习过程的贡献提供了新视角。我们的代码已在GitHub上开源，欢迎访问 https://github.com/597358816/EFRame 查看。

> Recent advances in reinforcement learning (RL) have significantly enhanced the reasoning capabilities of large language models (LLMs). Group Relative Policy Optimization (GRPO), an efficient variant of PPO that lowers RL's computational cost, still faces limited exploration, low sample efficiency and instability, constraining its performance on complex reasoning tasks. To address these limitations, we introduce EFRame, an Exploration-Filtering-Replay framework that systematically augments GRPO along three critical dimensions. EFRame performs additional rollouts to explore high-quality trajectories, applies online filtering to eliminate low-quality samples that introduce noise and variance, and leverages experience replay to repeatedly exploit rare but informative samples. EFRame establishes a complete and stable learning cycle, guiding the model through a structured transition from exploration to convergence. Our experiments across a variety of reasoning benchmarks demonstrate that EFRame not only improves the robustness and efficiency of training, but also enables access to deeper reasoning capabilities that remain unattainable under vanilla GRPO. Furthermore, EFRame enables a more fine-grained categorization of training samples, allowing for a deeper analysis of how different types of samples contribute to the learning process in RL. Our code is available at https://github.com/597358816/EFRame.

[Arxiv](https://arxiv.org/abs/2506.22200)