# RecLLM-R1：强化学习与思维链v1驱动的两阶段训练范式

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于推荐系统，提出了一种新的推荐框架RecLLM-R1。该框架通过将用户和项目数据转化为自然语言提示，并结合监督微调和强化学习方法，优化推荐系统的性能。论文的焦点在于LLMs在推荐系统中的具体应用及其带来的改进，因此属于LLM应用类别。` `推荐系统` `社交媒体`

> RecLLM-R1: A Two-Stage Training Paradigm with Reinforcement Learning and Chain-of-Thought v1

# 摘要

> 传统推荐系统常面临“过滤气泡”、外部知识利用率低以及模型优化与业务策略迭代脱节的挑战。为解决这些问题，本文提出了RecLLM-R1，这是一种基于大型语言模型（LLMs）并借鉴DeepSeek R1方法的新颖推荐框架。该框架首先通过精心设计的数据构建流程，将用户画像、历史互动数据以及多维度的项目属性转化为LLM可理解的自然语言提示。随后，采用两阶段训练范式：第一阶段通过监督微调（SFT）赋予LLM基础的推荐能力；第二阶段则运用增强有链式思维（Chain-of-Thought, CoT）机制的分组相对策略优化（GRPO）强化学习方法。这一阶段通过灵活定义的奖励函数引导模型进行多步推理和全局决策，旨在同时优化推荐的准确性、多样性以及其他定制化业务目标。在大规模社交媒体平台的真实用户行为数据集上的实证评估表明，RecLLM-R1在准确性、多样性、新颖性等多个评估指标上显著超越现有基线方法，有效缓解了过滤气泡效应，并为在复杂业务目标下推荐模型与策略的协同优化提供了一条有前景的途径。

> Traditional recommendation systems often grapple with "filter bubbles", underutilization of external knowledge, and a disconnect between model optimization and business policy iteration. To address these limitations, this paper introduces RecLLM-R1, a novel recommendation framework leveraging Large Language Models (LLMs) and drawing inspiration from the DeepSeek R1 methodology. The framework initiates by transforming user profiles, historical interactions, and multi-faceted item attributes into LLM-interpretable natural language prompts through a carefully engineered data construction process. Subsequently, a two-stage training paradigm is employed: the initial stage involves Supervised Fine-Tuning (SFT) to imbue the LLM with fundamental recommendation capabilities. The subsequent stage utilizes Group Relative Policy Optimization (GRPO), a reinforcement learning technique, augmented with a Chain-of-Thought (CoT) mechanism. This stage guides the model through multi-step reasoning and holistic decision-making via a flexibly defined reward function, aiming to concurrently optimize recommendation accuracy, diversity, and other bespoke business objectives. Empirical evaluations on a real-world user behavior dataset from a large-scale social media platform demonstrate that RecLLM-R1 significantly surpasses existing baseline methods across a spectrum of evaluation metrics, including accuracy, diversity, and novelty. It effectively mitigates the filter bubble effect and presents a promising avenue for the integrated optimization of recommendation models and policies under intricate business goals.

[Arxiv](https://arxiv.org/abs/2506.19235)