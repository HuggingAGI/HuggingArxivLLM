# QLIP：文本对齐视觉分词统一自回归多模态理解和生成

发布时间：2025年02月07日

`LLM应用` `计算机视觉` `生成式AI`

> QLIP: Text-Aligned Visual Tokenization Unifies Auto-Regressive Multimodal Understanding and Generation

# 摘要

> 我们提出了一种名为量化语言-图像预训练（QLIP）的视觉分词方法，将图像重建质量与零样本图像理解能力完美结合。QLIP采用基于二元球形量化的自编码器，同时优化图像重建目标和语言-图像对齐目标。我们首次证明了这两个目标并非非此即彼，而是在训练过程中可以动态平衡。通过两阶段训练管道，QLIP成功融合了图像-语言预训练的大批量需求与重建目标的内存限制。我们通过单一模型验证了QLIP在多模态理解和文本条件图像生成中的卓越性能。具体而言，QLIP可以无缝替代LLaVA的视觉编码器和LlamaGen的图像分词器，甚至在某些场景下表现更优。最终，我们证明QLIP能够支持一个统一的混合模态自回归模型，实现理解和生成任务的高效结合。

> We introduce Quantized Language-Image Pretraining (QLIP), a visual tokenization method that combines state-of-the-art reconstruction quality with state-of-the-art zero-shot image understanding. QLIP trains a binary-spherical-quantization-based autoencoder with reconstruction and language-image alignment objectives. We are the first to show that the two objectives do not need to be at odds. We balance the two loss terms dynamically during training and show that a two-stage training pipeline effectively mixes the large-batch requirements of image-language pre-training with the memory bottleneck imposed by the reconstruction objective. We validate the effectiveness of QLIP for multimodal understanding and text-conditioned image generation with a single model. Specifically, QLIP serves as a drop-in replacement for the visual encoder for LLaVA and the image tokenizer for LlamaGen with comparable or even better performance. Finally, we demonstrate that QLIP enables a unified mixed-modality auto-regressive model for understanding and generation.

[Arxiv](https://arxiv.org/abs/2502.05178)