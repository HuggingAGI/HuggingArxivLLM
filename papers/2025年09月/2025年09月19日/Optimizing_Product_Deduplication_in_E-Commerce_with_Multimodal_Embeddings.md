# 利用多模态嵌入优化电子商务产品去重

发布时间：2025年09月19日

`其他` `零售与电商`

> Optimizing Product Deduplication in E-Commerce with Multimodal Embeddings

# 摘要

> 在大型电商平台中，重复商品 listings 屡见不鲜，不仅造成消费者困惑、运营效率低下，还会削弱平台信任度并增加成本。传统关键词搜索方法依赖文本精确匹配，忽略了产品标题的语义相似性，因此难以准确识别重复商品。为此，我们研发了一套专为电商领域打造的可扩展多模态产品去重系统。该系统采用基于 BERT 架构的领域定制文本模型，搭配 MaskedAutoEncoders 进行图像表征；同时通过降维技术对两种架构进行优化，生成 128 维紧凑嵌入向量，确保信息损失最小化。此外，我们还构建了一种新型决策模型，能协同利用文本与图像向量特征。将这些特征提取机制与向量数据库 Milvus 整合后，系统可在超 2 亿件商品的海量目录中实现高效高精度的相似性搜索，且仅需 100GB 系统内存。实证结果显示，我们的匹配系统宏平均 F1 分数达 0.90，显著优于第三方解决方案的 0.83。研究表明，结合领域定制化适配与前沿机器学习技术，有望有效缓解大规模电商场景中的重复 listings 问题。

> In large scale e-commerce marketplaces, duplicate product listings frequently cause consumer confusion and operational inefficiencies, degrading trust on the platform and increasing costs. Traditional keyword-based search methodologies falter in accurately identifying duplicates due to their reliance on exact textual matches, neglecting semantic similarities inherent in product titles. To address these challenges, we introduce a scalable, multimodal product deduplication designed specifically for the e-commerce domain. Our approach employs a domain-specific text model grounded in BERT architecture in conjunction with MaskedAutoEncoders for image representations. Both of these architectures are augmented with dimensionality reduction techniques to produce compact 128-dimensional embeddings without significant information loss. Complementing this, we also developed a novel decider model that leverages both text and image vectors. By integrating these feature extraction mechanisms with Milvus, an optimized vector database, our system can facilitate efficient and high-precision similarity searches across extensive product catalogs exceeding 200 million items with just 100GB of system RAM consumption. Empirical evaluations demonstrate that our matching system achieves a macro-average F1 score of 0.90, outperforming third-party solutions which attain an F1 score of 0.83. Our findings show the potential of combining domain-specific adaptations with state-of-the-art machine learning techniques to mitigate duplicate listings in large-scale e-commerce environments.

[Arxiv](https://arxiv.org/abs/2509.15858)