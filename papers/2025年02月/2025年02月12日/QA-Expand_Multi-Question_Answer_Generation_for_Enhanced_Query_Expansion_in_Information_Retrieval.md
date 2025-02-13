# 多问题答案生成方法 QA-Expand：助力信息检索中的查询扩展优化

发布时间：2025年02月12日

`LLM应用` `信息检索` `问答系统`

> QA-Expand: Multi-Question Answer Generation for Enhanced Query Expansion in Information Retrieval

# 摘要

> 查询扩展在信息检索领域被广泛应用，通过为查询添加额外的上下文信息来提升搜索效果。尽管基于LLM的方法能够通过多个提示生成伪相关内容和扩展项，但这些方法往往产生重复且范围狭窄的扩展，缺乏多样化的背景信息，难以检索到所有相关结果。本文提出了一种新颖且有效的查询扩展框架——QA-Expand。该框架首先从初始查询生成多个相关问题，随后为这些问题生成对应的伪答案作为替代文档。通过反馈模型进一步优化和筛选这些答案，确保仅保留最有价值的补充信息。在BEIR和TREC等基准测试中的大量实验证明，与现有最优方法相比，QA-Expand将检索性能提升了高达13%，为应对现代检索挑战提供了有力的解决方案。

> Query expansion is widely used in Information Retrieval (IR) to improve search outcomes by enriching queries with additional contextual information. Although recent Large Language Model (LLM) based methods generate pseudo-relevant content and expanded terms via multiple prompts, they often yield repetitive, narrow expansions that lack the diverse context needed to retrieve all relevant information. In this paper, we introduce QA-Expand, a novel and effective framework for query expansion. It first generates multiple relevant questions from the initial query and subsequently produces corresponding pseudo-answers as surrogate documents. A feedback model further rewrites and filters these answers to ensure only the most informative augmentations are incorporated. Extensive experiments on benchmarks such as BEIR and TREC demonstrate that QA-Expand enhances retrieval performance by up to 13% over state-of-the-art methods, offering a robust solution for modern retrieval challenges.

[Arxiv](https://arxiv.org/abs/2502.08557)