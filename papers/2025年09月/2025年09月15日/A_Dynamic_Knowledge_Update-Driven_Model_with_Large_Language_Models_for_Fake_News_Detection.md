# 一种基于大型语言模型的动态知识更新驱动虚假新闻检测模型

发布时间：2025年09月15日

`RAG` `媒体与娱乐`

> A Dynamic Knowledge Update-Driven Model with Large Language Models for Fake News Detection

# 摘要

> 随着互联网与社交媒体的迅猛发展，如何从海量复杂信息中辨别可信新闻已成为一大难题。新闻事件往往突发且多变，其真实性标签可能随事件发展而动态变化，因此获取最新事件进展对假新闻检测而言尤为关键。现有方法多采用检索增强生成技术填补知识空白，却面临检索内容可信度不足、嘈杂信息干扰等问题。为此，我们提出动态知识更新驱动的假新闻检测模型（DYNAMO）。该模型借助知识图谱实现新知识的持续更新，并与大型语言模型融合，具备双重功能——新闻真实性检测与新知识正确性验证，从而解决了确保新知识真实性和深度挖掘新闻语义这两大关键问题。具体而言，我们首先构建新闻领域专用知识图谱；接着，通过蒙特卡洛树搜索对复杂新闻进行分解并逐步验证；最后，从已验证的真实新闻文本及推理路径中提取并更新新知识。实验结果显示，DYNAMO在两个真实世界数据集上均表现最优。

> As the Internet and social media evolve rapidly, distinguishing credible news from a vast amount of complex information poses a significant challenge. Due to the suddenness and instability of news events, the authenticity labels of news can potentially shift as events develop, making it crucial for fake news detection to obtain the latest event updates. Existing methods employ retrieval-augmented generation to fill knowledge gaps, but they suffer from issues such as insufficient credibility of retrieved content and interference from noisy information. We propose a dynamic knowledge update-driven model for fake news detection (DYNAMO), which leverages knowledge graphs to achieve continuous updating of new knowledge and integrates with large language models to fulfill dual functions: news authenticity detection and verification of new knowledge correctness, solving the two key problems of ensuring the authenticity of new knowledge and deeply mining news semantics. Specifically, we first construct a news-domain-specific knowledge graph. Then, we use Monte Carlo Tree Search to decompose complex news and verify them step by step. Finally, we extract and update new knowledge from verified real news texts and reasoning paths. Experimental results demonstrate that DYNAMO achieves the best performance on two real-world datasets.

[Arxiv](https://arxiv.org/abs/2509.11687)