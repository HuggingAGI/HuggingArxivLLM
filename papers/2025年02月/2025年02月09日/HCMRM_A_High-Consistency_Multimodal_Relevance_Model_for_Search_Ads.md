# HCMRM：用于搜索广告的高一致性多模态相关性模型

发布时间：2025年02月09日

`LLM应用

理由：这篇论文探讨了如何利用视觉-语言预训练模型来优化搜索广告中的查询到视频的相关性匹配，从而提升广告系统的排序效果。虽然它涉及预训练模型的应用，但主要关注点在于模型在具体任务中的应用和优化，而不是模型本身的理论或机制。因此，将其分类为LLM应用是合适的。` `短视频`

> HCMRM: A High-Consistency Multimodal Relevance Model for Search Ads

# 摘要

> 搜索广告是商家在短视频平台触达目标用户的关键。短视频广告通过与用户搜索意图匹配的相关性匹配和竞价排序机制展示。本文专注于优化查询到视频的相关性匹配，以提升广告系统中排序的效果。近期视觉-语言预训练模型在多模态任务中表现突出，但它们对下游查询-视频相关性任务的贡献有限。这是因为视觉信号与文本的对齐方式，与查询、视觉信号和视频文本三元组的建模方式不同。此外，我们之前的相关性模型在排序能力方面存在局限性，这主要是由于二元交叉熵微调目标与排序目标之间的差异。为了解决这些问题，我们设计了一个高一致性多模态相关性模型（HCMRM）。它采用了一种简单而有效的方法，来增强预训练与相关性任务之间的一致性。具体来说，在预训练阶段，除了对齐视觉信号和视频文本外，还会从视频文本中提取一些关键词作为伪查询，以进行三元相关性建模。在微调阶段，我们引入了一种层次化Softmax损失函数，使模型在学习标签内部顺序的同时，最大化正负样本之间的差异。这促进了后续排序阶段的相关性和竞价融合排序。该方法已在快手搜索广告系统中部署超过一年，使得无关广告的比例降低了6.1%，广告收入增加了1.4%。

> Search advertising is essential for merchants to reach the target users on short video platforms. Short video ads aligned with user search intents are displayed through relevance matching and bid ranking mechanisms. This paper focuses on improving query-to-video relevance matching to enhance the effectiveness of ranking in ad systems. Recent vision-language pre-training models have demonstrated promise in various multimodal tasks. However, their contribution to downstream query-video relevance tasks is limited, as the alignment between the pair of visual signals and text differs from the modeling of the triplet of the query, visual signals, and video text. In addition, our previous relevance model provides limited ranking capabilities, largely due to the discrepancy between the binary cross-entropy fine-tuning objective and the ranking objective. To address these limitations, we design a high-consistency multimodal relevance model (HCMRM). It utilizes a simple yet effective method to enhance the consistency between pre-training and relevance tasks. Specifically, during the pre-training phase, along with aligning visual signals and video text, several keywords are extracted from the video text as pseudo-queries to perform the triplet relevance modeling. For the fine-tuning phase, we introduce a hierarchical softmax loss, which enables the model to learn the order within labels while maximizing the distinction between positive and negative samples. This promotes the fusion ranking of relevance and bidding in the subsequent ranking stage. The proposed method has been deployed in the Kuaishou search advertising system for over a year, contributing to a 6.1% reduction in the proportion of irrelevant ads and a 1.4% increase in ad revenue.

[Arxiv](https://arxiv.org/abs/2502.05822)