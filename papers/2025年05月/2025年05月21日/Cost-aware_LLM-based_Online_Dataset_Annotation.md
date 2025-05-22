# 基于LLM的在线数据集标注：成本感知

发布时间：2025年05月21日

`LLM应用

摘要讨论了如何利用多个大型语言模型（LLMs）进行数据集标注，并提出了一种优化方法CaMVo，以提高效率和准确性。这属于LLM的应用层面，因此归类为LLM应用。` `机器学习` `数据科学`

> Cost-aware LLM-based Online Dataset Annotation

# 摘要

> 大型语言模型（LLMs）的最新进展使极小人工干预下的数据集自动标注成为现实。虽然跨多个LLM的多数投票通过缓解单个模型的偏见提升了标签可靠性，但其重复查询导致了高昂的计算成本。为此，我们提出了一种新颖的在线框架——基于成本感知的多数投票（CaMVo），用于高效且准确的LLM数据集标注。CaMVo通过上下文嵌入自适应选择LLM子集，无需预训练或真实标签即可平衡置信度和成本。借助基于LinUCB的选择机制和置信分数上的贝叶斯估计器，CaMVo为每个LLM估计标签准确性的下界，并通过加权多数投票聚合响应。在MMLU和IMDB电影评论数据集上的实证评估表明，CaMVo在显著降低标注成本的同时，达到了与完全多数投票相当甚至更优的准确性。这证明了CaMVo作为动态标注环境中经济高效注释的实用且稳健解决方案。

> Recent advances in large language models (LLMs) have enabled automated dataset labeling with minimal human supervision. While majority voting across multiple LLMs can improve label reliability by mitigating individual model biases, it incurs high computational costs due to repeated querying. In this work, we propose a novel online framework, Cost-aware Majority Voting (CaMVo), for efficient and accurate LLM-based dataset annotation. CaMVo adaptively selects a subset of LLMs for each data instance based on contextual embeddings, balancing confidence and cost without requiring pre-training or ground-truth labels. Leveraging a LinUCB-based selection mechanism and a Bayesian estimator over confidence scores, CaMVo estimates a lower bound on labeling accuracy for each LLM and aggregates responses through weighted majority voting. Our empirical evaluation on the MMLU and IMDB Movie Review datasets demonstrates that CaMVo achieves comparable or superior accuracy to full majority voting while significantly reducing labeling costs. This establishes CaMVo as a practical and robust solution for cost-efficient annotation in dynamic labeling environments.

[Arxiv](https://arxiv.org/abs/2505.15101)