# C-TLSAN：内容增强型时间感知长短时注意力网络应用于个性化推荐

发布时间：2025年06月15日

`其他` `推荐系统` `电子商务`

> C-TLSAN: Content-Enhanced Time-Aware Long- and Short-Term Attention Network for Personalized Recommendation

# 摘要

> # 摘要
序列推荐系统通过捕捉用户历史行为模式，建模其动态变化的偏好。近年来，该领域借助深度神经网络和注意力机制，有效建模了用户的序列行为和时间敏感兴趣。

在本研究中，我们提出了C-TLSAN（内容增强的时间感知长短期注意力网络），这是TLSAN架构的扩展版本。C-TLSAN不仅同时建模用户长期和短期偏好，还结合了与项目相关的语义内容，例如产品描述。

C-TLSAN通过将与用户历史交互相关的文本内容直接嵌入到长期和短期注意力层中，丰富了推荐流程。这使得模型能够从行为模式和丰富的项目内容中学习，从而在时间维度上增强用户和项目表示。通过融合序列信号与文本语义，我们的方法提升了推荐系统的表达能力和个性化能力。

我们在大规模亚马逊数据集上进行了广泛实验，将C-TLSAN与最新的基线模型进行了对比，包括基于大型语言模型（LLMs）的近期序列推荐器。实验结果表明，C-TLSAN在下一个项目预测任务中始终优于强大的基线模型。与表现最佳的基线（TLSAN）相比，C-TLSAN在10个亚马逊产品类别中平均提高了AUC 1.66%，Recall@10 93.99%，以及Precision@10 94.80%。这些结果凸显了将内容感知增强集成到时序建模框架中对序列推荐的价值。

我们的代码可在https://github.com/booml247/cTLSAN获取。


> Sequential recommender systems aim to model users' evolving preferences by capturing patterns in their historical interactions. Recent advances in this area have leveraged deep neural networks and attention mechanisms to effectively represent sequential behaviors and time-sensitive interests. In this work, we propose C-TLSAN (Content-Enhanced Time-Aware Long- and Short-Term Attention Network), an extension of the TLSAN architecture that jointly models long- and short-term user preferences while incorporating semantic content associated with items, such as product descriptions.
  C-TLSAN enriches the recommendation pipeline by embedding textual content linked to users' historical interactions directly into both long-term and short-term attention layers. This allows the model to learn from both behavioral patterns and rich item content, enhancing user and item representations across temporal dimensions. By fusing sequential signals with textual semantics, our approach improves the expressiveness and personalization capacity of recommendation systems.
  We conduct extensive experiments on large-scale Amazon datasets, benchmarking C-TLSAN against state-of-the-art baselines, including recent sequential recommenders based on Large Language Models (LLMs), which represent interaction history and predictions in text form. Empirical results demonstrate that C-TLSAN consistently outperforms strong baselines in next-item prediction tasks. Notably, it improves AUC by 1.66%, Recall@10 by 93.99%, and Precision@10 by 94.80% on average over the best-performing baseline (TLSAN) across 10 Amazon product categories. These results highlight the value of integrating content-aware enhancements into temporal modeling frameworks for sequential recommendation. Our code is available at https://github.com/booml247/cTLSAN.

[Arxiv](https://arxiv.org/abs/2506.13021)