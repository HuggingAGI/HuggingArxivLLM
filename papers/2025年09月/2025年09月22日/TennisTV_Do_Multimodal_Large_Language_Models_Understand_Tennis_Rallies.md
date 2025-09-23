# TennisTV：多模态大语言模型能否理解网球回合？

发布时间：2025年09月22日

`LLM应用` `媒体与娱乐`

> TennisTV: Do Multimodal Large Language Models Understand Tennis Rallies?

# 摘要

> 多模态大型语言模型（MLLMs）擅长通用视频理解，却难以应对网球这类快速高频运动——其回合片段虽短，信息密度却极高。为了在这一极具挑战性的领域系统评估MLLMs，我们推出了TennisTV——首个且最全面的网球视频理解基准。TennisTV将每个回合建模为连续击球事件的时间有序序列，通过自动化流水线完成过滤与问题生成。该基准涵盖回合与击球两个层级的8项任务，包含2500个人工验证的问题。我们评估了16个代表性MLLMs，首次对网球视频理解能力进行了系统性评估。结果揭示了MLLMs存在显著不足，并提炼出两个关键发现：（i）帧采样密度需针对不同任务进行定制与平衡；（ii）提升时间定位能力是增强推理性能的关键。

> Multimodal large language models (MLLMs) excel at general video understanding but struggle with fast, high-frequency sports like tennis, where rally clips are short yet information-dense. To systematically evaluate MLLMs in this challenging domain, we present TennisTV, the first and most comprehensive benchmark for tennis video understanding. TennisTV models each rally as a temporal-ordered sequence of consecutive stroke events, using automated pipelines for filtering and question generation. It covers 9 tasks from the stroke level to the rally level and includes 2943 human-verified questions. Evaluating 17 representative MLLMs, we provide the first systematic assessment of tennis video understanding. Results reveal substantial shortcomings and yield two key insights: (i) frame-sampling density should be tailored and balanced across tasks, and (ii) improving temporal grounding is essential for stronger reasoning.

[Arxiv](https://arxiv.org/abs/2509.15602)