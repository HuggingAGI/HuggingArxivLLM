# VideoLLaMA 3: 图像与视频理解的前沿多模态基础模型

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文介绍了VideoLLaMA3，一个多模态基础模型，专注于图像和视频理解。它涉及了视觉编码器、投影器和LLM的联合训练和微调，属于LLM在多模态任务中的应用。因此，分类为LLM应用是合适的。` `计算机视觉` `多媒体`

> VideoLLaMA 3: Frontier Multimodal Foundation Models for Image and Video Understanding

# 摘要

> 本文提出了VideoLLaMA3，一个更先进的多模态基础模型，专为图像和视频理解设计。其核心设计理念是以视觉为中心，体现在训练范式和框架设计两方面。我们强调高质量的图像-文本数据对图像和视频理解的重要性，因此专注于构建大规模、高质量的图像-文本数据集，而非大量视频-文本数据。VideoLLaMA3的训练分为四个阶段：1）视觉对齐阶段，预热视觉编码器和投影器；2）视觉-语言预训练阶段，使用多种类型的图像-文本数据（如场景图像、文档、图表）和纯文本数据联合调整视觉编码器、投影器和LLM；3）多任务微调阶段，结合图像-文本SFT数据和视频-文本数据，为视频理解奠定基础；4）视频微调阶段，进一步提升模型的视频理解能力。在框架设计上，我们调整了视觉编码器，使其能根据图像大小生成相应数量的视觉标记，而非固定数量。对于视频输入，我们通过减少相似视觉标记的数量，使视频表示更加精确和紧凑。得益于这些以视觉为中心的设计，VideoLLaMA3在图像和视频理解基准测试中表现出色。

> In this paper, we propose VideoLLaMA3, a more advanced multimodal foundation model for image and video understanding. The core design philosophy of VideoLLaMA3 is vision-centric. The meaning of "vision-centric" is two-fold: the vision-centric training paradigm and vision-centric framework design. The key insight of our vision-centric training paradigm is that high-quality image-text data is crucial for both image and video understanding. Instead of preparing massive video-text datasets, we focus on constructing large-scale and high-quality image-text datasets. VideoLLaMA3 has four training stages: 1) vision-centric alignment stage, which warms up the vision encoder and projector; 2) vision-language pretraining stage, which jointly tunes the vision encoder, projector, and LLM with large-scale image-text data covering multiple types (including scene images, documents, charts) as well as text-only data. 3) multi-task fine-tuning stage, which incorporates image-text SFT data for downstream tasks and video-text data to establish a foundation for video understanding. 4) video-centric fine-tuning, which further improves the model's capability in video understanding. As for the framework design, to better capture fine-grained details in images, the pretrained vision encoder is adapted to encode images of varying sizes into vision tokens with corresponding numbers, rather than a fixed number of tokens. For video inputs, we reduce the number of vision tokens according to their similarity so that the representation of videos will be more precise and compact. Benefit from vision-centric designs, VideoLLaMA3 achieves compelling performances in both image and video understanding benchmarks.

[Arxiv](https://arxiv.org/abs/2501.13106)