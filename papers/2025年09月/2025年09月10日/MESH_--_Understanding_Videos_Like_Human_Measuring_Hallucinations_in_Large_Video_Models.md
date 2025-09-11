# MESH——以人类视角理解视频：大型视频模型幻觉测量研究

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> MESH -- Understanding Videos Like Human: Measuring Hallucinations in Large Video Models

# 摘要

> 大型视频模型（LVMs）依托大型语言模型（LLMs）与视觉模块的语义理解能力，整合时间维度信息，从而更精准地解析动态视频内容。然而，LVMs仍难逃“幻觉”问题——时常生成不准确或不相关的描述。现有视频幻觉评估基准过度依赖人工对视频内容的分类，却忽略了人类解读视频时天然依赖的感知过程。为此，我们提出MESH基准，专门用于系统评估LVMs的幻觉问题。MESH采用问答框架，结合二选一与多选题形式，融入目标实例与陷阱实例；并通过自底向上的评估思路，依次考察基本物体、主体特征（从粗到细）以及主体-动作对，与人类视频理解逻辑相契合。实验表明，MESH为识别视频幻觉提供了高效且全面的解决方案。评估结果显示，尽管LVMs在识别基本物体和特征方面表现优异，但在处理细节信息，或在较长视频中对齐涉及多个主体的复杂动作时，其幻觉倾向会显著上升。

> Large Video Models (LVMs) build on the semantic capabilities of Large Language Models (LLMs) and vision modules by integrating temporal information to better understand dynamic video content. Despite their progress, LVMs are prone to hallucinations-producing inaccurate or irrelevant descriptions. Current benchmarks for video hallucination depend heavily on manual categorization of video content, neglecting the perception-based processes through which humans naturally interpret videos. We introduce MESH, a benchmark designed to evaluate hallucinations in LVMs systematically. MESH uses a Question-Answering framework with binary and multi-choice formats incorporating target and trap instances. It follows a bottom-up approach, evaluating basic objects, coarse-to-fine subject features, and subject-action pairs, aligning with human video understanding. We demonstrate that MESH offers an effective and comprehensive approach for identifying hallucinations in videos. Our evaluations show that while LVMs excel at recognizing basic objects and features, their susceptibility to hallucinations increases markedly when handling fine details or aligning multiple actions involving various subjects in longer videos.

[Arxiv](https://arxiv.org/abs/2509.08538)