# REF-VLM：基于三元组的统一视觉解码引用范式

发布时间：2025年03月10日

`LLM应用` `多模态`

> REF-VLM: Triplet-Based Referring Paradigm for Unified Visual Decoding

# 摘要

> 多模态大型语言模型（MLLMs）经过大规模数据集训练后，在各类视觉语言任务中展现出强大的零样本能力。然而，仅以文本输出形式呈现的密集预测任务，如语义分割和关键点检测，对MLLMs仍具重大挑战。同时，当前使用潜在嵌入进行视觉任务解码的MLLMs在多任务学习和多粒度场景下适应性有限。在此，我们提出了REF-VLM，一个用于统一训练各种视觉解码任务的端到端框架。为应对复杂视觉解码场景，我们引入了基于三元组的引用范式（TRP），通过三元组结构明确解耦视觉解码任务中的三个关键维度：概念、解码类型和目标。TRP采用符号分隔符实现结构化表示学习，提升模型输出的可解析性和可解释性。同时，我们构建了视觉任务指令遵循数据集（VTInstruct），一个包含25种任务类型、超过1亿个多模态对话样本的大规模多任务数据集。VTInstruct不仅涵盖文本输入输出，还整合了点、框、涂鸦和掩膜等多种视觉提示，并生成由文本和视觉单元（如框、关键点、深度和掩膜）组成的输出。不同视觉提示与视觉单元的组合衍生出多样化的任务类型，显著拓展了REF-VLM的应用范围。实验结果表明，无论是定性还是定量分析，REF-VLM在各类标准基准上均超越现有MLLMs。代码、数据集和演示可访问https://github.com/MacavityT/REF-VLM获取。

> Multimodal Large Language Models (MLLMs) demonstrate robust zero-shot capabilities across diverse vision-language tasks after training on mega-scale datasets. However, dense prediction tasks, such as semantic segmentation and keypoint detection, pose significant challenges for MLLMs when represented solely as text outputs. Simultaneously, current MLLMs utilizing latent embeddings for visual task decoding generally demonstrate limited adaptability to both multi-task learning and multi-granularity scenarios. In this work, we present REF-VLM, an end-to-end framework for unified training of various visual decoding tasks. To address complex visual decoding scenarios, we introduce the Triplet-Based Referring Paradigm (TRP), which explicitly decouples three critical dimensions in visual decoding tasks through a triplet structure: concepts, decoding types, and targets. TRP employs symbolic delimiters to enforce structured representation learning, enhancing the parsability and interpretability of model outputs. Additionally, we construct Visual-Task Instruction Following Dataset (VTInstruct), a large-scale multi-task dataset containing over 100 million multimodal dialogue samples across 25 task types. Beyond text inputs and outputs, VT-Instruct incorporates various visual prompts such as point, box, scribble, and mask, and generates outputs composed of text and visual units like box, keypoint, depth and mask. The combination of different visual prompts and visual units generates a wide variety of task types, expanding the applicability of REF-VLM significantly. Both qualitative and quantitative experiments demonstrate that our REF-VLM outperforms other MLLMs across a variety of standard benchmarks. The code, dataset, and demo available at https://github.com/MacavityT/REF-VLM.

[Arxiv](https://arxiv.org/abs/2503.07413)