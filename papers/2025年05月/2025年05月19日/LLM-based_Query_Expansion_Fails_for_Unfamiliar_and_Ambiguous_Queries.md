# 基于 LLM 的查询扩展在面对不熟悉和模糊的查询时表现不佳

发布时间：2025年05月19日

`LLM应用` `信息检索`

> LLM-based Query Expansion Fails for Unfamiliar and Ambiguous Queries

# 摘要

> 查询扩展（QE）通过引入相关术语来提升检索效果，大型语言模型（LLMs）为传统基于规则和统计的方法提供了一种有效的替代方案。然而，基于LLMs的QE存在一个根本性限制：它常常无法生成相关知识，从而降低搜索性能。先前的研究集中于幻觉现象，但其根本原因——LLMs的知识不足——仍未得到充分探索。本文系统性地研究了基于LLMs的QE中的两个失败案例：（1）当LLMs缺乏查询相关的知识时，导致错误的扩展；（2）当查询存在歧义时，引发有偏颇的优化，从而缩小搜索范围。我们在多个数据集上进行了受控实验，评估了知识和查询歧义对稀疏和密集检索模型检索性能的影响。我们的结果显示，当LLMs的知识不足或查询歧义较高时，基于LLMs的QE会显著降低检索效果。我们提出了一种在这些条件下评估QE的框架，揭示了基于LLMs的检索增强的局限性。

> Query expansion (QE) enhances retrieval by incorporating relevant terms, with large language models (LLMs) offering an effective alternative to traditional rule-based and statistical methods. However, LLM-based QE suffers from a fundamental limitation: it often fails to generate relevant knowledge, degrading search performance. Prior studies have focused on hallucination, yet its underlying cause--LLM knowledge deficiencies--remains underexplored. This paper systematically examines two failure cases in LLM-based QE: (1) when the LLM lacks query knowledge, leading to incorrect expansions, and (2) when the query is ambiguous, causing biased refinements that narrow search coverage. We conduct controlled experiments across multiple datasets, evaluating the effects of knowledge and query ambiguity on retrieval performance using sparse and dense retrieval models. Our results reveal that LLM-based QE can significantly degrade the retrieval effectiveness when knowledge in the LLM is insufficient or query ambiguity is high. We introduce a framework for evaluating QE under these conditions, providing insights into the limitations of LLM-based retrieval augmentation.

[Arxiv](https://arxiv.org/abs/2505.12694)