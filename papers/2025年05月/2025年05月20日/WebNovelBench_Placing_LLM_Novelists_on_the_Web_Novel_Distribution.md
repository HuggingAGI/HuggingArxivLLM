# WebNovelBench：让 LLM 小说家在网络小说分发领域大显身手

发布时间：2025年05月20日

`LLM应用

摘要讨论了评估大型语言模型（LLMs）在长篇叙事生成中的应用，介绍了新的基准测试WebNovelBench，并分析了其在评估LLM叙事能力中的作用。因此，这篇论文属于LLM应用类别。`

> WebNovelBench: Placing LLM Novelists on the Web Novel Distribution

# 摘要

> 评估大型语言模型（LLMs）的长篇叙事能力仍是一个重大挑战，因为现有基准测试往往缺乏规模、多样性和客观衡量标准。为此，我们推出了WebNovelBench——首个专注于长篇小说生成评估的基准测试。该基准基于一个包含4,000多部中文网络小说的大型数据集，将评估转化为从情节概要到完整故事生成的任务。我们提出了一个多维度框架，涵盖八个叙事质量维度，并通过LLM作为评估者进行自动评估。评分经主成分分析（Principal Component Analysis）聚合后，与人类作品进行百分位排名对比。实验结果表明，WebNovelBench能有效区分人类经典作品、热门网络小说和LLM生成内容。我们对24个先进LLMs进行了全面分析，对其叙事能力进行了排名，并为未来发展提供了见解。这一基准测试为评估和提升LLM驱动的叙事生成提供了一种可扩展、可重复且数据驱动的方法论。

> Robustly evaluating the long-form storytelling capabilities of Large Language Models (LLMs) remains a significant challenge, as existing benchmarks often lack the necessary scale, diversity, or objective measures. To address this, we introduce WebNovelBench, a novel benchmark specifically designed for evaluating long-form novel generation. WebNovelBench leverages a large-scale dataset of over 4,000 Chinese web novels, framing evaluation as a synopsis-to-story generation task. We propose a multi-faceted framework encompassing eight narrative quality dimensions, assessed automatically via an LLM-as-Judge approach. Scores are aggregated using Principal Component Analysis and mapped to a percentile rank against human-authored works. Our experiments demonstrate that WebNovelBench effectively differentiates between human-written masterpieces, popular web novels, and LLM-generated content. We provide a comprehensive analysis of 24 state-of-the-art LLMs, ranking their storytelling abilities and offering insights for future development. This benchmark provides a scalable, replicable, and data-driven methodology for assessing and advancing LLM-driven narrative generation.

[Arxiv](https://arxiv.org/abs/2505.14818)