# 基于 BERT 与 ResNet 的多模态情感分析

发布时间：2024年12月04日

`LLM应用` `情感分析` `社交媒体`

> Multimodal Sentiment Analysis Based on BERT and ResNet

# 摘要

> 随着互联网与社交媒体的迅猛发展，多模态数据（文本和图像）在情感分析任务中的重要性与日俱增。然而，现有的方法难以有效融合文本和图像特征，从而限制了分析的精准度。为解决此难题，提出了一个融合 BERT 与 ResNet 的多模态情感分析框架。BERT 在自然语言处理中展现出强大的文本表征能力，ResNet 在计算机视觉领域有着出色的图像特征提取表现。首先，运用 BERT 提取文本特征向量，利用 ResNet 提取图像特征表示。接着，探索了多种特征融合策略，最终选用基于注意力机制的融合模型，充分利用文本和图像间的互补信息。在公共数据集 MAVA-single 上的实验结果显示，与仅使用 BERT 或 ResNet 的单模态模型相比，所提出的多模态模型提升了准确率和 F1 分数，达到 74.5%的最优准确率。本研究不仅为多模态情感分析提供了新思路和新方法，还彰显了 BERT 和 ResNet 在跨领域融合中的应用潜力。未来，将探索更先进的特征融合技术和优化策略，进一步提升多模态情感分析的准确率和泛化能力。

> With the rapid development of the Internet and social media, multi-modal data (text and image) is increasingly important in sentiment analysis tasks. However, the existing methods are difficult to effectively fuse text and image features, which limits the accuracy of analysis. To solve this problem, a multimodal sentiment analysis framework combining BERT and ResNet was proposed. BERT has shown strong text representation ability in natural language processing, and ResNet has excellent image feature extraction performance in the field of computer vision. Firstly, BERT is used to extract the text feature vector, and ResNet is used to extract the image feature representation. Then, a variety of feature fusion strategies are explored, and finally the fusion model based on attention mechanism is selected to make full use of the complementary information between text and image. Experimental results on the public dataset MAVA-single show that compared with the single-modal models that only use BERT or ResNet, the proposed multi-modal model improves the accuracy and F1 score, reaching the best accuracy of 74.5%. This study not only provides new ideas and methods for multimodal sentiment analysis, but also demonstrates the application potential of BERT and ResNet in cross-domain fusion. In the future, more advanced feature fusion techniques and optimization strategies will be explored to further improve the accuracy and generalization ability of multimodal sentiment analysis.

[Arxiv](https://arxiv.org/abs/2412.03625)