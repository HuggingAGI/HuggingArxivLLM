# 分层超长小说生成中的信息失真测量：最优扩展比率

发布时间：2025年05月18日

`LLM应用` `文学创作`

> Measuring Information Distortion in Hierarchical Ultra long Novel Generation:The Optimal Expansion Ratio

# 摘要

> 用大型语言模型 (LLMs) 写小说，有个关键问题值得探讨：要写出百万字的高质量小说，需要多详细的人工编写提纲？尽管 DOME、Plan&Write 和 Long Writer 等框架在提升文风连贯性和逻辑一致性方面有所突破，但它们主要针对的是 1 万至 10 万字的中短篇小说，对超长篇小说的创作仍是个未解之谜。我们从 LLMZip 和 LLM2Vec 等近期文本压缩方法中汲取灵感，通过信息论分析，量化了 LLMs 在不同压缩-扩展比率下压缩和重构超长小说时的失真程度。我们提出了一种分层两阶段生成流程（提纲 -> 详细提纲 -> 稿件），并找到了一个既能保留信息又不增加过多人工投入的最佳提纲长度。通过对中文小说的大量实验，我们发现，与传统的单阶段方法相比，这种分层两阶段提纲方法能显著降低语义失真。我们的研究发现为作者和研究人员与 LLMs 协作创作百万字小说提供了实证依据的指导。


> Writing novels with Large Language Models (LLMs) raises a critical question: how much human-authored outline is necessary to generate high-quality million-word novels? While frameworks such as DOME, Plan&Write, and Long Writer have improved stylistic coherence and logical consistency, they primarily target shorter novels (10k--100k words), leaving ultra-long generation largely unexplored. Drawing on insights from recent text compression methods like LLMZip and LLM2Vec, we conduct an information-theoretic analysis that quantifies distortion occurring when LLMs compress and reconstruct ultra-long novels under varying compression-expansion ratios. We introduce a hierarchical two-stage generation pipeline (outline -> detailed outline -> manuscript) and find an optimal outline length that balances information preservation with human effort. Through extensive experimentation with Chinese novels, we establish that a two-stage hierarchical outline approach significantly reduces semantic distortion compared to single-stage methods. Our findings provide empirically-grounded guidance for authors and researchers collaborating with LLMs to create million-word novels.

[Arxiv](https://arxiv.org/abs/2505.12572)