# 基于交叉注意力的MRI与Jacobian图融合方法用于阿尔茨海默病诊断

发布时间：2025年03月01日

`其他` `医学影像分析`

> Cross-Attention Fusion of MRI and Jacobian Maps for Alzheimer's Disease Diagnosis

# 摘要

> 阿尔茨海默病 (AD) 的早期诊断对于在神经退化不可逆前进行干预至关重要。结构 MRI (sMRI) 被广泛用于 AD 诊断，但传统深度学习方法主要依赖基于强度的特征，需要大量数据来捕捉细微结构变化。Jacobian 行列式图 (JSM) 通过编码局部脑部变形提供了补充信息，但现有多种模式融合策略未能充分利用这些特征与 sMRI 的整合。我们提出了一种交叉注意力融合框架，用于建模 sMRI 强度与 JSM 衍生变形之间的内在关系，以进行 AD 分类。使用阿尔茨海默病神经成像计划 (ADNI) 数据集，我们比较了交叉注意力、成对自注意力和瓶颈注意力，分别与四个预训练的 3D 图像编码器进行对比。结果显示，交叉注意力融合实现了更优性能：AD 对比认知正常 (CN) 的平均 ROC-AUC 评分为 0.903 (+/-0.033)，轻度认知障碍 (MCI) 对比 CN 的评分为 0.692 (+/-0.061)。尽管表现强劲，我们的模型仅含 1.56 百万参数，远低于 ResNet-34 (63M) 和 Swin UNETR (61.98M)，前者为后者的 40 多倍。这些发现展示了交叉注意力融合在提升 AD 诊断准确性同时保持计算效率的潜力。

> Early diagnosis of Alzheimer's disease (AD) is critical for intervention before irreversible neurodegeneration occurs. Structural MRI (sMRI) is widely used for AD diagnosis, but conventional deep learning approaches primarily rely on intensity-based features, which require large datasets to capture subtle structural changes. Jacobian determinant maps (JSM) provide complementary information by encoding localized brain deformations, yet existing multimodal fusion strategies fail to fully integrate these features with sMRI. We propose a cross-attention fusion framework to model the intrinsic relationship between sMRI intensity and JSM-derived deformations for AD classification. Using the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset, we compare cross-attention, pairwise self-attention, and bottleneck attention with four pre-trained 3D image encoders. Cross-attention fusion achieves superior performance, with mean ROC-AUC scores of 0.903 (+/-0.033) for AD vs. cognitively normal (CN) and 0.692 (+/-0.061) for mild cognitive impairment (MCI) vs. CN. Despite its strong performance, our model remains highly efficient, with only 1.56 million parameters--over 40 times fewer than ResNet-34 (63M) and Swin UNETR (61.98M). These findings demonstrate the potential of cross-attention fusion for improving AD diagnosis while maintaining computational efficiency.

[Arxiv](https://arxiv.org/abs/2503.00586)