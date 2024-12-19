# RACQUET：揭示视觉LLM中被忽略的指称歧义所带来的危险

发布时间：2024年12月18日

`LLM应用` `语言模型` `多模态`

> RACQUET: Unveiling the Dangers of Overlooked Referential Ambiguity in Visual LLMs

# 摘要

> 歧义的消解是有效交流的关键所在。尽管人类能借助对话基础策略轻松化解歧义，然而当下语言模型能在多大程度上效仿这些策略尚不明确。在本项工作中，我们通过引入 RACQUET 来探究基于图像的问答中的指称歧义，这是一个精心整理的、针对歧义不同方面的数据集。经过一系列评估，我们发现最先进的大型多模态语言模型在处理其回应中的歧义时存在显著的局限性和过度自信的问题。过度自信的问题在 RACQUET-BIAS 中尤为突出，这是一个旨在分析一个关键但未被充分探讨的问题的子集：未能解决歧义会导致产生刻板、带有社会偏见的回应。我们的研究结果凸显了为模型配备强大策略以应对不确定性，同时避免不良刻板印象的迫切性。

> Ambiguity resolution is key to effective communication. While humans effortlessly address ambiguity through conversational grounding strategies, the extent to which current language models can emulate these strategies remains unclear. In this work, we examine referential ambiguity in image-based question answering by introducing RACQUET, a carefully curated dataset targeting distinct aspects of ambiguity. Through a series of evaluations, we reveal significant limitations and problems of overconfidence of state-of-the-art large multimodal language models in addressing ambiguity in their responses. The overconfidence issue becomes particularly relevant for RACQUET-BIAS, a subset designed to analyze a critical yet underexplored problem: failing to address ambiguity leads to stereotypical, socially biased responses. Our results underscore the urgency of equipping models with robust strategies to deal with uncertainty without resorting to undesirable stereotypes.

[Arxiv](https://arxiv.org/abs/2412.13835)