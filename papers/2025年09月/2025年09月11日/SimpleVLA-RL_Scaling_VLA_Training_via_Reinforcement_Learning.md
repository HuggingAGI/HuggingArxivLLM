# SimpleVLA-RL：借助强化学习实现VLA训练规模化

发布时间：2025年09月11日

`强化学习` `工业与制造`

> SimpleVLA-RL: Scaling VLA Training via Reinforcement Learning

# 摘要

> 视觉-语言-动作（VLA）模型是近年来机器人操作领域的强大新范式。尽管大规模预训练与监督微调（SFT）已带来显著进展，但这类模型仍面临两大核心挑战：(i) SFT扩展所需的大规模人工操作机器人轨迹数据稀缺且成本高昂；(ii) 对涉及分布偏移的任务泛化能力有限。大型推理模型（LRMs）的最新突破表明，强化学习（RL）能显著提升逐步推理能力，这不禁引出一个问题：RL能否同样提升VLA的长时程逐步动作规划能力？为此，我们提出SimpleVLA-RL——一个专为VLA模型设计的高效RL框架。基于veRL，我们创新性地提出了VLA专属轨迹采样、可扩展并行化、多环境渲染及优化损失计算等模块。将其应用于OpenVLA-OFT时，SimpleVLA-RL在LIBERO数据集上达到了当前最佳（SoTA）性能；在我们提出的探索增强策略加持下，其在RoboTwin 1.0与2.0上的表现甚至超越了【数学公式】。SimpleVLA-RL不仅降低了对大规模数据的依赖，实现了稳健泛化，还在真实任务中显著超越了SFT。值得注意的是，我们在RL训练中发现了一种名为“pushcut”的新现象：策略会探索出先前训练中从未出现过的全新模式。项目地址：https://github.com/PRIME-RL/SimpleVLA-RL

> Vision-Language-Action (VLA) models have recently emerged as a powerful paradigm for robotic manipulation. Despite substantial progress enabled by large-scale pretraining and supervised fine-tuning (SFT), these models face two fundamental challenges: (i) the scarcity and high cost of large-scale human-operated robotic trajectories required for SFT scaling, and (ii) limited generalization to tasks involving distribution shift. Recent breakthroughs in Large Reasoning Models (LRMs) demonstrate that reinforcement learning (RL) can dramatically enhance step-by-step reasoning capabilities, raising a natural question: Can RL similarly improve the long-horizon step-by-step action planning of VLA? In this work, we introduce SimpleVLA-RL, an efficient RL framework tailored for VLA models. Building upon veRL, we introduce VLA-specific trajectory sampling, scalable parallelization, multi-environment rendering, and optimized loss computation. When applied to OpenVLA-OFT, SimpleVLA-RL achieves SoTA performance on LIBERO and even outperforms $π_0$ on RoboTwin 1.0\&2.0 with the exploration-enhancing strategies we introduce. SimpleVLA-RL not only reduces dependence on large-scale data and enables robust generalization, but also remarkably surpasses SFT in real-world tasks. Moreover, we identify a novel phenomenon ``pushcut'' during RL training, wherein the policy discovers previously unseen patterns beyond those seen in the previous training process. Github: https://github.com/PRIME-RL/SimpleVLA-RL

[Arxiv](https://arxiv.org/abs/2509.09674)