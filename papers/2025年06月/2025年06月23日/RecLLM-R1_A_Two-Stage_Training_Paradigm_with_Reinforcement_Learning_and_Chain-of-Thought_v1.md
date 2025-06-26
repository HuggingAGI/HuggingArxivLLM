# RecLLM-R1：强化学习与思维链v1驱动的两阶段训练范式

发布时间：2025年06月23日

`LLM应用` `推荐系统` `社交媒体`

> RecLLM-R1: A Two-Stage Training Paradigm with Reinforcement Learning and Chain-of-Thought v1

# 摘要

> 传统推荐系统常受“过滤气泡”困扰，同时面临外部知识利用率低和模型优化与企业政策迭代脱节的问题。为解决这些局限，本文提出RecLLM-R1——一个基于大型语言模型（LLMs）并借鉴DeepSeek R1方法的新推荐框架。该框架首先通过精心设计的数据构建过程，将用户档案、历史交互和多维度的项目属性转化为LLM可解释的自然语言提示。随后采用两阶段训练范式：第一阶段通过监督微调（SFT）赋予LLM基础推荐能力；第二阶段则结合强化学习技术组相对策略优化（GRPO）与链式推理（CoT）机制，通过灵活定义的奖励函数引导模型进行多步推理和整体决策，以同时优化推荐准确性、多样性和其他定制化企业目标。在大规模社交媒体平台的真实用户行为数据集上的实证评估表明，RecLLM-R1在准确性、多样性和新颖性等多方面的评估指标上显著超越现有基线方法，有效缓解了过滤气泡效应，并为在复杂商业目标下推荐模型与政策的集成优化提供了一个有前景的解决方案。
    

> Traditional recommendation systems often grapple with "filter bubbles", underutilization of external knowledge, and a disconnect between model optimization and business policy iteration. To address these limitations, this paper introduces RecLLM-R1, a novel recommendation framework leveraging Large Language Models (LLMs) and drawing inspiration from the DeepSeek R1 methodology. The framework initiates by transforming user profiles, historical interactions, and multi-faceted item attributes into LLM-interpretable natural language prompts through a carefully engineered data construction process. Subsequently, a two-stage training paradigm is employed: the initial stage involves Supervised Fine-Tuning (SFT) to imbue the LLM with fundamental recommendation capabilities. The subsequent stage utilizes Group Relative Policy Optimization (GRPO), a reinforcement learning technique, augmented with a Chain-of-Thought (CoT) mechanism. This stage guides the model through multi-step reasoning and holistic decision-making via a flexibly defined reward function, aiming to concurrently optimize recommendation accuracy, diversity, and other bespoke business objectives. Empirical evaluations on a real-world user behavior dataset from a large-scale social media platform demonstrate that RecLLM-R1 significantly surpasses existing baseline methods across a spectrum of evaluation metrics, including accuracy, diversity, and novelty. It effectively mitigates the filter bubble effect and presents a promising avenue for the integrated optimization of recommendation models and policies under intricate business goals.

[Arxiv](https://arxiv.org/abs/2506.19235)