# CameraBench：借助摄影评估多模态大语言模型的视觉推理能力。

发布时间：2025年04月14日

`LLM应用` `计算机视觉`

> CameraBench: Benchmarking Visual Reasoning in MLLMs via Photography

# 摘要

> 大型语言模型（LLMs）和多模态大型语言模型（MLLMs）在人工智能领域取得了显著进展。然而，涉及视觉与文本输入的视觉推理领域仍待深入探索。近期，OpenAI o1和Gemini 2.0 Flash Thinking等视觉推理模型的引入为这一领域开辟了新可能。本研究聚焦于摄影相关任务，因为一张照片是物理世界的视觉快照，其中潜在的物理因素（如光照、模糊程度等）与相机参数相互作用。要从照片的视觉信息中成功推理出这些数值化相机设置，要求多模态大型语言模型对潜在物理规律有更深刻的理解，以实现精准的视觉感知。这一能力对于摄影辅助代理等实际应用至关重要，极具挑战性与智能性。我们旨在评估多模态大型语言模型在区分与数值化相机设置相关的视觉差异方面的能力，延续此前针对视觉-语言模型（VLMs）提出的方法。初步研究结果凸显了视觉推理在摄影相关任务中的重要性。此外，结果表明没有任何单一的多模态大型语言模型能在所有评估任务中始终占据优势，这凸显了在开发具备更优视觉推理能力的多模态大型语言模型方面所面临的持续挑战与机遇。

> Large language models (LLMs) and multimodal large language models (MLLMs) have significantly advanced artificial intelligence. However, visual reasoning, reasoning involving both visual and textual inputs, remains underexplored. Recent advancements, including the reasoning models like OpenAI o1 and Gemini 2.0 Flash Thinking, which incorporate image inputs, have opened this capability. In this ongoing work, we focus specifically on photography-related tasks because a photo is a visual snapshot of the physical world where the underlying physics (i.e., illumination, blur extent, etc.) interplay with the camera parameters. Successfully reasoning from the visual information of a photo to identify these numerical camera settings requires the MLLMs to have a deeper understanding of the underlying physics for precise visual comprehension, representing a challenging and intelligent capability essential for practical applications like photography assistant agents. We aim to evaluate MLLMs on their ability to distinguish visual differences related to numerical camera settings, extending a methodology previously proposed for vision-language models (VLMs). Our preliminary results demonstrate the importance of visual reasoning in photography-related tasks. Moreover, these results show that no single MLLM consistently dominates across all evaluation tasks, demonstrating ongoing challenges and opportunities in developing MLLMs with better visual reasoning.

[Arxiv](https://arxiv.org/abs/2504.10090)