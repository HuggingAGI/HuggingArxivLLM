# Vitron: 一个集理解、生成、分割与编辑于一体的像素级视觉LLM

发布时间：2024年10月08日

`LLM应用

理由：这篇论文主要讨论的是视觉大型语言模型（LLMs）在多模态任务中的应用，特别是如何通过VITRON模型来实现对静态图像和动态视频的全面理解、生成、分割和编辑。论文的重点在于如何利用LLM技术来解决具体的视觉任务，并展示了其在多个数据集和任务上的表现。因此，这篇论文属于LLM应用类别。` `计算机视觉` `多模态学习`

> Vitron: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing

# 摘要

> # 摘要
近期视觉大型语言模型（LLMs）的发展取得了显著进展，但在多模态通用性方面仍面临挑战，如实例级理解的粗粒度、图像与视频支持的不足，以及视觉任务覆盖的局限。本文提出VITRON，一个通用的像素级视觉LLM，旨在全面理解、生成、分割和编辑静态图像与动态视频。VITRON基于LLM骨干，前端模块集成了图像、视频和像素级区域视觉的编码器，后端则采用最先进的视觉专家，支持从视觉理解到生成、从低级到高级的一系列视觉任务。为确保LLM与后端模块间的高效精准消息传递，我们提出了一种混合方法，结合离散文本指令与连续信号嵌入。此外，我们设计了多种像素级时空视觉-语言对齐学习，以提升VITRON的细粒度视觉能力。最后，通过跨任务协同模块，我们最大化任务不变的细粒度视觉特征，增强不同视觉任务间的协同效应。VITRON在12个视觉任务和22个数据集上的表现，展示了其在四大视觉任务集群中的广泛能力。总体而言，这项工作揭示了开发更统一的多模态通用模型的巨大潜力。项目主页：https://vitron-llm.github.io/

> Recent developments of vision large language models (LLMs) have seen remarkable progress, yet still encounter challenges towards multimodal generalists, such as coarse-grained instance-level understanding, lack of unified support for both images and videos, and insufficient coverage across various vision tasks. In this paper, we present VITRON, a universal pixel-level vision LLM designed for comprehensive understanding, generating, segmenting, and editing of both static images and dynamic videos. Building on top of an LLM backbone, VITRON incorporates encoders for images, videos, and pixel-level regional visuals within its frontend modules, while employing state-of-the-art visual specialists as its backend, via which VITRON supports a spectrum of vision end tasks, spanning visual comprehension to visual generation, from low level to high level. To ensure an effective and precise message passing from LLM to backend modules for function invocation, we propose a novel hybrid method by simultaneously integrating discrete textual instructions and continuous signal embeddings. Further, we design various pixel-level spatiotemporal vision-language alignment learning for VITRON to reach the best fine-grained visual capability. Finally, a cross-task synergy module is advised to learn to maximize the task-invariant fine-grained visual features, enhancing the synergy between different visual tasks. Demonstrated over 12 visual tasks and evaluated across 22 datasets, VITRON showcases its extensive capabilities in the four main vision task clusters. Overall, this work illuminates the great potential of developing a more unified multimodal generalist. Project homepage: https://vitron-llm.github.io/

[Arxiv](https://arxiv.org/abs/2412.19806)