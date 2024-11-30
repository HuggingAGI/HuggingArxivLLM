# 本研究旨在深入探讨和评估神经网络排序模型的可解释性，以揭示其内部决策机制及优化依据。

发布时间：2024年03月04日

`LLM理论`

> Evaluating the Explainability of Neural Rankers

# 摘要

> 随着信息检索模型从无监督统计向基于特征的监督学习乃至充分利用大型语言模型预训练的数据驱动模式演变，其有效性不断提升，表现为检索结果顶部的相关性增强。然而，“这些模型有多高的可解释性？”这一问题亟待深入探讨，本文正以此为目标进行评估。我们特别提出一个通用评估平台，对任意排序模型的可解释性进行系统化评估，所有待评估模型共享同一套解释算法。在该框架下，各模型不仅需输出文档的排序列表，还需为每篇文档提供一系列解释单元或理由，并利用这些内含的元信息衡量各个理由作为内在解释力指标的局部一致性，这个过程无需人工判定相关性。同时，作为外在评价方式，我们通过子文档级别相关性评估计算这些理由的实际相关性。研究结果显示了多个引人注目的现象，如句子级别的理由更稳定、模型复杂度上升通常导致解释一致性下降，以及可解释性指标作为补充评估维度对于IR系统的重要性，因为一致性与顶级排名的nDCG关联度并不高。

> Information retrieval models have witnessed a paradigm shift from unsupervised statistical approaches to feature-based supervised approaches to completely data-driven ones that make use of the pre-training of large language models. While the increasing complexity of the search models have been able to demonstrate improvements in effectiveness (measured in terms of relevance of top-retrieved results), a question worthy of a thorough inspection is - "how explainable are these models?", which is what this paper aims to evaluate. In particular, we propose a common evaluation platform to systematically evaluate the explainability of any ranking model (the explanation algorithm being identical for all the models that are to be evaluated). In our proposed framework, each model, in addition to returning a ranked list of documents, also requires to return a list of explanation units or rationales for each document. This meta-information from each document is then used to measure how locally consistent these rationales are as an intrinsic measure of interpretability - one that does not require manual relevance assessments. Additionally, as an extrinsic measure, we compute how relevant these rationales are by leveraging sub-document level relevance assessments. Our findings show a number of interesting observations, such as sentence-level rationales are more consistent, an increase in complexity mostly leads to less consistent explanations, and that interpretability measures offer a complementary dimension of evaluation of IR systems because consistency is not well-correlated with nDCG at top ranks.

[Arxiv](https://arxiv.org/abs/2403.01981)