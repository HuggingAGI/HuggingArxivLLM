# SDR-GNN：用于会话情感识别中不完整多模态学习的频谱域重构图神经网络

发布时间：2024年11月29日

`其他` `情感识别` `多模态对话`

> SDR-GNN: Spectral Domain Reconstruction Graph Neural Network for Incomplete Multimodal Learning in Conversational Emotion Recognition

# 摘要

> 多模态对话中的情感识别（MERC）旨在借助文本、听觉和视觉模态特征来对话语情感予以分类。现有的多数 MERC 方法都假定每个话语具备完整模态，却忽视了现实场景中常见的模态不完整这一问题。近来，图神经网络（GNNs）在对话中的不完整多模态情感识别（IMERC）领域收获了显著成果。然而，传统的 GNNs 聚焦于节点间的二元关系，这限制了其捕捉更复杂、高阶信息的能力。此外，反复的消息传递可能致使过度平滑，降低了其保留关键高频细节的能力。为应对这些问题，我们提出了一种用于对话情感识别中不完整多模态学习的频谱域重建图神经网络（SDR-GNN）。SDR-GNN 基于说话者和上下文关系，通过滑动窗口构建话语语义交互图，以对情感依赖进行建模。为捕获高阶和高频信息，SDR-GNN 采用加权关系聚合，确保在话语间实现一致的语义特征提取。另外，它在频谱域开展多频聚合，通过提取高频和低频信息能够有效恢复不完整的模态。最后，运用多头注意力来融合和优化特征以进行情感识别。在各类现实世界数据集中开展的大量实验表明，我们的方法在不完整多模态学习方面成效显著，且优于当下最先进的方法。

> Multimodal Emotion Recognition in Conversations (MERC) aims to classify utterance emotions using textual, auditory, and visual modal features. Most existing MERC methods assume each utterance has complete modalities, overlooking the common issue of incomplete modalities in real-world scenarios. Recently, graph neural networks (GNNs) have achieved notable results in Incomplete Multimodal Emotion Recognition in Conversations (IMERC). However, traditional GNNs focus on binary relationships between nodes, limiting their ability to capture more complex, higher-order information. Moreover, repeated message passing can cause over-smoothing, reducing their capacity to preserve essential high-frequency details. To address these issues, we propose a Spectral Domain Reconstruction Graph Neural Network (SDR-GNN) for incomplete multimodal learning in conversational emotion recognition. SDR-GNN constructs an utterance semantic interaction graph using a sliding window based on both speaker and context relationships to model emotional dependencies. To capture higher-order and high-frequency information, SDR-GNN utilizes weighted relationship aggregation, ensuring consistent semantic feature extraction across utterances. Additionally, it performs multi-frequency aggregation in the spectral domain, enabling efficient recovery of incomplete modalities by extracting both high- and low-frequency information. Finally, multi-head attention is applied to fuse and optimize features for emotion recognition. Extensive experiments on various real-world datasets demonstrate that our approach is effective in incomplete multimodal learning and outperforms current state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2411.19822)