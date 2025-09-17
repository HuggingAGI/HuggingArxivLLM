# LLMAP：LLM辅助的结合用户偏好的多目标路径规划

发布时间：2025年09月13日

`LLM应用` `交通运输`

> LLMAP: LLM-Assisted Multi-Objective Route Planning with User Preferences

# 摘要

> 大型语言模型（LLMs）的兴起，让自然语言驱动的路线规划成为融合丰富用户目标的新兴研究方向。当前研究主要分为两类：一类是将LLM作为智能体（LLM-as-Agent）直接进行路线规划，另一类是基于图的搜索策略。但前一种方法的LLM难以处理海量地图数据，后一种方法则在理解自然语言偏好上能力不足。更关键的是，全球用户在时空分布上高度异质且难以预测，这也带来了挑战。为此，本文提出了一种新颖的LLM辅助路线规划（LLMAP）系统：通过LLM作为解析器（LLM-as-Parser）理解自然语言、识别任务、提取用户偏好并梳理任务依赖关系，同时结合多步图构建与迭代搜索（MSGS）算法作为底层求解器来寻找最优路线。该系统采用多目标优化方法，自适应调整目标权重，在最大化兴趣点（POI）质量和任务完成率的同时缩短路线距离，并满足三个关键约束：用户时间限制、POI开放时间及任务依赖关系。我们在全球14个国家、27个城市采集了1000个不同复杂度的路线规划提示，以此开展了大量实验。结果表明，该方法在多约束条件下表现优异，且各项性能均有保障。

> The rise of large language models (LLMs) has made natural language-driven route planning an emerging research area that encompasses rich user objectives. Current research exhibits two distinct approaches: direct route planning using LLM-as-Agent and graph-based searching strategies. However, LLMs in the former approach struggle to handle extensive map data, while the latter shows limited capability in understanding natural language preferences. Additionally, a more critical challenge arises from the highly heterogeneous and unpredictable spatio-temporal distribution of users across the globe. In this paper, we introduce a novel LLM-Assisted route Planning (LLMAP) system that employs an LLM-as-Parser to comprehend natural language, identify tasks, and extract user preferences and recognize task dependencies, coupled with a Multi-Step Graph construction with iterative Search (MSGS) algorithm as the underlying solver for optimal route finding. Our multi-objective optimization approach adaptively tunes objective weights to maximize points of interest (POI) quality and task completion rate while minimizing route distance, subject to three key constraints: user time limits, POI opening hours, and task dependencies. We conduct extensive experiments using 1,000 routing prompts sampled with varying complexity across 14 countries and 27 cities worldwide. The results demonstrate that our approach achieves superior performance with guarantees across multiple constraints.

[Arxiv](https://arxiv.org/abs/2509.12273)