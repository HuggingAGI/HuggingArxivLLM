# 统一配对框架在强化学习中的人类反馈（RLHF）中的应用：连接生成式奖励建模与策略优化

发布时间：2025年04月07日

`LLM应用` `人工智能` `机器学习`

> A Unified Pairwise Framework for RLHF: Bridging Generative Reward Modeling and Policy Optimization

# 摘要

> 从人类反馈中学习的强化学习（RLHF）已成为训练后使大型语言模型与人类偏好对齐的重要范式。该框架通常分为两个阶段：首先基于人类偏好数据训练奖励模型，然后利用强化学习算法优化语言模型。然而，当前的RLHF方法存在两大限制。第一，现有框架依赖Bradley-Terry模型进行配对响应的标量奖励分配，这给奖励模型带来了巨大挑战，因为不同上下文中提示-响应对的变异性要求模型具备强大的校准能力。第二，尽管奖励模型执行的是判别任务，但它们通常是从生成式基础模型初始化，导致任务与模型之间的不匹配。本文提出了一种名为Pairwise-RL的RLHF框架，通过生成式奖励建模与配对近端策略优化（PPO）算法的结合解决这些挑战。Pairwise-RL在一致的配对范式下统一了奖励模型训练及其在强化学习中的应用，借助生成建模技术提升奖励模型性能和评分校准。实验结果表明，Pairwise-RL在内部评估数据集和标准公共基准测试中均优于传统RLHF框架，凸显了其在提升模型对齐和行为表现方面的有效性。

> Reinforcement Learning from Human Feedback (RLHF) has emerged as a important paradigm for aligning large language models (LLMs) with human preferences during post-training. This framework typically involves two stages: first, training a reward model on human preference data, followed by optimizing the language model using reinforcement learning algorithms. However, current RLHF approaches may constrained by two limitations. First, existing RLHF frameworks often rely on Bradley-Terry models to assign scalar rewards based on pairwise comparisons of individual responses. However, this approach imposes significant challenges on reward model (RM), as the inherent variability in prompt-response pairs across different contexts demands robust calibration capabilities from the RM. Second, reward models are typically initialized from generative foundation models, such as pre-trained or supervised fine-tuned models, despite the fact that reward models perform discriminative tasks, creating a mismatch. This paper introduces Pairwise-RL, a RLHF framework that addresses these challenges through a combination of generative reward modeling and a pairwise proximal policy optimization (PPO) algorithm. Pairwise-RL unifies reward model training and its application during reinforcement learning within a consistent pairwise paradigm, leveraging generative modeling techniques to enhance reward model performance and score calibration. Experimental evaluations demonstrate that Pairwise-RL outperforms traditional RLHF frameworks across both internal evaluation datasets and standard public benchmarks, underscoring its effectiveness in improving alignment and model behavior.

[Arxiv](https://arxiv.org/abs/2504.04950)