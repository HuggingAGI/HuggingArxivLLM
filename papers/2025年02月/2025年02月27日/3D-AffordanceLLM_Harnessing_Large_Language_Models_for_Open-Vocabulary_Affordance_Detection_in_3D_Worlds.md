# 3D-AffordanceLLM：驾驭大型语言模型进行开放词汇3D环境中的可及性检测

发布时间：2025年02月27日

`LLM应用

这篇论文属于LLM应用类别，因为它详细描述了如何将大型语言模型应用于3D可用性检测任务，提出了创新的框架和方法，并展示了其在实际应用中的有效性。` `机器人` `人工智能`

> 3D-AffordanceLLM: Harnessing Large Language Models for Open-Vocabulary Affordance Detection in 3D Worlds

# 摘要

> # 3D可用性检测：从挑战到突破

3D可用性检测是机器人领域的重要课题，具有广泛的应用前景。然而，现有方法主要依赖基于标签的语义分割范式，存在以下局限：

- 严重依赖预定义标签
- 无法理解复杂自然语言
- 开放场景泛化能力不足

为突破这些限制，我们提出了一种全新的	extit{Instruction Reasoning Affordance Segmentation} (IRAS)任务框架。该框架能够根据输入的推理文本自适应生成可用性掩膜，摆脱了传统固定标签类别的束缚。

我们开发了	extit{3D-AffordanceLLM}（简称3D-ADLLM）框架，专为3D开放场景下的推理可用性检测设计。该框架具有以下创新点：

- 将大型语言模型（LLMs）引入3D可用性感知
- 采用自定义解码器生成可用性掩膜
- 实现开放世界推理可用性检测

针对3D可用性数据集稀缺的难题，我们提出了创新的迁移学习方案：

1. **预训练阶段**：通过	extit{Referring Object Part Segmentation} (ROPS)任务，培养模型的物体部件级识别与分割能力
2. **微调阶段**：基于IRAS任务进行优化，赋予模型推理可用性检测的能力

实验结果表明，3D-ADLLM在开放词汇可用性检测任务中，mIoU指标提升了约8\%，充分证明了其优越性。这一提升得益于：
- LLMs丰富的世界知识
- 强大的人机交互推理能力
- 创新的多阶段训练策略
- 高效的知识迁移机制


> 3D Affordance detection is a challenging problem with broad applications on various robotic tasks. Existing methods typically formulate the detection paradigm as a label-based semantic segmentation task. This paradigm relies on predefined labels and lacks the ability to comprehend complex natural language, resulting in limited generalization in open-world scene. To address these limitations, we reformulate the traditional affordance detection paradigm into \textit{Instruction Reasoning Affordance Segmentation} (IRAS) task. This task is designed to output a affordance mask region given a query reasoning text, which avoids fixed categories of input labels. We accordingly propose the \textit{3D-AffordanceLLM} (3D-ADLLM), a framework designed for reasoning affordance detection in 3D open-scene. Specifically, 3D-ADLLM introduces large language models (LLMs) to 3D affordance perception with a custom-designed decoder for generating affordance masks, thus achieving open-world reasoning affordance detection. In addition, given the scarcity of 3D affordance datasets for training large models, we seek to extract knowledge from general segmentation data and transfer it to affordance detection. Thus, we propose a multi-stage training strategy that begins with a novel pre-training task, i.e., \textit{Referring Object Part Segmentation}~(ROPS). This stage is designed to equip the model with general recognition and segmentation capabilities at the object-part level. Then followed by fine-tuning with the IRAS task, 3D-ADLLM obtains the reasoning ability for affordance detection. In summary, 3D-ADLLM leverages the rich world knowledge and human-object interaction reasoning ability of LLMs, achieving approximately an 8\% improvement in mIoU on open-vocabulary affordance detection tasks.

[Arxiv](https://arxiv.org/abs/2502.20041)