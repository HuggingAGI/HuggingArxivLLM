# 3D-LLaVA：全能超点Transformer引领通用3D LMMs新纪元

发布时间：2025年01月02日

`LLM应用

理由：这篇论文提出了一个名为3D-LLaVA的3D大型多模态模型（3D LMM），旨在作为智能助手理解、推理并与3D世界交互。该模型通过极简设计，仅以点云为输入，并集成了视觉特征选择、视觉提示编码和参考掩码解码等功能。论文的核心是Omni Superpoint Transformer（OST），它通过混合预训练获得感知先验，并将3D数据与LLM桥接。经过统一指令调优，3D-LLaVA在多个基准测试中表现优异。这表明该论文主要关注如何将LLM应用于3D视觉对话和推理任务中，因此应归类为LLM应用。` `3D视觉` `人机交互`

> 3D-LLaVA: Towards Generalist 3D LMMs with Omni Superpoint Transformer

# 摘要

> # 摘要
当前3D大型多模态模型（3D LMMs）在3D视觉对话和推理中展现了巨大潜力，但如何进一步提升其细粒度场景理解和灵活人机交互能力仍具挑战。本文提出3D-LLaVA，一个简洁而强大的3D LMM，旨在作为智能助手理解、推理并与3D世界交互。与依赖复杂管道的现有方法不同，3D-LLaVA采用极简设计，仅以点云为输入。其核心是Omni Superpoint Transformer（OST），集成了视觉特征选择、视觉提示编码和参考掩码解码三大功能。OST通过混合预训练获得感知先验，并作为视觉连接器将3D数据与LLM桥接。经过统一指令调优，3D-LLaVA在多个基准测试中表现优异。代码和模型将开源，以推动未来研究。

> Current 3D Large Multimodal Models (3D LMMs) have shown tremendous potential in 3D-vision-based dialogue and reasoning. However, how to further enhance 3D LMMs to achieve fine-grained scene understanding and facilitate flexible human-agent interaction remains a challenging problem. In this work, we introduce 3D-LLaVA, a simple yet highly powerful 3D LMM designed to act as an intelligent assistant in comprehending, reasoning, and interacting with the 3D world. Unlike existing top-performing methods that rely on complicated pipelines-such as offline multi-view feature extraction or additional task-specific heads-3D-LLaVA adopts a minimalist design with integrated architecture and only takes point clouds as input. At the core of 3D-LLaVA is a new Omni Superpoint Transformer (OST), which integrates three functionalities: (1) a visual feature selector that converts and selects visual tokens, (2) a visual prompt encoder that embeds interactive visual prompts into the visual token space, and (3) a referring mask decoder that produces 3D masks based on text description. This versatile OST is empowered by the hybrid pretraining to obtain perception priors and leveraged as the visual connector that bridges the 3D data to the LLM. After performing unified instruction tuning, our 3D-LLaVA reports impressive results on various benchmarks. The code and model will be released to promote future exploration.

[Arxiv](https://arxiv.org/abs/2501.01163)