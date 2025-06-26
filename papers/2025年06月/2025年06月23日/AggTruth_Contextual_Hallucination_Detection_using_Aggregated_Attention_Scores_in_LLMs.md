# AggTruth：基于LLMs中聚合注意力分数的上下文幻觉检测

发布时间：2025年06月23日

`RAG` `人工智能`

> AggTruth: Contextual Hallucination Detection using Aggregated Attention Scores in LLMs

# 摘要

> 大型语言模型（LLMs）在现实应用中经常出现幻觉现象，即使是在检索增强生成（RAG）设置下，这对模型的部署带来了重大挑战。本文介绍了一种名为AggTruth的方法，通过分析上下文（段落）中内部注意力分数的分布，实现对上下文幻觉的在线检测。具体来说，我们提出了四种不同的方法变体，每种变体采用了不同的注意力分数聚合技术。在所有研究的LLMs中，AggTruth在同任务和跨任务设置下均表现出稳定性能，并在多个场景下超越了当前最优方法。此外，我们深入分析了特征选择技术，并探讨了所选注意力头数量对检测性能的影响，证明了仔细选择注意力头是获得最佳结果的关键。
    

> In real-world applications, Large Language Models (LLMs) often hallucinate, even in Retrieval-Augmented Generation (RAG) settings, which poses a significant challenge to their deployment. In this paper, we introduce AggTruth, a method for online detection of contextual hallucinations by analyzing the distribution of internal attention scores in the provided context (passage). Specifically, we propose four different variants of the method, each varying in the aggregation technique used to calculate attention scores. Across all LLMs examined, AggTruth demonstrated stable performance in both same-task and cross-task setups, outperforming the current SOTA in multiple scenarios. Furthermore, we conducted an in-depth analysis of feature selection techniques and examined how the number of selected attention heads impacts detection performance, demonstrating that careful selection of heads is essential to achieve optimal results.

[Arxiv](https://arxiv.org/abs/2506.18628)