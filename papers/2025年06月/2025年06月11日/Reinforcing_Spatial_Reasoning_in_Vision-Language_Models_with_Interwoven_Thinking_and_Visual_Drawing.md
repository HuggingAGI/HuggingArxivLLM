# 结合交织思维与视觉绘制强化视觉语言模型的空间推理能力

发布时间：2025年06月11日

`LLM应用` `计算机视觉` `空间推理`

> Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing

# 摘要

> 随着大型语言模型（LLMs）在文本推理领域的显著突破，提升大型视觉语言模型（LVLMs）的多模态推理能力成为了研究热点。然而，现有方法主要采用直接的文本中心方式处理多模态推理，其推理和答案推导完全依赖文本，仅在输入端加入了多模态元素。这种单一的文本处理方式在需要精确几何理解以及持续空间追踪的空间推理任务中常常力不从心——这些能力对人类而言是通过心理可视化和操作轻松实现的。为突破这一限制，我们提出了一种全新的推理范式：通过绘图进行空间推理。这一方法使LVLMs能够通过基本的绘图操作在视觉空间中进行推理。通过赋予模型标注边界框和绘制辅助线等基本绘图能力，我们让它们能够通过直接的视觉操作表达和分析空间关系，同时绕开了传统工具集成推理方法中专用感知工具带来的性能瓶颈。为了实现这一能力，我们设计了一个三阶段的训练框架：首先利用合成数据进行冷启动训练以建立基础绘图能力，随后通过反思拒绝采样增强模型的自我反思行为，最后借助强化学习直接优化目标奖励。大量实验结果表明，我们的模型VILASR在迷宫导航、静态空间推理、视频推理和多视图推理等多样化空间推理任务中，均显著优于现有方法，平均性能提升了18.4%。

> As textual reasoning with large language models (LLMs) has advanced significantly, there has been growing interest in enhancing the multimodal reasoning capabilities of large vision-language models (LVLMs). However, existing methods primarily approach multimodal reasoning in a straightforward, text-centric manner, where both reasoning and answer derivation are conducted purely through text, with the only difference being the presence of multimodal input. As a result, these methods often encounter fundamental limitations in spatial reasoning tasks that demand precise geometric understanding and continuous spatial tracking-capabilities that humans achieve through mental visualization and manipulation. To address the limitations, we propose drawing to reason in space, a novel paradigm that enables LVLMs to reason through elementary drawing operations in the visual space. By equipping models with basic drawing operations, including annotating bounding boxes and drawing auxiliary lines, we empower them to express and analyze spatial relationships through direct visual manipulation, meanwhile avoiding the performance ceiling imposed by specialized perception tools in previous tool-integrated reasoning approaches. To cultivate this capability, we develop a three-stage training framework: cold-start training with synthetic data to establish basic drawing abilities, reflective rejection sampling to enhance self-reflection behaviors, and reinforcement learning to directly optimize for target rewards. Extensive experiments demonstrate that our model, named VILASR, consistently outperforms existing methods across diverse spatial reasoning benchmarks, involving maze navigation, static spatial reasoning, video-based reasoning, and multi-view-based reasoning tasks, with an average improvement of 18.4%.

[Arxiv](https://arxiv.org/abs/2506.09965)