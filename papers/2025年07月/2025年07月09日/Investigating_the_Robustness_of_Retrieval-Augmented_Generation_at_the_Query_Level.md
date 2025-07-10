# # 探究检索增强生成在查询级别的鲁棒性
在查询级别研究检索增强生成的鲁棒性

发布时间：2025年07月09日

`RAG` `问答系统`

> Investigating the Robustness of Retrieval-Augmented Generation at the Query Level

# 摘要

> 大型语言模型（LLMs）更新成本高昂且效率低下。为了解决这一问题，我们提出了检索增强生成（RAG）这一解决方案，它能在推理过程中动态整合外部知识，从而提升事实准确性并减少幻觉。尽管RAG展现出了巨大潜力，但其实用性仍面临挑战，尤其是对输入查询质量的高度依赖性。本文深入研究了RAG流水线中不同组件对各种查询扰动的敏感性。我们的分析表明，即使是轻微的查询变化，也会导致常用检索器性能显著下降。我们不仅单独研究了每个模块的作用，还在端到端问答场景中考察了它们的综合影响，使用了涵盖通用领域和特定领域的丰富数据集。此外，我们还提出了一套系统化的评估框架，用于全面评估RAG流水线在查询级别的鲁棒性，并基于超过1092项实验的结果，为实践者提供了切实可行的建议。

> Large language models (LLMs) are very costly and inefficient to update with new information. To address this limitation, retrieval-augmented generation (RAG) has been proposed as a solution that dynamically incorporates external knowledge during inference, improving factual consistency and reducing hallucinations. Despite its promise, RAG systems face practical challenges-most notably, a strong dependence on the quality of the input query for accurate retrieval. In this paper, we investigate the sensitivity of different components in the RAG pipeline to various types of query perturbations. Our analysis reveals that the performance of commonly used retrievers can degrade significantly even under minor query variations. We study each module in isolation as well as their combined effect in an end-to-end question answering setting, using both general-domain and domain-specific datasets. Additionally, we propose an evaluation framework to systematically assess the query-level robustness of RAG pipelines and offer actionable recommendations for practitioners based on the results of more than 1092 experiments we performed.

[Arxiv](https://arxiv.org/abs/2507.06956)