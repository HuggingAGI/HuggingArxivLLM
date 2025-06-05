# Struct2D：面向大型多模态模型的空间推理视觉引导框架

发布时间：2025年06月04日

`LLM应用` `计算机视觉` `三维空间推理`

> Struct2D: A Perception-Guided Framework for Spatial Reasoning in Large Multimodal Models

# 摘要

> 解锁大型多模态模型（LMMs）的空间推理能力，对于实现与3D环境的智能交互至关重要。过去的研究多依赖显式的3D输入或专用模型架构，而我们提出一个问题：仅使用从感知中提取的结构化2D表示，LMMs能否完成3D空间推理？我们推出Struct2D，一个感知引导的提示框架，巧妙结合鸟瞰图（BEV）图像、物体标记及基于物体的元数据，并在必要时融入以自我为中心的关键帧。通过Struct2D，我们对闭源LMMs（如GPT-o3）进行了深入的零样本分析，发现当提供结构化2D输入时，这些模型展现出惊人的空间推理能力，能够轻松应对相对方向估计和路线规划等任务。基于这一发现，我们构建了Struct2D-Set，一个涵盖八个空间推理类别的大规模指令微调数据集，包含20万条精细问答对，数据由3D室内场景自动生成。我们对开源LMM（Qwen2.5VL）进行了Struct2D-Set微调，使其在3D问答、密集描述和物体定位等多个基准测试中表现优异。我们的研究表明，结构化的2D输入能够有效连接LMMs中的感知与语言推理，无需依赖显式的3D输入。我们将开源代码和数据集，助力未来研究。

> Unlocking spatial reasoning in Large Multimodal Models (LMMs) is crucial for enabling intelligent interaction with 3D environments. While prior efforts often rely on explicit 3D inputs or specialized model architectures, we ask: can LMMs reason about 3D space using only structured 2D representations derived from perception? We introduce Struct2D, a perception-guided prompting framework that combines bird's-eye-view (BEV) images with object marks and object-centric metadata, optionally incorporating egocentric keyframes when needed. Using Struct2D, we conduct an in-depth zero-shot analysis of closed-source LMMs (e.g., GPT-o3) and find that they exhibit surprisingly strong spatial reasoning abilities when provided with structured 2D inputs, effectively handling tasks such as relative direction estimation and route planning. Building on these insights, we construct Struct2D-Set, a large-scale instruction tuning dataset with 200K fine-grained QA pairs across eight spatial reasoning categories, generated automatically from 3D indoor scenes. We fine-tune an open-source LMM (Qwen2.5VL) on Struct2D-Set, achieving competitive performance on multiple benchmarks, including 3D question answering, dense captioning, and object grounding. Our approach demonstrates that structured 2D inputs can effectively bridge perception and language reasoning in LMMs-without requiring explicit 3D representations as input. We will release both our code and dataset to support future research.

[Arxiv](https://arxiv.org/abs/2506.04220)