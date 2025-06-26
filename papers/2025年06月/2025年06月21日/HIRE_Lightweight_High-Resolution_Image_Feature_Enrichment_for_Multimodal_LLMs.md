# ## HIRE: 为多模态大型语言模型（LLMs）设计的轻量级高分辨率图像特征增强方法

发布时间：2025年06月21日

`LLM应用` `人工智能` `计算机视觉`

> HIRE: Lightweight High-Resolution Image Feature Enrichment for Multimodal LLMs

# 摘要

> 现代多模态大语言模型通过整合高分辨率图像特征，在细粒度视觉理解任务中表现优异，跨多个基准测试均达到高水平。然而，这些特征来自大型图像编码器（如ViT），多次调用导致计算成本激增。本研究首先提出特征上采样作为高分辨率特征生成的自然扩展。通过详尽的实验与消融分析，我们证实了浅层特征增强器在保持竞争力的同时，可将训练与推理时间及计算成本大幅缩减，FLOPs节省最高达1.5倍。

> The integration of high-resolution image features in modern multimodal large language models has demonstrated significant improvements in fine-grained visual understanding tasks, achieving high performance across multiple benchmarks. Since these features are obtained from large image encoders like ViT, they come with a significant increase in computational costs due to multiple calls to these encoders. In this work, we first develop an intuition for feature upsampling as a natural extension of high-resolution feature generation. Through extensive experiments and ablations, we demonstrate how a shallow feature enricher can achieve competitive results with tremendous reductions in training and inference time as well as computational cost, with upto 1.5x saving in FLOPs.

[Arxiv](https://arxiv.org/abs/2506.17608)