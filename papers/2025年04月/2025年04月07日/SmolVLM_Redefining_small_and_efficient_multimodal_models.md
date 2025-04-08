# # SmolVLM：重新定义小型高效多模态模型

发布时间：2025年04月07日

`LLM应用` `移动设备` `视觉语言模型`

> SmolVLM: Redefining small and efficient multimodal models

# 摘要

> 大型视觉语言模型（VLMs）虽然性能出众，但对计算资源的需求极大，限制了其在移动和边缘设备上的应用。现有的小型VLM通常沿用大型模型的设计思路，如复杂的图像标记化方法，这导致GPU内存使用效率低下，难以满足设备端应用的实际需求。
    为此，我们推出了SmolVLM系列——专为资源高效推理打造的紧凑型多模态模型。通过系统性地探索优化的架构设计、标记化策略及数据整理方法，我们成功识别出关键设计要素，这些要素在保持极小内存占用的同时，显著提升了图像和视频任务的性能。
    其中，SmolVLM-256M在推理时仅需不到1GB的GPU内存，即便在开发时间晚于Idefics-80B模型18个月的情况下，性能仍超越了其300倍大的对手。而我们最大的模型，拥有22亿参数，与消耗两倍GPU内存的先进VLM比肩。值得一提的是，SmolVLM不仅擅长处理静态图像，更在视频理解领域表现出色。
    我们的成果表明，通过战略性架构优化、高效激进的标记化方法以及精心整理的训练数据，可以在显著减少资源消耗的同时大幅提升多模态性能，为实现更高效、更节能的实际部署铺平了道路。

> Large Vision-Language Models (VLMs) deliver exceptional performance but require significant computational resources, limiting their deployment on mobile and edge devices. Smaller VLMs typically mirror design choices of larger models, such as extensive image tokenization, leading to inefficient GPU memory usage and constrained practicality for on-device applications.
  We introduce SmolVLM, a series of compact multimodal models specifically engineered for resource-efficient inference. We systematically explore architectural configurations, tokenization strategies, and data curation optimized for low computational overhead. Through this, we identify key design choices that yield substantial performance gains on image and video tasks with minimal memory footprints.
  Our smallest model, SmolVLM-256M, uses less than 1GB GPU memory during inference and outperforms the 300-times larger Idefics-80B model, despite an 18-month development gap. Our largest model, at 2.2B parameters, rivals state-of-the-art VLMs consuming twice the GPU memory. SmolVLM models extend beyond static images, demonstrating robust video comprehension capabilities.
  Our results emphasize that strategic architectural optimizations, aggressive yet efficient tokenization, and carefully curated training data significantly enhance multimodal performance, facilitating practical, energy-efficient deployments at significantly smaller scales.

[Arxiv](https://arxiv.org/abs/2504.05299)