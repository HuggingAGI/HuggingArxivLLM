# RLEP：强化学习结合经验回放，助力提升大语言模型的推理能力

发布时间：2025年07月10日

`LLM应用` `人工智能`

> RLEP: Reinforcement Learning with Experience Replay for LLM Reasoning

# 摘要

> 强化学习（RL）在大型语言模型中的应用是个耗能大户：训练常不稳定，策略可能逐渐偏离预训练权重。我们提出了\emph{RLEP}\, -- \,强化学习与经验回放\, -- \,一个两阶段框架，先收集验证轨迹，再在后续训练中重放这些轨迹。每个更新步骤中，策略会在混合新生成轨迹与重放成功经验的小批量数据上优化。通过重放高质量例子，RLEP引导模型远离徒劳探索，专注有前景推理路径，实现更快收敛和更强性能。在Qwen2.5-Math-7B模型上，RLEP以更少更新次数达基准峰值准确率并超越，AIME-2024准确率从38.2%提至39.9%，AIME-2025从19.8%提至22.3%，AMC-2023从77.0%提至82.2%。我们的代码、数据集和检查点在https://github.com/Kwai-Klear/RLEP公开，助力可重复研究。

> Reinforcement learning (RL) for large language models is an energy-intensive endeavor: training can be unstable, and the policy may gradually drift away from its pretrained weights. We present \emph{RLEP}\, -- \,Reinforcement Learning with Experience rePlay\, -- \,a two-phase framework that first collects verified trajectories and then replays them during subsequent training. At every update step, the policy is optimized on mini-batches that blend newly generated rollouts with these replayed successes. By replaying high-quality examples, RLEP steers the model away from fruitless exploration, focuses learning on promising reasoning paths, and delivers both faster convergence and stronger final performance. On the Qwen2.5-Math-7B base model, RLEP reaches baseline peak accuracy with substantially fewer updates and ultimately surpasses it, improving accuracy on AIME-2024 from 38.2% to 39.9%, on AIME-2025 from 19.8% to 22.3%, and on AMC-2023 from 77.0% to 82.2%. Our code, datasets, and checkpoints are publicly available at https://github.com/Kwai-Klear/RLEP to facilitate reproducibility and further research.

[Arxiv](https://arxiv.org/abs/2507.07451)