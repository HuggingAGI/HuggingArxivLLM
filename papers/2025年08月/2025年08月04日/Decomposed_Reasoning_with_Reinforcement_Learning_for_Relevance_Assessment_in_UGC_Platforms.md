# 基于强化学习的分解推理用于用户生成内容平台的相关性评估

发布时间：2025年08月04日

`RAG` `用户生成内容` `内容生成`

> Decomposed Reasoning with Reinforcement Learning for Relevance Assessment in UGC Platforms

# 摘要

> 检索增强生成（RAG）在用户生成内容（UGC）平台中至关重要，但其效果取决于对查询-文档相关性的精准评估。尽管大型语言模型（LLMs）在相关性建模方面取得了进展，但UGC平台仍面临两大挑战：1）用户反馈稀疏导致意图模糊；2）非正式语言引入大量噪声。针对这些问题，我们提出强化推理模型（R3A），该模型在评分前采用分解式推理框架。首先，R3A利用平台内高排名文档推断潜在查询意图；其次，通过逐字片段提取验证相关性决策，减少UGC噪声干扰。基于强化学习框架，R3A优化了模糊查询和非结构化内容的处理。实验结果显示，R3A在相关性准确性方面显著超越现有方法，无论是离线测试还是在线实验均表现卓越。

> Retrieval-augmented generation (RAG) plays a critical role in user-generated content (UGC) platforms, but its effectiveness depends heavily on accurate relevance assessment of query-document pairs. Despite recent advances in applying large language models (LLMs) to relevance modeling, UGC platforms present unique challenges: 1) ambiguous user intent due to sparse user feedback in RAG scenarios, and 2) substantial noise introduced by informal and unstructured language. To address these issues, we propose the Reinforced Reasoning Model for Relevance Assessment (R3A), which introduces a decomposed reasoning framework over queries and candidate documents before scoring. R3A first leverages auxiliary high-ranked documents within the platform to infer latent query intent. It then performs verbatim fragment extraction to justify relevance decisions, thereby reducing errors caused by noisy UGC. Based on a reinforcement learning framework, R3A is optimized to mitigate distortions arising from ambiguous queries and unstructured content. Experimental results show that R3A significantly outperforms existing baseline methods in terms of relevance accuracy, across both offline benchmarks and online experiments.

[Arxiv](https://arxiv.org/abs/2508.02506)