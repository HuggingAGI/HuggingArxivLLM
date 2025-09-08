# ACE-RL：面向长文本生成强化学习的自适应约束增强奖励

发布时间：2025年09月05日

`强化学习` `基础理论`

> ACE-RL: Adaptive Constraint-Enhanced Reward for Long-form Generation Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）在长上下文理解上已取得显著进步，然而在高质量长文本生成领域仍面临不小的挑战。现有研究主要存在两大局限：（1）严重依赖稀缺的高质量长文本响应数据，用于监督微调（SFT）或强化学习（RL）中的成对偏好奖励。（2）侧重于相关性、连贯性、有用性等粗粒度质量优化维度，却忽略了不同长文本生成场景中特有的细粒度细节。为解决上述问题，我们提出了基于自适应约束增强奖励的长文本生成强化学习框架（ACE-RL）。ACE-RL首先通过识别每条指令的潜在意图与需求，将其自动拆解为一系列细粒度的自适应约束标准。接着，我们设计了一种奖励机制，根据长文本响应对相应约束的满足度来量化其质量，从而将主观质量评估转化为约束验证。最后，通过强化学习引导模型提升长文本生成质量。实验结果显示，我们的ACE-RL框架在WritingBench上表现出色，相比现有的SFT和RL基线分别提升了20.70%和7.32%；性能最优的模型甚至超越了GPT-4o等专有系统7.10%，为LLMs在各类长文本生成场景下创作高质量内容提供了更高效的训练范式。

> Large Language Models (LLMs) have demonstrated remarkable progress in long-context understanding, yet they face significant challenges in high-quality long-form generation. Existing studies primarily suffer from two limitations: (1) A heavy reliance on scarce, high-quality long-form response data for supervised fine-tuning (SFT) or for pairwise preference reward in reinforcement learning (RL). (2) Focus on coarse-grained quality optimization dimensions, such as relevance, coherence, and helpfulness, overlooking the fine-grained specifics inherent to diverse long-form generation scenarios. To address this issue, we propose a framework using Adaptive Constraint-Enhanced reward for long-form generation Reinforcement Learning (ACE-RL). ACE-RL first automatically deconstructs each instruction into a set of fine-grained, adaptive constraint criteria by identifying its underlying intents and demands. Subsequently, we design a reward mechanism that quantifies the quality of long-form responses based on their satisfaction over corresponding constraints, converting subjective quality evaluation into constraint verification. Finally, we utilize reinforcement learning to guide models toward superior long-form generation capabilities. Experimental results demonstrate that our ACE-RL framework significantly outperforms existing SFT and RL baselines by 20.70% and 7.32% on WritingBench, and our top-performing model even surpasses proprietary systems like GPT-4o by 7.10%, providing a more effective training paradigm for LLMs to generate high-quality content across diverse long-form generation scenarios.

[Arxiv](https://arxiv.org/abs/2509.04903)