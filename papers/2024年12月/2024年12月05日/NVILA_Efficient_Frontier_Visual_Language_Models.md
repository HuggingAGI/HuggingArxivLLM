# NVILA：高效的前沿视觉语言模型

发布时间：2024年12月05日

`LLM应用` `计算机视觉` `人工智能`

> NVILA: Efficient Frontier Visual Language Models

# 摘要

> 摘要：近年来，视觉语言模型（VLMs）在准确性上取得了重大进展。然而，其效率却鲜少受到关注。本文引入了 NVILA，这是一系列旨在兼顾效率与准确性的开放视觉语言模型。以 VILA 为基础，我们先是提升了空间和时间分辨率，接着压缩了视觉标记，以此改进其模型架构。这种“先扩后压”的方式让 NVILA 能够高效处理高分辨率图像和长视频。我们还展开了系统的调研，以提升 NVILA 在整个生命周期（从训练、微调到部署）中的效率。NVILA 在众多图像和视频基准测试中的准确性与许多领先的开放及专有 VLMs 相当甚至更优。同时，它使训练成本降低 4.5 倍，微调内存使用减少 3.4 倍，预填充延迟降低 1.6 - 2.2 倍，解码延迟降低 1.2 - 2.8 倍。我们很快会公开我们的代码和模型，以利于重现。

> 
Abstract:Visual language models (VLMs) have made significant advances in accuracy in recent years. However, their efficiency has received much less attention. This paper introduces NVILA, a family of open VLMs designed to optimize both efficiency and accuracy. Building on top of VILA, we improve its model architecture by first scaling up the spatial and temporal resolutions, and then compressing visual tokens. This "scale-then-compress" approach enables NVILA to efficiently process high-resolution images and long videos. We also conduct a systematic investigation to enhance the efficiency of NVILA throughout its entire lifecycle, from training and fine-tuning to deployment. NVILA matches or surpasses the accuracy of many leading open and proprietary VLMs across a wide range of image and video benchmarks. At the same time, it reduces training costs by 4.5X, fine-tuning memory usage by 3.4X, pre-filling latency by 1.6-2.2X, and decoding latency by 1.2-2.8X. We will soon make our code and models available to facilitate reproducibility.
    

[Arxiv](https://arxiv.org/pdf/2412.04468)