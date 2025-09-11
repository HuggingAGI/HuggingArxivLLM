# SocialNav-SUB：面向社交机器人导航场景理解的视觉语言模型基准测试

发布时间：2025年09月10日

`LLM应用` `工业与制造`

> SocialNav-SUB: Benchmarking VLMs for Scene Understanding in Social Robot Navigation

# 摘要

> 在动态、以人为中心的环境中，机器人导航需基于稳健的场景理解做出符合社交规范的决策。最近的视觉语言模型（VLMs）展现出物体识别、常识推理和上下文理解等潜力——这些能力恰好契合社交机器人导航的细微要求。然而，VLMs能否准确理解复杂的社交导航场景（例如推断智能体间的时空关系及人类意图）仍不明确，而这正是实现安全且符合社交规范的机器人导航的关键。尽管近期已有研究探索VLMs在社交机器人导航中的应用，但尚无工作系统评估其满足这些必要条件的能力。本文提出社交导航场景理解基准（SocialNav-SUB）——一个视觉问答（VQA）数据集与基准，专门用于评估VLMs在真实世界社交机器人导航场景中的场景理解能力。SocialNav-SUB提供统一框架，通过社交机器人导航中需空间、时空及社交推理的VQA任务，将VLMs与人类及基于规则的基线进行对比评估。实验表明，尽管最优VLMs与人类答案的一致性概率尚可，但仍逊于简单的基于规则方法和人类共识基线，暴露出当前VLMs在社交场景理解上的关键短板。该基准为社交机器人导航基础模型的后续研究奠定基础，同时提供框架以探索如何定制VLMs来满足真实世界社交机器人导航需求。本文概述及代码数据详见https://larg.github.io/socialnav-sub。

> Robot navigation in dynamic, human-centered environments requires socially-compliant decisions grounded in robust scene understanding. Recent Vision-Language Models (VLMs) exhibit promising capabilities such as object recognition, common-sense reasoning, and contextual understanding-capabilities that align with the nuanced requirements of social robot navigation. However, it remains unclear whether VLMs can accurately understand complex social navigation scenes (e.g., inferring the spatial-temporal relations among agents and human intentions), which is essential for safe and socially compliant robot navigation. While some recent works have explored the use of VLMs in social robot navigation, no existing work systematically evaluates their ability to meet these necessary conditions. In this paper, we introduce the Social Navigation Scene Understanding Benchmark (SocialNav-SUB), a Visual Question Answering (VQA) dataset and benchmark designed to evaluate VLMs for scene understanding in real-world social robot navigation scenarios. SocialNav-SUB provides a unified framework for evaluating VLMs against human and rule-based baselines across VQA tasks requiring spatial, spatiotemporal, and social reasoning in social robot navigation. Through experiments with state-of-the-art VLMs, we find that while the best-performing VLM achieves an encouraging probability of agreeing with human answers, it still underperforms simpler rule-based approach and human consensus baselines, indicating critical gaps in social scene understanding of current VLMs. Our benchmark sets the stage for further research on foundation models for social robot navigation, offering a framework to explore how VLMs can be tailored to meet real-world social robot navigation needs. An overview of this paper along with the code and data can be found at https://larg.github.io/socialnav-sub .

[Arxiv](https://arxiv.org/abs/2509.08757)