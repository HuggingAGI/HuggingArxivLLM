# # 挖掘可靠指标：提升威胁报告中的 IoC 提取能力

发布时间：2025年06月12日

`LLM应用` `网络安全` `威胁情报`

> Uncovering Reliable Indicators: Improving IoC Extraction from Threat Reports

# 摘要

> 妥协指标（IoCs）是威胁检测和响应中的关键要素，用于标记网络和系统中的恶意活动。然而，自动化IoC提取系统的效果从根本上受限于一个核心问题：缺乏高质量的真实数据。当前的提取工具要么依赖于耗时且昂贵的手动提取真实数据，要么依赖于包含非恶意人工制品的自动化真实数据创建方法，导致误报率（FP）虚高，威胁情报可靠性不足。在本研究中，我们深入分析了现有真实数据创建策略的不足，并通过引入首个混合人机协同的IoC提取管道来解决这些问题，该管道结合了基于大型语言模型的分类器（LANCE）与专家分析师的验证。我们的系统通过可解释且上下文感知的标注方式提高了精确度，并将分析师的工作量减少了43%，相较于手动标注，这一点在我们与六位分析师的评估中得到了验证。通过这种方法，我们生成了PRISM，这是一个高质量、公开可用的基准数据集，包含来自50份真实威胁报告的1,791个标注IoC。PRISM不仅支持IoC提取方法的公平评估和训练，更为基于专家验证指标的研究提供了可重复的基础，推动了威胁检测领域的进一步发展。

> Indicators of Compromise (IoCs) are critical for threat detection and response, marking malicious activity across networks and systems. Yet, the effectiveness of automated IoC extraction systems is fundamentally limited by one key issue: the lack of high-quality ground truth. Current extraction tools rely either on manually extracted ground truth, which is labor-intensive and costly, or on automated ground truth creation methods that include non-malicious artifacts, leading to inflated false positive (FP) rates and unreliable threat intelligence. In this work, we analyze the shortcomings of existing ground truth creation strategies and address them by introducing the first hybrid human-in-the-loop pipeline for IoC extraction, which combines a large language model-based classifier (LANCE) with expert analyst validation. Our system improves precision through explainable, context-aware labeling and reduces analysts' work factor by 43% compared to manual annotation, as demonstrated in our evaluation with six analysts. Using this approach, we produce PRISM, a high-quality, publicly available benchmark of 1,791 labeled IoCs from 50 real-world threat reports. PRISM supports both fair evaluation and training of IoC extraction methods and enables reproducible research grounded in expert-validated indicators.

[Arxiv](https://arxiv.org/abs/2506.11325)