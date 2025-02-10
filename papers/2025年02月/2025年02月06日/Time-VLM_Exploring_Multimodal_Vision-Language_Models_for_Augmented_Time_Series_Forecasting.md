# Time-VLM：探索多模态视觉-语言模型在增强时间序列预测中的应用

发布时间：2025年02月06日

`LLM应用` `时间序列预测` `多模态`

> Time-VLM: Exploring Multimodal Vision-Language Models for Augmented Time Series Forecasting

# 摘要

> 时间序列预测领域近期的研究探索了通过引入文本或视觉模态来提升模型精度的可能性。然而，文本虽然能够提供上下文理解，却往往缺乏精细的时间细节；视觉模态虽能捕捉复杂的时序模式，却缺乏语义背景，这限制了它们之间的互补潜力。针对这一问题，我们提出了Time-VLM，一个创新的多模态框架，它利用预训练的视觉-语言模型（VLMs）来连接时序、视觉和文本模态，从而提升预测效果。我们的框架包含三个关键组件：（1）检索增强学习器，通过与记忆库的交互提取增强的时间特征；（2）视觉增强学习器，将时间序列编码为信息丰富的图像；（3）文本增强学习器，生成具有上下文的文本描述。这些组件与冻结的预训练VLMs协同工作，生成多模态嵌入，然后与时间特征融合以进行最终预测。在多样化数据集上的广泛实验表明，Time-VLM在少样本和零样本场景下表现出色，从而为多模态时间序列预测开辟了新方向。

> Recent advancements in time series forecasting have explored augmenting models with text or vision modalities to improve accuracy. While text provides contextual understanding, it often lacks fine-grained temporal details. Conversely, vision captures intricate temporal patterns but lacks semantic context, limiting the complementary potential of these modalities. To address this, we propose Time-VLM, a novel multimodal framework that leverages pre-trained Vision-Language Models (VLMs) to bridge temporal, visual, and textual modalities for enhanced forecasting. Our framework comprises three key components: (1) a Retrieval-Augmented Learner, which extracts enriched temporal features through memory bank interactions; (2) a Vision-Augmented Learner, which encodes time series as informative images; and (3) a Text-Augmented Learner, which generates contextual textual descriptions. These components collaborate with frozen pre-trained VLMs to produce multimodal embeddings, which are then fused with temporal features for final prediction. Extensive experiments across diverse datasets demonstrate that Time-VLM achieves superior performance, particularly in few-shot and zero-shot scenarios, thereby establishing a new direction for multimodal time series forecasting.

[Arxiv](https://arxiv.org/abs/2502.04395)