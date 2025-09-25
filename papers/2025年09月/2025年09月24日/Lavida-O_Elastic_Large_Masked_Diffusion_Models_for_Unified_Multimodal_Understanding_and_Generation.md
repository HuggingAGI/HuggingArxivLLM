# Lavida-O：弹性大型掩码扩散模型——统一多模态理解与生成

发布时间：2025年09月24日

`其他` `媒体与娱乐`

> Lavida-O: Elastic Large Masked Diffusion Models for Unified Multimodal Understanding and Generation

# 摘要

> 我们提出Lavida-O——一个用于多模态理解与生成的统一掩码扩散模型（MDM）。不同于现有多模态MDM（如MMaDa和Muddit）仅能支持简单的图像级理解任务和低分辨率图像生成，Lavida-O打造了单一框架，可实现图像级理解、目标定位、图像编辑以及高分辨率（1024像素）文本到图像合成。Lavida-O创新性地集成了弹性混合Transformer（Elastic-MoT）架构，将轻量级生成分支与更大的理解分支耦合，借助令牌压缩、通用文本条件控制和分层采样支持，实现了高效且高质量的生成。Lavida-O进一步在图像生成和编辑任务中融入了规划与迭代自反思机制，凭借自身理解能力无缝提升生成质量。Lavida-O在各类基准测试中均达到了最先进水平，涵盖RefCOCO目标定位、GenEval文本到图像生成和ImgEdit图像编辑，性能超越现有自回归模型和连续扩散模型（如Qwen2.5-VL和FluxKontext-dev），且推理速度大幅提升。这些进展奠定了Lavida-O作为可扩展多模态推理与生成新范式的地位。

> We propose Lavida-O, a unified Masked Diffusion Model (MDM) for multimodal understanding and generation. Unlike existing multimodal MDMs such as MMaDa and Muddit which only support simple image-level understanding tasks and low-resolution image generation, Lavida-O presents a single framework that enables image-level understanding, object grounding, image editing, and high-resolution (1024px) text-to-image synthesis. Lavida-O incorporates a novel Elastic Mixture-of-Transformers (Elastic-MoT) architecture that couples a lightweight generation branch with a larger understanding branch, supported by token compression, universal text conditioning and stratified sampling for efficient and high-quality generation. Lavida-O further incorporates planning and iterative self-reflection in image generation and editing tasks, seamlessly boosting generation quality with its understanding capabilities. Lavida-O achieves state-of-the-art performance on a wide range of benchmarks including RefCOCO object grounding, GenEval text-to-image generation, and ImgEdit image editing, outperforming existing autoregressive models and continuous diffusion models such as Qwen2.5-VL and FluxKontext-dev, while offering considerable speedup at inference. These advances establish Lavida-O as a new paradigm for scalable multimodal reasoning and generation.

[Arxiv](https://arxiv.org/abs/2509.19244)