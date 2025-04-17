# 超越词语：借助扩散机制提升无监督提示学习的辨别能力

发布时间：2025年04月16日

`其他` `计算机视觉` `视觉语言模型`

> Beyond Words: Augmenting Discriminative Richness via Diffusions in Unsupervised Prompt Learning

# 摘要

> 近年来，通过大量未标记数据对视觉语言模型（VLMs）进行微调引发了广泛关注。然而，高质量伪标签数据的缺乏仍是主要挑战。现有伪标签策略常因语义与视觉信息的不匹配而导致无监督提示学习（UPL）效果欠佳。本文提出了一种名为	extbf{A}ugmenting D	extbf{i}scriminative 	extbf{R}ichness via Diffusions（AiR）的简单而有效的方法，旨在通过学习更丰富、更全面的类别表示来提升分类能力。具体而言，我们的方法包含一个伪标签生成模块，利用高保真的合成样本创建辅助分类器，捕捉更丰富的视觉变化，从而连接文本-图像对分类到更鲁棒的图像-图像对分类。此外，我们还通过基于扩散模型的合成样本的多样性增强提示学习，为语义-视觉对齐提供更多有用信息。在包括RESISC45和Flowers102在内的五个公共基准数据集以及三种学习范式（UL、SSL和TRZSL）上的广泛实验表明，与现有无监督提示学习方法相比，AiR实现了显著且一致的性能提升。

> Fine-tuning vision-language models (VLMs) with large amounts of unlabeled data has recently garnered significant interest. However, a key challenge remains the lack of high-quality pseudo-labeled data. Current pseudo-labeling strategies often struggle with mismatches between semantic and visual information, leading to sub-optimal performance of unsupervised prompt learning (UPL) methods. In this paper, we introduce a simple yet effective approach called \textbf{A}ugmenting D\textbf{i}scriminative \textbf{R}ichness via Diffusions (AiR), toward learning a richer discriminating way to represent the class comprehensively and thus facilitate classification. Specifically, our approach includes a pseudo-label generation module that leverages high-fidelity synthetic samples to create an auxiliary classifier, which captures richer visual variation, bridging text-image-pair classification to a more robust image-image-pair classification. Additionally, we exploit the diversity of diffusion-based synthetic samples to enhance prompt learning, providing greater information for semantic-visual alignment. Extensive experiments on five public benchmarks, including RESISC45 and Flowers102, and across three learning paradigms-UL, SSL, and TRZSL-demonstrate that AiR achieves substantial and consistent performance improvements over state-of-the-art unsupervised prompt learning methods.

[Arxiv](https://arxiv.org/abs/2504.11930)