# NAVCON：一个具有认知启发且基于语言的视觉与语言导航语料库

发布时间：2024年12月17日

`LLM应用` `视觉语言导航` `人工智能`

> NAVCON: A Cognitively Inspired and Linguistically Grounded Corpus for Vision and Language Navigation

# 摘要

> 我们推出了 NAVCON，这是在两个热门数据集（R2R 和 RxR）基础上构建的大规模有标注的视觉语言导航（VLN）语料库。此文介绍了四个核心的、出于认知动机且基于语言的导航概念，以及一种为导航指令中这些概念的自然语言表达生成大规模银质标注的算法。我们把标注后的指令与执行这些指令的代理的视频片段进行配对。NAVCON 涵盖约 30 万条指令，包含 236,316 个概念标注，还有 270 万张对齐的图像（来自约 19,000 条指令），展现了代理执行指令时所看到的景象。据我们了解，这是首个导航概念的综合资源。我们通过对 NAVCON 样本开展人类评估研究来评定银质标注的质量。为进一步验证该资源的质量和实用性，我们训练了一个用于检测未曾见过的指令中的导航概念及其语言表达的模型。另外，我们发现，利用 NAVCON 的大规模银质标注，GPT-4o 的少样本学习在这项任务中表现出色。

> We present NAVCON, a large-scale annotated Vision-Language Navigation (VLN) corpus built on top of two popular datasets (R2R and RxR). The paper introduces four core, cognitively motivated and linguistically grounded, navigation concepts and an algorithm for generating large-scale silver annotations of naturally occurring linguistic realizations of these concepts in navigation instructions. We pair the annotated instructions with video clips of an agent acting on these instructions. NAVCON contains 236, 316 concept annotations for approximately 30, 0000 instructions and 2.7 million aligned images (from approximately 19, 000 instructions) showing what the agent sees when executing an instruction. To our knowledge, this is the first comprehensive resource of navigation concepts. We evaluated the quality of the silver annotations by conducting human evaluation studies on NAVCON samples. As further validation of the quality and usefulness of the resource, we trained a model for detecting navigation concepts and their linguistic realizations in unseen instructions. Additionally, we show that few-shot learning with GPT-4o performs well on this task using large-scale silver annotations of NAVCON.

[Arxiv](https://arxiv.org/abs/2412.13026)