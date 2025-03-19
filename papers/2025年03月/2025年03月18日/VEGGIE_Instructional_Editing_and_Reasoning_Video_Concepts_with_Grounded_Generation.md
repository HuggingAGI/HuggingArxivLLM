# VEGGIE：通过扎根生成实现指令编辑与视频概念推理

发布时间：2025年03月18日

`LLM应用` `视频编辑` `视频处理`

> VEGGIE: Instructional Editing and Reasoning Video Concepts with Grounded Generation

# 摘要

> 近期，视频扩散模型在视频编辑领域取得了显著进展，但要在统一框架下处理指令性编辑和多样化任务（如添加、删除、更改）仍具挑战性。本文提出VEGGIE（Video Editor with Grounded Generation from Instructions），这是一个简单而高效的端到端框架，基于多样化的用户指令，实现了视频概念编辑、定位与推理功能的统一。具体而言，VEGGIE通过多语言大语言模型（MLLM）解析用户意图并将其与视频上下文关联，生成特定帧的定位任务查询以获得像素空间响应，随后利用扩散模型渲染这些计划并生成符合用户意图的编辑视频。为支持多样化的任务和复杂指令，我们采用 curriculum learning 策略：首先将 MLLM 和视频扩散模型与大规模指令性图像编辑数据对齐，随后在高质量多任务视频数据上进行端到端微调。此外，我们引入了创新的数据合成管道，生成配对的指令性视频编辑数据用于模型训练。该管道通过图像到视频模型注入动态特性，将静态图像数据转换为多样化的高质量视频编辑样本。VEGGIE在指令性视频编辑中展现了卓越的性能，凭借其多样的编辑技能，超越了最佳指令性基线模型，而其他模型在多任务处理上则表现乏力。VEGGIE在视频对象定位与推理分割方面同样表现出色，而其他基线方法往往难以完成这些任务。我们进一步揭示了多任务如何相互助力，并展望了零样本多模态指令和上下文视频编辑等有前景的应用。


> Recent video diffusion models have enhanced video editing, but it remains challenging to handle instructional editing and diverse tasks (e.g., adding, removing, changing) within a unified framework. In this paper, we introduce VEGGIE, a Video Editor with Grounded Generation from Instructions, a simple end-to-end framework that unifies video concept editing, grounding, and reasoning based on diverse user instructions. Specifically, given a video and text query, VEGGIE first utilizes an MLLM to interpret user intentions in instructions and ground them to the video contexts, generating frame-specific grounded task queries for pixel-space responses. A diffusion model then renders these plans and generates edited videos that align with user intent. To support diverse tasks and complex instructions, we employ a curriculum learning strategy: first aligning the MLLM and video diffusion model with large-scale instructional image editing data, followed by end-to-end fine-tuning on high-quality multitask video data. Additionally, we introduce a novel data synthesis pipeline to generate paired instructional video editing data for model training. It transforms static image data into diverse, high-quality video editing samples by leveraging Image-to-Video models to inject dynamics. VEGGIE shows strong performance in instructional video editing with different editing skills, outperforming the best instructional baseline as a versatile model, while other models struggle with multi-tasking. VEGGIE also excels in video object grounding and reasoning segmentation, where other baselines fail. We further reveal how the multiple tasks help each other and highlight promising applications like zero-shot multimodal instructional and in-context video editing.

[Arxiv](https://arxiv.org/abs/2503.14350)