# 基于整理数据的监督微调属于强化学习（且可进一步改进）。

发布时间：2025年07月17日

`LLM理论` `机器人控制` `自动化`

> Supervised Fine Tuning on Curated Data is Reinforcement Learning (and can be improved)

# 摘要

> 行为克隆（BC）在精心整理（或筛选）的数据上是大型语言模型监督微调（SFT）和控制策略模仿学习的主要范式。我们从这一成功策略出发，结合强化学习（RL）寻找最优策略的理论与实践进行深入分析。基于现有文献，我们发现SFT实际上是在稀疏奖励设置下最大化强化学习目标的下界，这解释了其通常表现出的良好性能。从这一视角出发，我们发现只需对SFT进行小幅修改，即可得到一个重要加权变体（iw-SFT），使其更接近强化学习的训练方式。具体来说，iw-SFT不仅优化了更紧的强化学习目标下界，还能在整理数据上超越传统SFT的性能。我们证明了iw-SFT易于实现，并且可以进一步推广到基于质量评分数据的训练场景。这一方法在大型语言模型和连续控制任务的策略训练中表现优异，例如在AIME 2024数据集上达到了66.7%的准确率，与更先进的强化学习算法相媲美。

> Behavior Cloning (BC) on curated (or filtered) data is the predominant paradigm for supervised fine-tuning (SFT) of large language models; as well as for imitation learning of control policies. Here, we draw on a connection between this successful strategy and the theory and practice of finding optimal policies via Reinforcement Learning (RL). Building on existing literature, we clarify that SFT can be understood as maximizing a lower bound on the RL objective in a sparse reward setting. Giving support to its often observed good performance. From this viewpoint, we realize that a small modification to SFT leads to an importance weighted variant that behaves closer to training with RL as it: i) optimizes a tighter bound to the RL objective and, ii) can improve performance compared to SFT on curated data. We refer to this variant as importance weighted supervised fine-tuning (iw-SFT). We show that it is easy to implement and can be further generalized to training with quality scored data. The resulting SFT variants are competitive with more advanced RL algorithms for large language models and for training policies in continuous control tasks. For example achieving 66.7% on the AIME 2024 dataset.

[Arxiv](https://arxiv.org/abs/2507.12856)