# IterQR: 基于LLM的迭代查询改写框架在电子商务搜索系统中的应用

发布时间：2025年02月16日

`LLM应用` `电子商务` `搜索系统`

> IterQR: An Iterative Framework for LLM-based Query Rewrite in e-Commercial Search System

# 摘要

> 现代电子 commerce 搜索系统的核心在于根据用户的查询，匹配用户的意图和可用候选，提供个性化和精准的服务。然而，用户的查询可能由于输入模糊或拼写错误而不准确，导致搜索结果不准确。这些情况可以通过查询改写来解决：将查询修改为其他表示形式或扩展。然而，传统的查询改写依赖于静态的改写词汇表，该词汇表是人工建立的，同时缺乏与电子 commerce 系统中的领域知识以及现实世界中的常识的互动。在本文中，借助大型语言模型 (LLMs) 生成文本内容的能力，我们提供了一个迭代的框架来生成查询改写。该框架在每次迭代中包含一个三阶段的过程：通过检索增强生成 (RAG) 和链式思维 (CoT) 进行基于领域知识的改写生成和查询理解；在线信号收集并自动更新正面改写；以及通过多任务目标对 LLM 进行后训练以生成新的改写。我们的工作（命名为 IterQR）提供了一个全面的框架，利用领域 / 现实世界知识生成 	extbf{Q}uery 	extbf{R}ewrite。它在 	extbf{iter}ations 过程中自动更新和自我修正改写。该方法已部署在美团外卖的搜索系统（中国领先的食品配送平台），为用户提供服务，显著提升了搜索效果。

> The essence of modern e-Commercial search system lies in matching user's intent and available candidates depending on user's query, providing personalized and precise service. However, user's query may be incorrect due to ambiguous input and typo, leading to inaccurate search. These cases may be released by query rewrite: modify query to other representation or expansion. However, traditional query rewrite replies on static rewrite vocabulary, which is manually established meanwhile lacks interaction with both domain knowledge in e-Commercial system and common knowledge in the real world. In this paper, with the ability to generate text content of Large Language Models (LLMs), we provide an iterative framework to generate query rewrite. The framework incorporates a 3-stage procedure in each iteration: Rewrite Generation with domain knowledge by Retrieval-Augmented Generation (RAG) and query understanding by Chain-of-Thoughts (CoT); Online Signal Collection with automatic positive rewrite update; Post-training of LLM with multi task objective to generate new rewrites. Our work (named as IterQR) provides a comprehensive framework to generate \textbf{Q}uery \textbf{R}ewrite with both domain / real-world knowledge. It automatically update and self-correct the rewrites during \textbf{iter}ations. \method{} has been deployed in Meituan Delivery's search system (China's leading food delivery platform), providing service for users with significant improvement.

[Arxiv](https://arxiv.org/abs/2504.05309)