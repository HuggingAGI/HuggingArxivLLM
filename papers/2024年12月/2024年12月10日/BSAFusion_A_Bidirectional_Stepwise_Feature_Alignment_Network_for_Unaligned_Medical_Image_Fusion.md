# BSAFusion：一种用于未对齐医学图像融合的双向逐步特征对齐网络

发布时间：2024年12月10日

`其他` `医学图像`

> BSAFusion: A Bidirectional Stepwise Feature Alignment Network for Unaligned Medical Image Fusion

# 摘要

> 倘若未对齐的多模态医学图像能在统一的处理框架内通过单阶段方式同时实现对齐与融合，这不但能达成双重任务的相互促进，还能助力降低模型的复杂度。然而，此类模型的设计面临着特征融合与对齐要求不兼容的难题；确切而言，特征对齐需要对应特征保持一致，而特征融合则要求特征相互补充。为应对这一挑战，本文提出了一种未对齐医学图像融合方法，即双向逐步特征对齐与融合（BSFA-F）策略。为降低模态差异对跨模态特征匹配的不良影响，我们将模态无差异特征表示（MDF-FR）方法融入 BSFA-F 中。MDF-FR 借助模态特征表示头（MFRH）整合输入图像的全局信息。通过将当前图像的 MFRH 所包含的信息注入其他模态图像，有效减少了模态差异对特征对齐的影响，同时保留了不同图像携带的互补信息。在特征对齐方面，BSFA-F 基于两点间向量位移的路径独立性，采用双向逐步对齐变形场预测策略。该策略解决了单步对齐中跨度大且变形场预测不准确的问题。最终，多模态特征融合模块完成了对齐特征的融合。多个数据集的实验结果表明了我们方法的有效性。源代码可在 https://github.com/slrl123/BSAFusion 获取。

> If unaligned multimodal medical images can be simultaneously aligned and fused using a single-stage approach within a unified processing framework, it will not only achieve mutual promotion of dual tasks but also help reduce the complexity of the model. However, the design of this model faces the challenge of incompatible requirements for feature fusion and alignment; specifically, feature alignment requires consistency among corresponding features, whereas feature fusion requires the features to be complementary to each other. To address this challenge, this paper proposes an unaligned medical image fusion method called Bidirectional Stepwise Feature Alignment and Fusion (BSFA-F) strategy. To reduce the negative impact of modality differences on cross-modal feature matching, we incorporate the Modal Discrepancy-Free Feature Representation (MDF-FR) method into BSFA-F. MDF-FR utilizes a Modality Feature Representation Head (MFRH) to integrate the global information of the input image. By injecting the information contained in MFRH of the current image into other modality images, it effectively reduces the impact of modality differences on feature alignment while preserving the complementary information carried by different images. In terms of feature alignment, BSFA-F employs a bidirectional stepwise alignment deformation field prediction strategy based on the path independence of vector displacement between two points. This strategy solves the problem of large spans and inaccurate deformation field prediction in single-step alignment. Finally, Multi-Modal Feature Fusion block achieves the fusion of aligned features. The experimental results across multiple datasets demonstrate the effectiveness of our method. The source code is available at https://github.com/slrl123/BSAFusion.

[Arxiv](https://arxiv.org/abs/2412.08050)