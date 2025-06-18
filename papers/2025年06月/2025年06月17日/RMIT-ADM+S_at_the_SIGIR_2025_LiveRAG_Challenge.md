# RMIT-ADM+S在SIGIR 2025 LiveRAG挑战中

发布时间：2025年06月17日

`RAG` `信息检索`

> RMIT-ADM+S at the SIGIR 2025 LiveRAG Challenge

# 摘要

> 本文介绍了RMIT--ADM+S团队在SIGIR 2025 LiveRAG挑战中的参赛情况。我们的生成-检索增强生成（GRAG）方法基于生成一个假设性的答案，并在检索阶段与原始问题一同使用。GRAG还引入了一个基于点式大型语言模型（LLM）的重新排序步骤，该步骤在最终答案生成之前进行。我们描述了系统架构以及设计选择的依据。特别地，通过使用点阵框架（Grid of Points, GoP）和N因子方差分析（N-way ANOVA）进行的系统性评估，我们能够在多个配置之间进行比较，包括查询变体生成、问题分解、排名融合策略以及答案生成的提示技术。我们的系统在私人排行榜上获得了1.199的相关性得分和0.477的忠实度得分，并在LiveRAG 2025挑战中跻身前四名。

> This paper presents the RMIT--ADM+S participation in the SIGIR 2025 LiveRAG Challenge. Our Generation-Retrieval-Augmented Generation (GRAG) approach relies on generating a hypothetical answer that is used in the retrieval phase, alongside the original question. GRAG also incorporates a pointwise large language model (LLM)-based re-ranking step prior to final answer generation. We describe the system architecture and the rationale behind our design choices. In particular, a systematic evaluation using the Grid of Points (GoP) framework and N-way ANOVA enabled comparison across multiple configurations, including query variant generation, question decomposition, rank fusion strategies, and prompting techniques for answer generation. Our system achieved a Relevance score of 1.199 and a Faithfulness score of 0.477 on the private leaderboard, placing among the top four finalists in the LiveRAG 2025 Challenge.

[Arxiv](https://arxiv.org/abs/2506.14516)