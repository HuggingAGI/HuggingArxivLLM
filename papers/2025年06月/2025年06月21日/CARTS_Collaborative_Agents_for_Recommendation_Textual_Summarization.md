# CARTS: 协作智能体实现推荐文本摘要

发布时间：2025年06月21日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLM）应用于推荐系统的文本摘要任务。虽然论文中提到了多智能体框架，但其核心内容是关于如何利用LLM来生成与商品核心特征高度相关的简洁标题，并在实际应用中取得了显著效果。因此，这篇论文更符合LLM应用的分类。` `推荐系统` `电子商务`

> CARTS: Collaborative Agents for Recommendation Textual Summarization

# 摘要

> 推荐系统往往需要文本数据摘要支持，例如为商品轮播或分组展示生成简洁且连贯的标题。虽然大型语言模型在文本摘要方面展现出潜力，但现有方法无法直接应用于推荐系统，因为解释需与商品核心特征高度相关并严格控制字数。本文提出CARTS（推荐文本摘要的协作式智能体），一种专为推荐系统设计的多智能体LLM框架，用于结构化摘要任务。CARTS将任务分解为三个阶段：生成增强生成（GAG）、 refinement circle和仲裁。各阶段智能体分别负责提取商品特征、迭代优化候选标题以及通过协作仲裁确定最终标题。在大规模电商数据和实时A/B测试中，CARTS显著超越传统LLM模型，实现了更高的标题相关性和更好的用户互动效果。

> Current recommendation systems often require some form of textual data summarization, such as generating concise and coherent titles for product carousels or other grouped item displays. While large language models have shown promise in NLP domains for textual summarization, these approaches do not directly apply to recommendation systems, where explanations must be highly relevant to the core features of item sets, adhere to strict word limit constraints. In this paper, we propose CARTS (Collaborative Agents for Recommendation Textual Summarization), a multi-agent LLM framework designed for structured summarization in recommendation systems. CARTS decomposes the task into three stages-Generation Augmented Generation (GAG), refinement circle, and arbitration, where successive agent roles are responsible for extracting salient item features, iteratively refining candidate titles based on relevance and length feedback, and selecting the final title through a collaborative arbitration process. Experiments on large-scale e-commerce data and live A/B testing show that CARTS significantly outperforms single-pass and chain-of-thought LLM baselines, delivering higher title relevance and improved user engagement metrics.

[Arxiv](https://arxiv.org/abs/2506.17765)