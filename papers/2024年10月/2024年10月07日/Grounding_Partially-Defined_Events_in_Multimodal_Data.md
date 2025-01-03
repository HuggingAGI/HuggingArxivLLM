# 在多模态数据中定位部分定义的事件

发布时间：2024年10月07日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）进行多模态事件分析，特别是在处理非结构化视频数据时。论文提出了一种多模态公式和一系列LLM驱动的方法来解决事件建模的难题，并在一个基准数据集上进行了评估。这些内容明显属于LLM在实际应用中的使用，因此分类为“LLM应用”。` `事件分析`

> Grounding Partially-Defined Events in Multimodal Data

# 摘要

> 我们如何仅凭短视频片段就能洞悉复杂的时事？尽管自然语言能轻松表达未完全明确、部分可观察的事件，但视觉数据却难以做到，这给事件理解带来了独特挑战。随着具备视觉能力的AI代理日益普及，这些系统必须能从非结构化视频数据中建模事件。为应对多模态环境中的事件建模难题，我们提出了一种多模态公式，用于表示部分定义的事件，并将其提取任务转化为三阶段跨度检索。我们为此任务设计了一个基准——MultiVENT-G，包含14.5小时密集注释的时事视频和1,168份文本文档，涵盖22.8K个事件中心实体。我们提出了一系列LLM驱动的方法进行多模态事件分析，并在MultiVENT-G上进行了评估。结果揭示了抽象事件理解的挑战，并展现了事件中心视频-语言系统的潜力。

> How are we able to learn about complex current events just from short snippets of video? While natural language enables straightforward ways to represent under-specified, partially observable events, visual data does not facilitate analogous methods and, consequently, introduces unique challenges in event understanding. With the growing prevalence of vision-capable AI agents, these systems must be able to model events from collections of unstructured video data. To tackle robust event modeling in multimodal settings, we introduce a multimodal formulation for partially-defined events and cast the extraction of these events as a three-stage span retrieval task. We propose a corresponding benchmark for this task, MultiVENT-G, that consists of 14.5 hours of densely annotated current event videos and 1,168 text documents, containing 22.8K labeled event-centric entities. We propose a collection of LLM-driven approaches to the task of multimodal event analysis, and evaluate them on MultiVENT-G. Results illustrate the challenges that abstract event understanding poses and demonstrates promise in event-centric video-language systems.

[Arxiv](https://arxiv.org/abs/2410.05267)