# SciSage：一个多智能体框架，生成高质量科学综述

发布时间：2025年06月14日

`Agent` `科学研究` `人工智能`

> SciSage: A Multi-Agent Framework for High-Quality Scientific Survey Generation

# 摘要

> 面对科学文献的迅猛增长，自动化综述生成工具亟需升级。现有基于大语言模型的方法在深度分析、结构连贯性和引用可靠性方面仍有不足。为此，我们推出SciSage——一个采用边写边反思范式的多智能体框架。SciSage搭载分层反思代理，能从大纲、章节到整篇文档的层面，对草稿进行全方位评估，并与专门负责查询解析、内容检索和优化的智能体协同工作。同时，我们发布了SurveyScope——一个经过严格筛选的基准测试集，涵盖11个计算机科学领域2020至2025年间最具影响力的46篇论文，实施了严格的时效性和基于引用的质量控制。评估结果显示，SciSage在文档连贯性和引用准确性方面显著优于现有最先进的基准方法，分别提升了1.73分和32%的F1分数。人工评估显示，尽管在7项对比中略逊于人工撰写综述，但SciSage在主题广度和检索效率方面具有明显优势。总体而言，SciSage为研究辅助写作工具提供了一个极具潜力的基础架构。

> The rapid growth of scientific literature demands robust tools for automated survey-generation. However, current large language model (LLM)-based methods often lack in-depth analysis, structural coherence, and reliable citations. To address these limitations, we introduce SciSage, a multi-agent framework employing a reflect-when-you-write paradigm. SciSage features a hierarchical Reflector agent that critically evaluates drafts at outline, section, and document levels, collaborating with specialized agents for query interpretation, content retrieval, and refinement. We also release SurveyScope, a rigorously curated benchmark of 46 high-impact papers (2020-2025) across 11 computer science domains, with strict recency and citation-based quality controls. Evaluations demonstrate that SciSage outperforms state-of-the-art baselines (LLM x MapReduce-V2, AutoSurvey), achieving +1.73 points in document coherence and +32% in citation F1 scores. Human evaluations reveal mixed outcomes (3 wins vs. 7 losses against human-written surveys), but highlight SciSage's strengths in topical breadth and retrieval efficiency. Overall, SciSage offers a promising foundation for research-assistive writing tools.

[Arxiv](https://arxiv.org/abs/2506.12689)