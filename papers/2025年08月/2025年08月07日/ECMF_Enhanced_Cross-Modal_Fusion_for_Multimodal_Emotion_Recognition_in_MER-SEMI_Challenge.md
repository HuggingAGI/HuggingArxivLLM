# ECMF：增强跨模态融合，MER-SEMI 挑战赛中的多模态情感识别解决方案。

发布时间：2025年08月07日

`LLM应用` `情绪识别` `多模态处理`

> ECMF: Enhanced Cross-Modal Fusion for Multimodal Emotion Recognition in MER-SEMI Challenge

# 摘要

> 情绪识别在提升人机交互方面至关重要。本研究通过提出一种新型多模态情绪识别框架，成功应对MER2025竞赛中的MER-SEMI挑战。为解决数据稀缺问题，我们利用大规模预训练模型从视觉、音频和文本中提取特征。针对视觉模态，我们设计了双分支视觉编码器，捕捉全局帧级特征和局部面部表征；针对文本模态，我们引入上下文增强方法，利用大型语言模型丰富文本情感线索。为有效融合多模态特征，我们提出包含自注意力机制和残差连接的融合策略。此外，我们通过多源标注策略优化训练集中的噪声标签。实验结果表明，我们的方法在MER2025-SEMI数据集上显著优于官方基线，加权F分数达到87.49%（基线为78.63%），充分验证了框架的有效性。

> Emotion recognition plays a vital role in enhancing human-computer interaction. In this study, we tackle the MER-SEMI challenge of the MER2025 competition by proposing a novel multimodal emotion recognition framework. To address the issue of data scarcity, we leverage large-scale pre-trained models to extract informative features from visual, audio, and textual modalities. Specifically, for the visual modality, we design a dual-branch visual encoder that captures both global frame-level features and localized facial representations. For the textual modality, we introduce a context-enriched method that employs large language models to enrich emotional cues within the input text. To effectively integrate these multimodal features, we propose a fusion strategy comprising two key components, i.e., self-attention mechanisms for dynamic modality weighting, and residual connections to preserve original representations. Beyond architectural design, we further refine noisy labels in the training set by a multi-source labeling strategy. Our approach achieves a substantial performance improvement over the official baseline on the MER2025-SEMI dataset, attaining a weighted F-score of 87.49% compared to 78.63%, thereby validating the effectiveness of the proposed framework.

[Arxiv](https://arxiv.org/abs/2508.05991)