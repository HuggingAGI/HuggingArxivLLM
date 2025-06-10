# 基于事件先验的视觉语言模型，助力高效视觉理解

发布时间：2025年06月09日

`LLM应用` `计算机视觉` `边缘计算`

> Event-Priori-Based Vision-Language Model for Efficient Visual Understanding

# 摘要

> 基于大型语言模型（LLM）的视觉语言模型（VLM）显著拓展了视觉理解能力的边界。然而，其对计算资源的高需求阻碍了在资源受限的边缘设备上的部署。低效的主要原因在于VLM需要处理密集且冗余的视觉信息。视觉输入中包含大量与文本语义无关的区域，导致相关计算在推理过程中难以发挥效用。

    本文提出了一种基于事件先验的视觉语言模型，命名为EP-VLM。其核心贡献在于引入了一种创新机制，通过利用基于动态事件视觉的运动先验来提升VLM的效率。受人类视觉认知启发，EP-VLM首先利用事件数据引导RGB视觉输入的基于补丁的稀疏化处理，逐步将VLM的计算集中在视觉输入的显著区域。随后，我们在VLM架构中构建了一种位置信息保留的视觉编码分词策略。该策略能够处理事件引导的无结构稀疏视觉输入，同时准确保留视觉输入中的位置理解。

    实验结果表明，与Qwen2-VL系列的基线模型相比，EP-VLM在保持几乎无损精度的同时实现了显著的效率提升。例如，在RealWorldQA数据集上，与原始Qwen2-VL-2B相比，EP-VLM实现了50%的FLOPs节省，同时保留了98%的原始精度。这项工作展示了基于事件视觉先验提升VLM推理效率的潜力，为开发更高效、可部署的VLM奠定了基础，从而推动了在边缘端实现可持续视觉理解的发展。
    

> Large Language Model (LLM)-based Vision-Language Models (VLMs) have substantially extended the boundaries of visual understanding capabilities. However, their high computational demands hinder deployment on resource-constrained edge devices. A key source of inefficiency stems from the VLM's need to process dense and redundant visual information. Visual inputs contain significant regions irrelevant to text semantics, rendering the associated computations ineffective for inference. This paper introduces a novel Event-Priori-Based Vision-Language Model, termed EP-VLM. Its core contribution is a novel mechanism leveraging motion priors derived from dynamic event vision to enhance VLM efficiency. Inspired by human visual cognition, EP-VLM first employs event data to guide the patch-wise sparsification of RGB visual inputs, progressively concentrating VLM computation on salient regions of the visual input. Subsequently, we construct a position-preserving tokenization strategy for the visual encoder within the VLM architecture. This strategy processes the event-guided, unstructured, sparse visual input while accurately preserving positional understanding within the visual input. Experimental results demonstrate that EP-VLM achieves significant efficiency improvements while maintaining nearly lossless accuracy compared to baseline models from the Qwen2-VL series. For instance, against the original Qwen2-VL-2B, EP-VLM achieves 50% FLOPs savings while retaining 98% of the original accuracy on the RealWorldQA dataset. This work demonstrates the potential of event-based vision priors for improving VLM inference efficiency, paving the way for creating more efficient and deployable VLMs for sustainable visual understanding at the edge.

[Arxiv](https://arxiv.org/abs/2506.07627)