# Walmart电商的语义广告检索：基于多领域知识逐步训练的语言模型

发布时间：2025年02月13日

`LLM应用` `电子商务` `机器学习`

> Semantic Ads Retrieval at Walmart eCommerce with Language Models Progressively Trained on Multiple Knowledge Domains

# 摘要

> 电子商务中的赞助搜索面临着独特且复杂的挑战，这些挑战源于搜索词与产品名称之间的语言结构不对称性、用户搜索意图的模糊性以及海量稀疏且不平衡的搜索数据。赞助搜索系统中，检索组件作为直接影响后续排序和竞价系统的初始步骤，扮演着关键角色。本文提出了一种针对Walmart.com广告检索系统的端到端优化方案。我们的方法包括：首先，利用BERT-like分类模型进行预训练，融入产品类别信息，以增强模型对Walmart产品语义的理解；其次，设计了一种用于嵌入结构的双塔式Siamese网络架构，以提升训练效率；最后，引入了Human-in-the-loop Progressive Fusion Training方法，确保模型具备强大的性能表现。实验结果显示，与基于DSSM的基线模型相比，该pipeline将搜索相关性指标提升了高达16%。此外，我们的大规模在线A/B测试表明，该方法在广告收入方面超越了现有生产模型。

> Sponsored search in e-commerce poses several unique and complex challenges. These challenges stem from factors such as the asymmetric language structure between search queries and product names, the inherent ambiguity in user search intent, and the vast volume of sparse and imbalanced search corpus data. The role of the retrieval component within a sponsored search system is pivotal, serving as the initial step that directly affects the subsequent ranking and bidding systems. In this paper, we present an end-to-end solution tailored to optimize the ads retrieval system on Walmart.com. Our approach is to pretrain the BERT-like classification model with product category information, enhancing the model's understanding of Walmart product semantics. Second, we design a two-tower Siamese Network structure for embedding structures to augment training efficiency. Third, we introduce a Human-in-the-loop Progressive Fusion Training method to ensure robust model performance. Our results demonstrate the effectiveness of this pipeline. It enhances the search relevance metric by up to 16% compared to a baseline DSSM-based model. Moreover, our large-scale online A/B testing demonstrates that our approach surpasses the ad revenue of the existing production model.

[Arxiv](https://arxiv.org/abs/2502.09089)