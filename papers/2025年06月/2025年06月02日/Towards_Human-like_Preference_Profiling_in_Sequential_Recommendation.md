# 探索序列推荐中的人类偏好建模

发布时间：2025年06月02日

`LLM应用` `推荐系统` `用户画像`

> Towards Human-like Preference Profiling in Sequential Recommendation

# 摘要

> 顺序推荐系统的目标是通过分析用户的互动历史来描绘用户画像，这一过程类似于人类通过权衡经验、相对偏好强度和情境相关性来进行决策。然而，现有的基于大型语言模型（LLM）的推荐系统往往未能有效模仿人类灵活且情境感知的决策策略，忽略了结构化、动态和情境感知机制，这些机制对于人类行为至关重要。为了解决这一问题，我们提出了RecPO，一个偏好优化框架，它通过建模结构化反馈和情境延迟，模拟了顺序推荐中的人类-like优先级排序。RecPO利用基于推断的偏好层次结构和时间信号的自适应奖励边界，使模型能够优先考虑立即相关项目，并区分不同程度的偏好和厌恶。在五个真实世界数据集上的广泛实验表明，RecPO不仅在性能上超越了现有的最先进的基准，还成功地反映了人类决策的关键特征：偏好及时满足、保持一致的偏好以及在变化的情境下进行辨别。

> Sequential recommendation systems aspire to profile users by interpreting their interaction histories, echoing how humans make decisions by weighing experience, relative preference strength, and situational relevance. Yet, existing large language model (LLM)-based recommenders often fall short of mimicking the flexible, context-aware decision strategies humans exhibit, neglecting the structured, dynamic, and context-aware mechanisms fundamental to human behaviors. To bridge this gap, we propose RecPO, a preference optimization framework that models structured feedback and contextual delay to emulate human-like prioritization in sequential recommendation RecPO exploits adaptive reward margins based on inferred preference hierarchies and temporal signals, enabling the model to favor immediately relevant items and to distinguish between varying degrees of preference and aversion. Extensive experiments across five real-world datasets demonstrate that RecPO not only yields performance gains over state-of-the-art baselines, but also mirrors key characteristics of human decision-making: favoring timely satisfaction, maintaining coherent preferences, and exercising discernment under shifting contexts.

[Arxiv](https://arxiv.org/abs/2506.02261)