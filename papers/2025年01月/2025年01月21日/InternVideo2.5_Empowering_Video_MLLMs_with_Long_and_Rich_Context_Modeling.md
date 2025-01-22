# InternVideo2.5：通过长且丰富的上下文建模，赋能视频多模态大语言模型

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要讨论了通过长且丰富的上下文（LRC）建模来提升视频多模态大型语言模型（MLLM）的性能，并提出了具体的模型改进方法（如直接偏好优化和自适应分层令牌压缩）。这些改进方法直接应用于视频理解任务，属于大型语言模型在实际应用中的优化和扩展，因此应归类为LLM应用。` `视频理解` `多模态学习`

> InternVideo2.5: Empowering Video MLLMs with Long and Rich Context Modeling

# 摘要

> 本文通过长且丰富的上下文（LRC）建模，旨在提升视频多模态大型语言模型（MLLM）的性能。为此，我们推出了InternVideo2.5，重点增强MLLM在感知视频细粒度细节和捕捉长时间结构方面的能力。具体而言，我们通过直接偏好优化将密集视觉任务注释融入MLLM，并利用自适应分层令牌压缩生成紧凑的时空表示。实验显示，这一独特的LRC设计显著提升了视频MLLM在主流视频理解基准（短和长）上的表现，使其能够记忆更长的视频输入（至少比原版长6倍），并掌握对象跟踪和分割等高级视觉能力。我们的研究凸显了多模态上下文丰富性（长度与精细度）在强化MLLM固有能力（专注力与记忆力）中的关键作用，为未来视频MLLM研究提供了新思路。代码和模型已开源，详见https://github.com/OpenGVLab/InternVideo/tree/main/InternVideo2.5。

> This paper aims to improve the performance of video multimodal large language models (MLLM) via long and rich context (LRC) modeling. As a result, we develop a new version of InternVideo2.5 with a focus on enhancing the original MLLMs' ability to perceive fine-grained details and capture long-form temporal structure in videos. Specifically, our approach incorporates dense vision task annotations into MLLMs using direct preference optimization and develops compact spatiotemporal representations through adaptive hierarchical token compression. Experimental results demonstrate this unique design of LRC greatly improves the results of video MLLM in mainstream video understanding benchmarks (short & long), enabling the MLLM to memorize significantly longer video inputs (at least 6x longer than the original), and master specialized vision capabilities like object tracking and segmentation. Our work highlights the importance of multimodal context richness (length and fineness) in empowering MLLM's innate abilites (focus and memory), providing new insights for future research on video MLLM. Code and models are available at https://github.com/OpenGVLab/InternVideo/tree/main/InternVideo2.5

[Arxiv](https://arxiv.org/abs/2501.12386)