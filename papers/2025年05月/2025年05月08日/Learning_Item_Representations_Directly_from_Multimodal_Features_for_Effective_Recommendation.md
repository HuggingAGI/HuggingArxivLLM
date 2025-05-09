# 从多模态特征直接学习项目表示，实现高效推荐

发布时间：2025年05月08日

`LLM应用` `推荐系统`

> Learning Item Representations Directly from Multimodal Features for Effective Recommendation

# 摘要

> 传统多模态推荐系统主要依赖贝叶斯个性化排序（BPR）优化，通过融合物品ID嵌入与多模态特征学习物品表示。然而，我们的研究发现，现有方法在优化过程中存在显著的梯度偏差，更倾向于从多模态特征中获取表示，而非物品ID嵌入。这种偏差导致即使多模态特征参数已收敛，物品ID嵌入仍常表现不佳。为充分利用多模态特征中的丰富信息，本文提出了一种创新模型LIRDRec，直接从多模态特征中学习物品表示，以提升推荐效果。考虑到各模态特征可能捕获物品不同但相关的属性，我们设计了一种多模态转换机制，结合模态特定编码器，实现跨模态特征的有效融合。此外，为区分不同模态类型的影响，我们在LIRDRec中引入了渐进式权重复制融合模块，该模块可逐步学习各模态在合成最终用户或物品表示时的权重分配。最后，我们借助多模态大语言模型（MLLMs）强大的视觉理解能力，将物品图像转化为文本，并通过大语言模型（LLMs）从文本中提取语义嵌入。在五个真实数据集上的实证评估表明，我们的方法显著优于现有基线。值得注意的是，通过结合MLLMs和LLMs提取的嵌入，LIRDRec可将NDCG@20指标的推荐准确性平均提升4.21%相较于传统方法。


> Conventional multimodal recommender systems predominantly leverage Bayesian Personalized Ranking (BPR) optimization to learn item representations by amalgamating item identity (ID) embeddings with multimodal features. Nevertheless, our empirical and theoretical findings unequivocally demonstrate a pronounced optimization gradient bias in favor of acquiring representations from multimodal features over item ID embeddings. As a consequence, item ID embeddings frequently exhibit suboptimal characteristics despite the convergence of multimodal feature parameters. Given the rich informational content inherent in multimodal features, in this paper, we propose a novel model (i.e., LIRDRec) that learns item representations directly from these features to augment recommendation performance. Recognizing that features derived from each modality may capture disparate yet correlated aspects of items, we propose a multimodal transformation mechanism, integrated with modality-specific encoders, to effectively fuse features from all modalities. Moreover, to differentiate the influence of diverse modality types, we devise a progressive weight copying fusion module within LIRDRec. This module incrementally learns the weight assigned to each modality in synthesizing the final user or item representations. Finally, we utilize the powerful visual understanding of Multimodal Large Language Models (MLLMs) to convert the item images into texts and extract semantics embeddings upon the texts via LLMs. Empirical evaluations conducted on five real-world datasets validate the superiority of our approach relative to competing baselines. It is worth noting the proposed model, equipped with embeddings extracted from MLLMs and LLMs, can further improve the recommendation accuracy of NDCG@20 by an average of 4.21% compared to the original embeddings.

[Arxiv](https://arxiv.org/abs/2505.04960)