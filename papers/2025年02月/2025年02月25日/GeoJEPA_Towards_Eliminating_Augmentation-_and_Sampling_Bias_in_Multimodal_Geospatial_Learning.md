# GeoJEPA:致力于消除多模态地理空间学习中的数据增强与采样偏差

发布时间：2025年02月25日

`其他` `地理信息科学` `数据科学`

> GeoJEPA: Towards Eliminating Augmentation- and Sampling Bias in Multimodal Geospatial Learning

# 摘要

> 现有的地理空间区域和地图实体自监督表示学习方法高度依赖于预训练任务的设计，通常涉及基于空间邻近性的数据增强或正负样本对的启发式采样。这种依赖性不仅引入了偏差，还限制了表示的表达能力和泛化性。因此，学术界迫切需要探索建模地理空间数据的新方法。针对这些方法面临的三大挑战——多模态性、异质性和预训练任务选择，我们提出了 GeoJEPA，这是一个基于自监督联合嵌入预测架构的多功能多模态融合模型，专为地理空间数据设计。通过 GeoJEPA，我们旨在消除自监督地理空间表示学习中广泛存在的增强和采样偏差。该模型利用 OpenStreetMap 的属性、几何和航拍图像大数据集进行自监督预训练。实验结果展示了城市区域和地图实体的多模态语义表示，我们通过定量和定性评估验证了其有效性。这项研究揭示了 JEPA 在处理多模态数据方面的独特优势，为地理空间数据分析提供了新思路。

> Existing methods for self-supervised representation learning of geospatial regions and map entities rely extensively on the design of pretext tasks, often involving augmentations or heuristic sampling of positive and negative pairs based on spatial proximity. This reliance introduces biases and limits the representations' expressiveness and generalisability. Consequently, the literature has expressed a pressing need to explore different methods for modelling geospatial data. To address the key difficulties of such methods, namely multimodality, heterogeneity, and the choice of pretext tasks, we present GeoJEPA, a versatile multimodal fusion model for geospatial data built on the self-supervised Joint-Embedding Predictive Architecture. With GeoJEPA, we aim to eliminate the widely accepted augmentation- and sampling biases found in self-supervised geospatial representation learning. GeoJEPA uses self-supervised pretraining on a large dataset of OpenStreetMap attributes, geometries and aerial images. The results are multimodal semantic representations of urban regions and map entities that we evaluate both quantitatively and qualitatively. Through this work, we uncover several key insights into JEPA's ability to handle multimodal data.

[Arxiv](https://arxiv.org/abs/2503.05774)