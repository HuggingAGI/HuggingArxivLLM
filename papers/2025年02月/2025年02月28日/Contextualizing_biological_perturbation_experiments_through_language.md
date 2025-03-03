# 通过语言理解生物扰动实验的情境

发布时间：2025年02月28日

`LLM应用` `生物科学` `生物医学`

> Contextualizing biological perturbation experiments through language

# 摘要

> 高内涵扰动实验让科学家能够以前所未有的分辨率探索生物分子系统，但高昂的实验和分析成本限制了其广泛应用。机器学习有望通过优化扰动空间的探索并挖掘数据中的新见解来改变这一现状。然而，现有方法未能充分利用生物学的丰富语义，且其目标与实际生物分析需求脱节。我们提出，大型语言模型（LLMs）为理解和解释复杂的生物关系及其实验结果提供了一种天然的解决方案。为此，我们开发了PerturbQA，一个专注于扰动实验的结构化推理基准。与现有基准主要聚焦于验证已有知识不同，PerturbQA针对扰动建模中的开放性问题进行了设计，包括预测未见扰动的差异表达和方向变化，以及基因集富集分析。我们对当前最先进的机器学习和统计方法，以及标准的LLM推理策略进行了全面评估，发现现有方法在PerturbQA上表现欠佳。为证明这一方法的可行性，我们开发了Summer框架（SUMMarize, retrievE, and answeR），这是一个简单而高效的领域专用LLM框架，在性能上达到了甚至超越了当前最先进水平。我们的代码和数据已公开发布于https://github.com/genentech/PerturbQA。


> High-content perturbation experiments allow scientists to probe biomolecular systems at unprecedented resolution, but experimental and analysis costs pose significant barriers to widespread adoption. Machine learning has the potential to guide efficient exploration of the perturbation space and extract novel insights from these data. However, current approaches neglect the semantic richness of the relevant biology, and their objectives are misaligned with downstream biological analyses. In this paper, we hypothesize that large language models (LLMs) present a natural medium for representing complex biological relationships and rationalizing experimental outcomes. We propose PerturbQA, a benchmark for structured reasoning over perturbation experiments. Unlike current benchmarks that primarily interrogate existing knowledge, PerturbQA is inspired by open problems in perturbation modeling: prediction of differential expression and change of direction for unseen perturbations, and gene set enrichment. We evaluate state-of-the-art machine learning and statistical approaches for modeling perturbations, as well as standard LLM reasoning strategies, and we find that current methods perform poorly on PerturbQA. As a proof of feasibility, we introduce Summer (SUMMarize, retrievE, and answeR, a simple, domain-informed LLM framework that matches or exceeds the current state-of-the-art. Our code and data are publicly available at https://github.com/genentech/PerturbQA.

[Arxiv](https://arxiv.org/abs/2502.21290)