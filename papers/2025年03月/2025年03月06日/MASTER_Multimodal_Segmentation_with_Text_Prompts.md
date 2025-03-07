# MASTER：基于文本提示的多模态分割

发布时间：2025年03月06日

`LLM应用` `自动驾驶` `模型架构`

> MASTER: Multimodal Segmentation with Text Prompts

# 摘要

> RGB-热成像融合技术为复杂场景下的各种天气和光照条件提供了一种潜在的解决方案。然而，大量研究集中于设计复杂的模块来融合不同模态的数据。随着大型语言模型（LLMs）的广泛应用，可以从自然语言中更有效地提取有价值的信息。因此，我们旨在利用大型语言模型的优势，设计一种结构简单且高度适配的多模态融合模型架构。

我们提出了多模态分割与文本提示（MASTER）架构，该架构将大型语言模型整合到RGB-热成像多模态数据融合过程中，并允许复杂查询文本参与融合过程。我们的模型采用双路径结构从不同模态的图像中提取信息。此外，我们以大型语言模型作为多模态融合的核心模块，使模型能够从RGB图像、热图像和文本信息中生成可学习的代码本标记。通过轻量级图像解码器获得语义分割结果。

在各种自动驾驶场景的基准测试中，提出的MASTER表现优异，取得了令人鼓舞的结果。

> RGB-Thermal fusion is a potential solution for various weather and light conditions in challenging scenarios. However, plenty of studies focus on designing complex modules to fuse different modalities. With the widespread application of large language models (LLMs), valuable information can be more effectively extracted from natural language. Therefore, we aim to leverage the advantages of large language models to design a structurally simple and highly adaptable multimodal fusion model architecture. We proposed MultimodAl Segmentation with TExt PRompts (MASTER) architecture, which integrates LLM into the fusion of RGB-Thermal multimodal data and allows complex query text to participate in the fusion process. Our model utilizes a dual-path structure to extract information from different modalities of images. Additionally, we employ LLM as the core module for multimodal fusion, enabling the model to generate learnable codebook tokens from RGB, thermal images, and textual information. A lightweight image decoder is used to obtain semantic segmentation results. The proposed MASTER performs exceptionally well in benchmark tests across various automated driving scenarios, yielding promising results.

[Arxiv](https://arxiv.org/abs/2503.04199)