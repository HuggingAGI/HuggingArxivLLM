# 视觉语言模型：文本到3D生成的可微分语义与空间奖励

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> Vision-Language Models as Differentiable Semantic and Spatial Rewards for Text-to-3D Generation

# 摘要

> 分数蒸馏采样（SDS）借助预训练文本到图像扩散模型，通过多视角2D渲染图的去噪过程监督3D模型，使其与输入提示词精准对齐并保证3D一致性，从而实现高质量文本到3D生成。然而，现有SDS方法存在两大核心局限：（1）依赖CLIP风格文本编码器导致语义对齐粗糙，难以驾驭细粒度提示词；（2）2D扩散先验缺乏显式3D空间约束，致使多物体场景常出现几何错位与物体关系混乱。为此，我们提出全新文本到3D生成框架VLM3D，将大型视觉语言模型（VLMs）融入SDS流程，作为可微分的语义与空间先验。与传统文本到图像扩散先验不同，VLMs凭借丰富的语言锚定监督实现细粒度提示词对齐，更通过其固有的视觉语言建模能力构建强大空间理解力——这不仅大幅提升单物体生成的3D一致性，还优化了多物体场景的关系推理。我们基于开源Qwen2.5-VL模型构建VLM3D实例，并在GPTeval3D基准测试集验证：在多样物体与复杂场景中，VLM3D在语义保真度、几何连贯性和空间准确性上均显著超越现有SDS方法。

> Score Distillation Sampling (SDS) enables high-quality text-to-3D generation by supervising 3D models through the denoising of multi-view 2D renderings, using a pretrained text-to-image diffusion model to align with the input prompt and ensure 3D consistency. However, existing SDS-based methods face two fundamental limitations: (1) their reliance on CLIP-style text encoders leads to coarse semantic alignment and struggles with fine-grained prompts; and (2) 2D diffusion priors lack explicit 3D spatial constraints, resulting in geometric inconsistencies and inaccurate object relationships in multi-object scenes. To address these challenges, we propose VLM3D, a novel text-to-3D generation framework that integrates large vision-language models (VLMs) into the SDS pipeline as differentiable semantic and spatial priors. Unlike standard text-to-image diffusion priors, VLMs leverage rich language-grounded supervision that enables fine-grained prompt alignment. Moreover, their inherent vision language modeling provides strong spatial understanding, which significantly enhances 3D consistency for single-object generation and improves relational reasoning in multi-object scenes. We instantiate VLM3D based on the open-source Qwen2.5-VL model and evaluate it on the GPTeval3D benchmark. Experiments across diverse objects and complex scenes show that VLM3D significantly outperforms prior SDS-based methods in semantic fidelity, geometric coherence, and spatial correctness.

[Arxiv](https://arxiv.org/abs/2509.15772)