# “幽默、艺术，还是虚假信息？”：面向意图感知的合成图像检测多模态数据集

发布时间：2025年08月28日

`LLM应用` `媒体与娱乐`

> "Humor, Art, or Misinformation?": A Multimodal Dataset for Intent-Aware Synthetic Image Detection

# 摘要

> 多模态AI的最新进展推动了合成内容及上下文外内容检测技术的进步。然而，现有研究大多忽略了AI生成图像背后的真实意图。为此，我们构建了S-HArM——一个用于意图感知分类的多模态数据集，包含来自Twitter/X和Reddit的9,576个真实场景图像-文本对，并标注为幽默/讽刺、艺术或虚假信息。此外，我们还探索了三种提示策略（图像引导、描述引导和多模态引导），借助Stable Diffusion构建了大规模合成训练数据。我们开展了全面的对比实验，涵盖模态融合、对比学习、重建网络、注意力机制及大型视觉-语言模型。结果显示，在图像引导和多模态引导数据上训练出的模型对真实场景内容的泛化性能更优，其原因在于保留了视觉上下文。但整体性能仍有不足，这表明推断意图的复杂性，同时也说明需要专门的架构支持。

> Recent advances in multimodal AI have enabled progress in detecting synthetic and out-of-context content. However, existing efforts largely overlook the intent behind AI-generated images. To fill this gap, we introduce S-HArM, a multimodal dataset for intent-aware classification, comprising 9,576 "in the wild" image-text pairs from Twitter/X and Reddit, labeled as Humor/Satire, Art, or Misinformation. Additionally, we explore three prompting strategies (image-guided, description-guided, and multimodally-guided) to construct a large-scale synthetic training dataset with Stable Diffusion. We conduct an extensive comparative study including modality fusion, contrastive learning, reconstruction networks, attention mechanisms, and large vision-language models. Our results show that models trained on image- and multimodally-guided data generalize better to "in the wild" content, due to preserved visual context. However, overall performance remains limited, highlighting the complexity of inferring intent and the need for specialized architectures.

[Arxiv](https://arxiv.org/abs/2508.20670)