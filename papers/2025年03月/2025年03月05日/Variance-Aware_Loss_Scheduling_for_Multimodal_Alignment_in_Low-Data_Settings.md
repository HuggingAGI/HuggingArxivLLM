# Variance-Aware Loss Scheduling for Multimodal Alignment in Low-Data Settings
低数据场景下基于方差感知的多模态对齐损失调度方法研究

发布时间：2025年03月05日

`LLM理论` `计算机视觉`

> Variance-Aware Loss Scheduling for Multimodal Alignment in Low-Data Settings

# 摘要

> 训练视觉-语言模型以实现图像-文本对齐通常需要大规模数据集才能达到稳健的性能。然而，在数据量有限的情况下，标准的对比学习可能难以有效对齐不同模态，主要由于过拟合和训练过程的不稳定性。本文中，我们提出了一种方差感知的损失调度方法，该方法根据模型对齐预测中的统计变异性（不确定性）动态调整对比损失的权重。通过使用Flickr8k图像-文字描述数据集的一个子集来模拟数据有限的条件，我们证明了与固定权重基线相比，我们的方法提高了图像-文本检索的准确性。我们还与其他自适应加权策略（利用输出熵和余弦相似度分布）进行了比较，发现方差感知调度提供了最佳的整体权衡。从t-SNE可视化结果来看，我们的方法在定性上生成了更具区分度的多模态嵌入。此外，在注入噪声的图像和文字描述的压力测试中，方差引导的损失证明了更强的鲁棒性，在引入随机扰动时保持了更高的召回率。这些结果突显了自适应损失加权在数据量有限的情况下对多模态对齐的益处。

> Training vision-language models for image-text alignment typically requires large datasets to achieve robust performance. In low-data scenarios, standard contrastive learning can struggle to align modalities effectively due to overfitting and unstable training dynamics. In this paper, we propose a variance-aware loss scheduling approach that dynamically adjusts the weighting of the contrastive loss based on the statistical variability (uncertainty) in the model's alignment predictions. Using a subset of the Flickr8k image-caption dataset to simulate limited data conditions, we demonstrate that our approach improves image-text retrieval accuracy compared to a fixed-weight baseline. We also compare against other adaptive weighting strategies (using output entropy and cosine similarity spread) and find that variance-aware scheduling provides the best overall trade-off. Qualitatively, our method yields more distinct multimodal embeddings as shown by t-SNE visualizations. Moreover, in a stress test with noise-injected captions and images, the variance-guided loss proves more robust, maintaining higher recall when random perturbations are introduced. These results highlight the benefit of adaptive loss weighting for multimodal alignment in low-data regimes.

[Arxiv](https://arxiv.org/abs/2503.03202)