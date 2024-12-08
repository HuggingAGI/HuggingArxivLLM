# JetFormer：一种针对原始图像和文本的自回归生成模型

发布时间：2024年11月29日

`LLM应用` `图像生成` `多模态模型`

> JetFormer: An Autoregressive Generative Model of Raw Images and Text

# 摘要

> 消除建模限制、统一跨领域架构，一直是训练大型多模态模型近期取得进展的关键因素。然而，多数此类模型仍依赖众多单独训练的组件，如特定模态的编码器与解码器。在本研究中，我们进一步优化了图像与文本的联合生成建模。我们提出了一种仅自回归解码器的转换器——JetFormer，其训练旨在直接最大化原始数据的可能性，不依赖任何单独预训练的组件，且能理解和生成文本与图像。具体而言，我们借助归一化流模型获取与自回归多模态转换器联合训练的软标记图像表示。在推理时，归一化流模型既是感知任务的图像编码器，也是图像生成任务的图像解码器。JetFormer 实现的文本到图像生成质量可与近期基于 VQ-VAE 和 VAE 的基线相媲美。这些基线依赖于预训练的图像自动编码器，其训练采用了包括感知损失在内的复杂混合损失。同时，JetFormer 展现出强大的图像理解能力。据我们所知，JetFormer 是首个能够生成高保真图像并产生强大对数似然边界的模型。

> Removing modeling constraints and unifying architectures across domains has been a key driver of the recent progress in training large multimodal models. However, most of these models still rely on many separately trained components such as modality-specific encoders and decoders. In this work, we further streamline joint generative modeling of images and text. We propose an autoregressive decoder-only transformer - JetFormer - which is trained to directly maximize the likelihood of raw data, without relying on any separately pretrained components, and can understand and generate both text and images. Specifically, we leverage a normalizing flow model to obtain a soft-token image representation that is jointly trained with an autoregressive multimodal transformer. The normalizing flow model serves as both an image encoder for perception tasks and an image decoder for image generation tasks during inference. JetFormer achieves text-to-image generation quality competitive with recent VQ-VAE- and VAE-based baselines. These baselines rely on pretrained image autoencoders, which are trained with a complex mixture of losses, including perceptual ones. At the same time, JetFormer demonstrates robust image understanding capabilities. To the best of our knowledge, JetFormer is the first model that is capable of generating high-fidelity images and producing strong log-likelihood bounds.

[Arxiv](https://arxiv.org/abs/2411.19722)