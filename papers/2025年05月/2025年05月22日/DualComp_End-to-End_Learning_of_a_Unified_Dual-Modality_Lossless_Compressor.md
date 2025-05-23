# # 摘要
DualComp：统一双模态无损压缩器的端到端学习

发布时间：2025年05月22日

`其他` `数据压缩` `图像处理`

> DualComp: End-to-End Learning of a Unified Dual-Modality Lossless Compressor

# 摘要

> 目前大多数基于学习的无损压缩器都针对单一模态设计，处理多模态数据时需要分别训练模型，缺乏灵活性。然而，不同模态在格式和统计特性上差异显著，导致缺乏模态特异性适配的压缩器效果不佳。尽管多模态大语言模型（MLLMs）为模态统一压缩提供了一种潜在解决方案，但其复杂性过高，限制了实际部署。为了解决这些问题，我们专注于最常见的两种模态——图像和文本，提出DualComp，首个统一且轻量化的学习型双模态无损压缩器。DualComp基于轻量化架构，通过三种关键结构增强来处理模态异质性：模态统一的分词机制、模态切换的上下文学习和模态路由的专家混合。此外，还采用重新参数化训练策略提升压缩性能。DualComp整合了模态专属和共享参数，实现高效参数利用，支持桌面CPU上的近实时推理（200KB/s）。尽管参数量远少于现有方法，DualComp在文本和图像数据集上的压缩性能仍与基于SOTA LLM的方法持平。其简化的单模态变体仅使用1.2%的模型规模，在Kodak数据集上将压缩性能提升了约9%，超越了此前的最佳图像压缩器。

> Most learning-based lossless compressors are designed for a single modality, requiring separate models for multi-modal data and lacking flexibility. However, different modalities vary significantly in format and statistical properties, making it ineffective to use compressors that lack modality-specific adaptations. While multi-modal large language models (MLLMs) offer a potential solution for modality-unified compression, their excessive complexity hinders practical deployment. To address these challenges, we focus on the two most common modalities, image and text, and propose DualComp, the first unified and lightweight learning-based dual-modality lossless compressor. Built on a lightweight backbone, DualComp incorporates three key structural enhancements to handle modality heterogeneity: modality-unified tokenization, modality-switching contextual learning, and modality-routing mixture-of-experts. A reparameterization training strategy is also used to boost compression performance. DualComp integrates both modality-specific and shared parameters for efficient parameter utilization, enabling near real-time inference (200KB/s) on desktop CPUs. With much fewer parameters, DualComp achieves compression performance on par with the SOTA LLM-based methods for both text and image datasets. Its simplified single-modality variant surpasses the previous best image compressor on the Kodak dataset by about 9% using just 1.2% of the model size.

[Arxiv](https://arxiv.org/abs/2505.16256)