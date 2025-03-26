# 基于 OpenFlamingo 的 C2C 汽车零部件数据多模态嵌入分析

发布时间：2025年03月20日

`LLM应用` `数据挖掘`

> Leveraging OpenFlamingo for Multimodal Embedding Analysis of C2C Car Parts Data

# 摘要

> 本文致力于探索多模态机器学习模型，尤其是OpenFlamingo模型，在处理大规模C2C在线汽车部件相关帖子数据集中的应用潜力。我们从OfferUp和Craigslist平台获取数据，构建了包含超过120万条帖子及其对应图片的丰富数据集。通过OpenFlamingo模型，我们提取了每条帖子的文本和图片嵌入表示。在联合嵌入空间中，我们运用k-means聚类分析方法，揭示了帖子之间的潜在模式和共性。研究发现，多数聚类具有清晰的特征模式，但也有部分聚类内部缺乏显著规律。这表明，OpenFlamingo模型在挖掘大规模数据集模式方面展现出潜力，但其模型架构仍需根据具体数据集进行优化调整，以提升效果。

> In this paper, we aim to investigate the capabilities of multimodal machine learning models, particularly the OpenFlamingo model, in processing a large-scale dataset of consumer-to-consumer (C2C) online posts related to car parts. We have collected data from two platforms, OfferUp and Craigslist, resulting in a dataset of over 1.2 million posts with their corresponding images. The OpenFlamingo model was used to extract embeddings for the text and image of each post. We used $k$-means clustering on the joint embeddings to identify underlying patterns and commonalities among the posts. We have found that most clusters contain a pattern, but some clusters showed no internal patterns. The results provide insight into the fact that OpenFlamingo can be used for finding patterns in large datasets but needs some modification in the architecture according to the dataset.

[Arxiv](https://arxiv.org/abs/2503.17408)