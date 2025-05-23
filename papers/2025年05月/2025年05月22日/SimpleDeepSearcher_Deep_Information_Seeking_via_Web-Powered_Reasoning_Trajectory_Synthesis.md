# SimpleDeepSearcher: 通过合成网络增强推理轨迹实现深度信息检索

发布时间：2025年05月22日

`RAG` `信息检索`

> SimpleDeepSearcher: Deep Information Seeking via Web-Powered Reasoning Trajectory Synthesis

# 摘要

> 检索增强生成（RAG）系统在复杂深度搜索场景中推动了大型语言模型（LLMs）的发展，尤其在需要多步推理和迭代信息检索的任务中表现突出。然而，现有方法在实践中面临多重挑战，包括高质量训练轨迹的缺失、模拟环境中的分布不匹配问题，以及现实部署中高昂的计算成本。本文介绍的SimpleDeepSearcher是一个轻量级但高效的框架，通过战略性数据工程而非复杂训练范式来弥补这一差距。我们的方法通过模拟实时网络搜索环境中的现实用户交互来合成高质量训练数据，并结合多标准整理策略，优化输入和输出两侧的多样性和质量。在五个跨领域基准上的实验表明，仅对871个整理样本进行监督微调，就能显著超越基于强化学习的基线。我们的工作通过系统解决数据稀缺瓶颈，确立了监督微调作为可行路径，并为高效深度搜索系统提供了实用见解。我们的代码可在https://github.com/RUCAIBox/SimpleDeepSearcher获取。


> Retrieval-augmented generation (RAG) systems have advanced large language models (LLMs) in complex deep search scenarios requiring multi-step reasoning and iterative information retrieval. However, existing approaches face critical limitations that lack high-quality training trajectories or suffer from the distributional mismatches in simulated environments and prohibitive computational costs for real-world deployment. This paper introduces SimpleDeepSearcher, a lightweight yet effective framework that bridges this gap through strategic data engineering rather than complex training paradigms. Our approach synthesizes high-quality training data by simulating realistic user interactions in live web search environments, coupled with a multi-criteria curation strategy that optimizes the diversity and quality of input and output side. Experiments on five benchmarks across diverse domains demonstrate that SFT on only 871 curated samples yields significant improvements over RL-based baselines. Our work establishes SFT as a viable pathway by systematically addressing the data-scarce bottleneck, offering practical insights for efficient deep search systems. Our code is available at https://github.com/RUCAIBox/SimpleDeepSearcher.

[Arxiv](https://arxiv.org/abs/2505.16834)