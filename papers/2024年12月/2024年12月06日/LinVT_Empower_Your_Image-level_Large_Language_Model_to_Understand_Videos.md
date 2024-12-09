# LinVT：助力您的图像级大型语言模型理解视频

发布时间：2024年12月06日

`LLM应用` `多模态`

> LinVT: Empower Your Image-level Large Language Model to Understand Videos

# 摘要

> 大型语言模型（LLMs）已在各类任务中广泛应用，这促使我们开发基于 LLM 的视频助手。我们并非从零开始训练，而是提出一个模块，将任意训练有素的基于图像的 LLMs 转化为视频-LLMs（在经过视频数据训练后）。为让基于图像的 LLMs 更好地处理视频，我们引入了两项设计原则：线性变换以保留原始的视觉语言对齐，以及从冗余视频内容中凝练代表性信息。在这些原则的指引下，我们推出了一个即插即用的线性视频标记器（LinVT），使现有的基于图像的 LLMs 能够理解视频。我们用六个近期的视觉 LLMs 对 LinVT 进行了基准测试，包括 Aquila、Blip-3、InternVL2、Mipha、Molmo 和 Qwen2-VL，展现了 LinVT 的高度兼容性。基于 LinVT 的 LLMs 在各种视频基准测试中取得了最先进的性能，彰显了 LinVT 在多模态视频理解方面的有效性。

> Large Language Models (LLMs) have been widely used in various tasks, motivating us to develop an LLM-based assistant for videos. Instead of training from scratch, we propose a module to transform arbitrary well-trained image-based LLMs into video-LLMs (after being trained on video data). To better adapt image-LLMs for processing videos, we introduce two design principles: linear transformation to preserve the original visual-language alignment and representative information condensation from redundant video content. Guided by these principles, we propose a plug-and-play Linear Video Tokenizer(LinVT), which enables existing image-LLMs to understand videos. We benchmark LinVT with six recent visual LLMs: Aquila, Blip-3, InternVL2, Mipha, Molmo and Qwen2-VL, showcasing the high compatibility of LinVT. LinVT-based LLMs achieve state-of-the-art performance across various video benchmarks, illustrating the effectiveness of LinVT in multi-modal video understanding.

[Arxiv](https://arxiv.org/abs/2412.05185)