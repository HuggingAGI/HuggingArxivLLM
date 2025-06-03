# LEMONADE：应用于现实世界的大型多语言专家标注摘要事件数据集

发布时间：2025年06月01日

`LLM应用` `全球事件分析` `冲突研究`

> LEMONADE: A Large Multilingual Expert-Annotated Abstractive Event Dataset for the Real World

# 摘要

> 本文介绍了 LEMONADE，一个包含 20 种语言、171 个国家和地区特有实体的大型冲突事件数据集，总计收录了 39,786 个事件。LEMONADE 基于部分重新标注的武装冲突位置与事件数据（ACLED）子集构建，该数据集记录了全球冲突事件已有十余年。为应对多语言来源整合用于全球事件分析的挑战，我们提出了摘要式事件抽取（AEE）及其子任务摘要式实体链接（AEL）。与传统的基于跨度的事件抽取不同，我们的方法通过整体文档理解检测事件论元和实体，并在多语言数据集中对其进行标准化。我们评估了多种大型语言模型（LLMs）在这些任务上的表现，调整了现有的零样本事件抽取系统，并对监督模型进行了基准测试。此外，我们引入了 ZEST，一个基于检索的新型零样本系统，用于 AEL。我们最佳的零样本系统在端到端任务中实现了 58.3% 的 F1 分数，且 LLMs 的表现优于专门的事件抽取模型如 GoLLIE。在实体链接方面，ZEST 达到了 45.7% 的 F1 分数，显著超越了仅实现 23.7% 的先进零样本基线 OneNet。然而，这些零样本结果分别落后于最佳监督系统在端到端和 AEL 任务中的表现 20.1% 和 37.0%，凸显了进一步研究的必要性。

> This paper presents LEMONADE, a large-scale conflict event dataset comprising 39,786 events across 20 languages and 171 countries, with extensive coverage of region-specific entities. LEMONADE is based on a partially reannotated subset of the Armed Conflict Location & Event Data (ACLED), which has documented global conflict events for over a decade.
  To address the challenge of aggregating multilingual sources for global event analysis, we introduce abstractive event extraction (AEE) and its subtask, abstractive entity linking (AEL). Unlike conventional span-based event extraction, our approach detects event arguments and entities through holistic document understanding and normalizes them across the multilingual dataset. We evaluate various large language models (LLMs) on these tasks, adapt existing zero-shot event extraction systems, and benchmark supervised models. Additionally, we introduce ZEST, a novel zero-shot retrieval-based system for AEL.
  Our best zero-shot system achieves an end-to-end F1 score of 58.3%, with LLMs outperforming specialized event extraction models such as GoLLIE. For entity linking, ZEST achieves an F1 score of 45.7%, significantly surpassing OneNet, a state-of-the-art zero-shot baseline that achieves only 23.7%. However, these zero-shot results lag behind the best supervised systems by 20.1% and 37.0% in the end-to-end and AEL tasks, respectively, highlighting the need for further research.

[Arxiv](https://arxiv.org/abs/2506.00980)