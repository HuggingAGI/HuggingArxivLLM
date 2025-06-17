# LTRR：为LLM训练排序检索器

发布时间：2025年06月16日

`RAG` `问答系统` `信息检索`

> LTRR: Learning To Rank Retrievers for LLMs

# 摘要

> 检索增强生成（RAG）系统通常依赖单一固定的检索器，尽管越来越多的证据表明，单一检索器无法在所有查询类型上都表现最优。本文中，我们探索了一种基于查询的路由方法，该方法根据查询动态选择一组检索器中的最优解，采用了无需训练的启发式策略和学习型路由模型。我们将路由问题建模为学习排序（LTR）问题，并提出了LTRR框架，该框架通过学习检索器的预期效用增益来对检索器进行排序，以提升下游LLM性能。我们在具有受控查询类型变化的合成问答数据上进行的实验表明，基于路由的RAG系统能够超越最佳单一检索器基线系统。使用答案正确性（AC）指标训练的模型以及采用配对学习方法（尤其是XGBoost）的模型表现提升尤为显著。我们还观察到对分布外查询的泛化能力提升。作为SIGIR 2025 LiveRAG挑战赛的一部分，我们提交的系统展示了该方法的实际可行性，在答案正确性和忠实度方面均取得了具有竞争力的表现。这些发现凸显了训练方法和指标选择在RAG系统查询路由中的重要性。

> Retrieval-Augmented Generation (RAG) systems typically rely on a single fixed retriever, despite growing evidence that no single retriever performs optimally across all query types. In this paper, we explore a query routing approach that dynamically selects from a pool of retrievers based on the query, using both train-free heuristics and learned routing models. We frame routing as a learning-to-rank (LTR) problem and introduce LTRR, a framework that learns to rank retrievers by their expected utility gain to downstream LLM performance. Our experiments, conducted on synthetic QA data with controlled query type variations, show that routing-based RAG systems can outperform the best single-retriever-based systems. Performance gains are especially pronounced in models trained with the Answer Correctness (AC) metric and with pairwise learning approaches, especially with XGBoost. We also observe improvements in generalization to out-of-distribution queries. As part of the SIGIR 2025 LiveRAG challenge, our submitted system demonstrated the practical viability of our approach, achieving competitive performance in both answer correctness and faithfulness. These findings highlight the importance of both training methodology and metric selection in query routing for RAG systems.

[Arxiv](https://arxiv.org/abs/2506.13743)