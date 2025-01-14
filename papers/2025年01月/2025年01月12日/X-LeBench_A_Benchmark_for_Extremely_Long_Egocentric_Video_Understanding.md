# X-LeBench: 极长第一人称视频理解基准

发布时间：2025年01月12日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）的文本处理能力来生成与现实世界视频数据一致的日常计划，并构建了一个新的基准数据集 X-LeBench 用于评估超长第一人称视频记录任务。虽然论文涉及了多模态大型语言模型（MLLMs）的评估，但其核心应用场景是利用 LLMs 的能力来生成和处理视频数据，因此归类为 LLM 应用更为合适。` `视频分析` `具身智能`

> X-LeBench: A Benchmark for Extremely Long Egocentric Video Understanding

# 摘要

> # 摘要
长时第一人称视频理解能够提供丰富的上下文信息和独特的长期人类行为洞察，在具身智能、长期活动分析和个性化辅助技术等领域具有广阔的应用前景。然而，现有基准数据集大多局限于单一、短时长的视频或中等时长的视频（最多几十分钟），在评估超长第一人称视频记录方面存在明显不足。为此，我们推出了 X-LeBench，这是一个专为评估超长第一人称视频记录任务而设计的新基准数据集。借助大型语言模型（LLMs）的强大文本处理能力，X-LeBench 构建了一个生活日志模拟管道，生成与现实世界视频数据一致的、连贯的日常计划。通过将合成的日常计划与 Ego4D（一个涵盖广泛日常生活场景的大规模第一人称视频数据集）的真实视频片段灵活结合，我们生成了 432 个模拟视频生活日志，这些日志在丰富的场景中反映了现实的日常活动。视频生活日志的时长从 23 分钟到 16.4 小时不等。对多个基线系统和多模态大型语言模型（MLLMs）的评估表明，它们在所有任务上表现欠佳，揭示了长时第一人称视频理解的内在挑战，并凸显了开发更先进模型的迫切需求。

> Long-form egocentric video understanding provides rich contextual information and unique insights into long-term human behaviors, holding significant potential for applications in embodied intelligence, long-term activity analysis, and personalized assistive technologies. However, existing benchmark datasets primarily focus on single, short-duration videos or moderately long videos up to dozens of minutes, leaving a substantial gap in evaluating extensive, ultra-long egocentric video recordings. To address this, we introduce X-LeBench, a novel benchmark dataset specifically crafted for evaluating tasks on extremely long egocentric video recordings. Leveraging the advanced text processing capabilities of large language models (LLMs), X-LeBench develops a life-logging simulation pipeline that produces realistic, coherent daily plans aligned with real-world video data. This approach enables the flexible integration of synthetic daily plans with real-world footage from Ego4D-a massive-scale egocentric video dataset covers a wide range of daily life scenarios-resulting in 432 simulated video life logs that mirror realistic daily activities in contextually rich scenarios. The video life-log durations span from 23 minutes to 16.4 hours. The evaluation of several baseline systems and multimodal large language models (MLLMs) reveals their poor performance across the board, highlighting the inherent challenges of long-form egocentric video understanding and underscoring the need for more advanced models.

[Arxiv](https://arxiv.org/abs/2501.06835)