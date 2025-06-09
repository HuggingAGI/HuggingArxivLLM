# Pts3D-LLM：探讨Token结构对大型语言模型3D场景理解的影响

发布时间：2025年06月05日

`LLM应用` `计算机视觉` `3D建模`

> Pts3D-LLM: Studying the Impact of Token Structure for 3D Scene Understanding With Large Language Models

# 摘要

> 为多模态大型语言模型（MLLMs）有效表示3D场景至关重要，但极具挑战性。现有方法通常仅依赖2D图像特征，并采用多种分词方法。本研究对3D分词结构进行了系统性研究，基于一致的模型主干和参数，全面对比了基于视频和基于点的表示方法。我们提出了一种新颖的方法，通过融合来自预训练的Sonata Point Transformer V3编码器的3D点云特征来丰富视觉分词。实验表明，加入显式的3D特征显著提升了性能。此外，我们发现，当点云被巧妙采样和排序时，基于点的结构可以与基于视频的结构相媲美。两种结构的最佳模型在多个3D理解基准上均达到了当前最优水平。我们强调对分词结构的分析是本研究的关键贡献，并透明地报告了多个种子平均后的结果，我们认为这对于推动该领域稳健发展至关重要。

> Effectively representing 3D scenes for Multimodal Large Language Models (MLLMs) is crucial yet challenging. Existing approaches commonly only rely on 2D image features and use varied tokenization approaches. This work presents a rigorous study of 3D token structures, systematically comparing video-based and point-based representations while maintaining consistent model backbones and parameters. We propose a novel approach that enriches visual tokens by incorporating 3D point cloud features from a Sonata pretrained Point Transformer V3 encoder. Our experiments demonstrate that merging explicit 3D features significantly boosts performance. Furthermore, we show that point-based token structures can rival video-based ones when the points are cleverly sampled and ordered. Our best models from both structures achieve state-of-the-art results on multiple 3D understanding benchmarks. We emphasize our analysis of token structures as a key contribution, alongside transparent reporting of results averaged over multiple seeds, a practice we believe is vital for robust progress in the field.

[Arxiv](https://arxiv.org/abs/2506.05689)