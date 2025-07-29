# RemoteReasoner：迈向地理空间推理工作流的统一方法

发布时间：2025年07月25日

`LLM应用` `地理空间分析`

> RemoteReasoner: Towards Unifying Geospatial Reasoning Workflow

# 摘要

> 遥感图像蕴含着大量本就无序的地理空间数据，解读这些数据需要复杂的推理能力，以理解超越简单识别任务的复杂用户意图和上下文关系。本文旨在构建一个地球观测工作流，通过推理空间上下文和用户意图来处理复杂查询。作为一个推理工作流，它应当具备某种程度的自主性，即预定义的推理路径不会限制学习过程。此外，其架构应当统一且灵活，使模型能够通过一次前向传播执行多种推理任务，输出不同格式的结果。现有遥感方法未能满足这些要求，因为它们依赖于监督微调范式，限制了推理的自主性。

为此，我们提出RemoteReasoner，一个灵活且健壮的遥感推理工作流。RemoteReasoner的设计整合了多模态大语言模型（MLLM）用于解析用户指令和定位目标，并结合任务适应策略，实现多粒度输出生成。与现有方法不同，我们的框架通过强化学习（RL）进行训练，赋予MLLM足够的自主性以实现精准推理。在推理阶段，我们的适应策略无需特定任务解码器或进一步微调，即可实现多种输出格式。

初步实验表明，RemoteReasoner在多粒度推理任务中表现出色，包括区域级和像素级推理。此外，我们的框架还支持现有推理流水线难以实现的新功能，如轮廓提取任务。


> Remote sensing imagery presents vast, inherently unstructured spatial data, demanding sophisticated reasoning to interpret complex user intents and contextual relationships beyond simple recognition tasks. In this paper, we aim to construct an Earth observation workflow to handle complex queries by reasoning about spatial context and user intent. As a reasoning workflow, it should be somewhat autonomous, where predefined ground-truth reasoning paths do not constrain the learning process. Furthermore, its architecture ought to be unified yet flexible, enabling the model to perform diverse reasoning tasks with distinct output formats through a single forward pass. Existing remote sensing approaches fail to address these requirements, as they rely on supervised fine-tuning paradigms that constrain the autonomy of reasoning. To this end, we propose RemoteReasoner, a flexible and robust workflow for remote sensing reasoning tasks. The design of RemoteReasoner integrates a multi-modal large language model (MLLM) for interpreting user instructions and localizing targets, together with task adaptation strategies that enable multi-granularity output generation. In contrast to existing methods, our framework is trained with reinforcement learning (RL) to endow the MLLM sufficient autonomy for precise reasoning. At the inference stage, our adaptation strategies enable diverse output formats at inference time without requiring task-specific decoders or further fine-tuning. Preliminary experiments demonstrated that RemoteReasoner achieves remarkable performance across multi-granularity reasoning tasks, including region-level and pixel-level. Additionally, our framework enables novel capabilities such as the contour extraction task beyond the reach of existing reasoning pipelines.

[Arxiv](https://arxiv.org/abs/2507.19280)