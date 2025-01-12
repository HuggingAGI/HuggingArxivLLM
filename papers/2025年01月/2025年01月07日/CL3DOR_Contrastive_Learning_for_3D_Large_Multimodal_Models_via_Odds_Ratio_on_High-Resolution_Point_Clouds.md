# CL3DOR：基于高分辨率点云比值比的3D多模态大模型对比学习

发布时间：2025年01月07日

`LLM应用

**理由**：这篇论文主要讨论了如何通过改进3D多模态模型的训练方法来提升跨模态理解的精确性，特别是通过对比学习方法（CL3DOR）来增强3D场景理解和推理任务的表现。虽然涉及多模态任务，但其核心仍然是基于大型语言模型（LLMs）的应用，特别是在3D场景理解和推理任务中的应用。因此，将其归类为LLM应用是合适的。` `计算机视觉` `3D建模`

> CL3DOR: Contrastive Learning for 3D Large Multimodal Models via Odds Ratio on High-Resolution Point Clouds

# 摘要

> # 摘要
最新研究表明，大型语言模型（LLMs）不仅能处理文本任务，还能胜任音频、图像和视频等多模态任务。尤其是3D大型多模态模型（3D LMMs）的研究，凭借处理点云等高维数据的潜力，取得了显著进展。然而，现有训练数据集中每个样本的视觉和文本内容在信息粒度和清晰度上存在不足，这限制了跨模态理解的精确性。为此，我们提出了CL3DOR——一种基于高分辨率点云比值比的3D多模态模型对比学习方法，旨在提升视觉和文本内容的特异性和清晰度。具体而言，我们增加了每个对象的点云密度，并在训练数据集中构建了信息丰富的硬负响应，以抑制不相关的输出。通过将比值比作为对比学习的辅助项融入传统语言建模损失，CL3DOR在3D场景理解和推理任务中表现卓越。此外，大量实验验证了CL3DOR关键组件的有效性。

> Recent research has demonstrated that Large Language Models (LLMs) are not limited to text-only tasks but can also function as multimodal models across various modalities, including audio, images, and videos. In particular, research on 3D Large Multimodal Models (3D LMMs) is making notable strides, driven by the potential of processing higher-dimensional data like point clouds. However, upon closer examination, we find that the visual and textual content within each sample of existing training datasets lacks both high informational granularity and clarity, which serve as a bottleneck for precise cross-modal understanding. To address these issues, we propose CL3DOR, Contrastive Learning for 3D large multimodal models via Odds ratio on high-Resolution point clouds, designed to ensure greater specificity and clarity in both visual and textual content. Specifically, we increase the density of point clouds per object and construct informative hard negative responses in the training dataset to penalize unwanted responses. To leverage hard negative responses, we incorporate the odds ratio as an auxiliary term for contrastive learning into the conventional language modeling loss. CL3DOR achieves state-of-the-art performance in 3D scene understanding and reasoning benchmarks. Additionally, we demonstrate the effectiveness of CL3DOR's key components through extensive experiments.

[Arxiv](https://arxiv.org/abs/2501.03879)