# VITA-1.5: 迈向 GPT-4o 级别的实时视觉与语音交互

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论的是多模态大型语言模型（MLLMs）在视觉与语音交互中的应用，特别是如何通过多阶段训练方法提升模型在视觉与语音任务中的性能。这属于将大型语言模型应用于具体场景（多模态对话系统）的研究，因此归类为“LLM应用”。` `语音交互` `多模态系统`

> VITA-1.5: Towards GPT-4o Level Real-Time Vision and Speech Interaction

# 摘要

> # 摘要
最近的多模态大型语言模型（MLLMs）大多聚焦于视觉与文本的融合，却忽视了语音在交互中的重要作用。然而，语音在多模态对话系统中至关重要，而由于模态间的本质差异，同时实现视觉与语音任务的高性能仍是一大挑战。本文提出了一种精心设计的多阶段训练方法，逐步训练LLM理解视觉与语音信息，最终实现流畅的视觉与语音交互。我们的方法不仅保持了强大的视觉-语言能力，还无需依赖独立的ASR和TTS模块，实现了高效的语音对话能力，大幅提升了多模态端到端响应速度。通过在图像、视频和语音任务的基准测试中与顶尖模型对比，我们展示了模型在视觉与语音上的强大能力，实现了近乎实时的视觉与语音交互。

> Recent Multimodal Large Language Models (MLLMs) have typically focused on integrating visual and textual modalities, with less emphasis placed on the role of speech in enhancing interaction. However, speech plays a crucial role in multimodal dialogue systems, and implementing high-performance in both vision and speech tasks remains a significant challenge due to the fundamental modality differences. In this paper, we propose a carefully designed multi-stage training methodology that progressively trains LLM to understand both visual and speech information, ultimately enabling fluent vision and speech interaction. Our approach not only preserves strong vision-language capacity, but also enables efficient speech-to-speech dialogue capabilities without separate ASR and TTS modules, significantly accelerating multimodal end-to-end response speed. By comparing our method against state-of-the-art counterparts across benchmarks for image, video, and speech tasks, we demonstrate that our model is equipped with both strong visual and speech capabilities, making near real-time vision and speech interaction.

[Arxiv](https://arxiv.org/abs/2501.01957)