# InstructSeg：实现有指导的视觉分割与多模态大型语言模型的统一

发布时间：2024年12月18日

`LLM应用`

> InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models

# 摘要

> 在多模态大型语言模型（MLLMs）的助力下，图像和视频领域的文本引导通用分割模型近来进展迅猛。然而，这些方法往往是针对特定领域分别开发的，忽略了这两个领域在任务设置和解决方案上的共性。在本文中，我们将图像和视频层面的引用分割与推理分割相结合，定义为指令视觉分割（IVS）。相应地，我们提出了 InstructSeg，这是一个为 IVS 配备 MLLMs 的端到端分割管线。具体而言，我们运用对象感知视频感知器从参考帧中提取时间和对象信息，助力全面的视频理解。另外，我们引入视觉引导的多粒度文本融合，以更好地将全局和详细的文本信息与细粒度视觉引导相融合。借助多任务和端到端训练，InstructSeg 在各类图像和视频分割任务中表现出色，仅用一个模型就超越了分割专家和基于 MLLM 的方法。我们的代码可在 https://github.com/congvvc/InstructSeg 获取。

> Boosted by Multi-modal Large Language Models (MLLMs), text-guided universal segmentation models for the image and video domains have made rapid progress recently. However, these methods are often developed separately for specific domains, overlooking the similarities in task settings and solutions across these two areas. In this paper, we define the union of referring segmentation and reasoning segmentation at both the image and video levels as Instructed Visual Segmentation (IVS). Correspondingly, we propose InstructSeg, an end-to-end segmentation pipeline equipped with MLLMs for IVS. Specifically, we employ an object-aware video perceiver to extract temporal and object information from reference frames, facilitating comprehensive video understanding. Additionally, we introduce vision-guided multi-granularity text fusion to better integrate global and detailed text information with fine-grained visual guidance. By leveraging multi-task and end-to-end training, InstructSeg demonstrates superior performance across diverse image and video segmentation tasks, surpassing both segmentation specialists and MLLM-based methods with a single model. Our code is available at https://github.com/congvvc/InstructSeg.

[Arxiv](https://arxiv.org/abs/2412.14006)