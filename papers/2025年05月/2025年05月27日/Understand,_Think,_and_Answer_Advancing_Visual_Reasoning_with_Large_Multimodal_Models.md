# 理解、思考、回答：迈向更智能的视觉推理

发布时间：2025年05月27日

`LLM应用` `视觉理解` `多模态模型`

> Understand, Think, and Answer: Advancing Visual Reasoning with Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在视觉-语言和视觉中心任务中展现出卓越的视觉理解能力，但在整合先进且特定任务的组合推理能力方面仍显不足，这限制了其向真正强大的通用视觉模型发展。针对这一挑战，我们提出了一种统一的视觉推理机制，使LMMs能够通过其固有能力（如接地能力和视觉理解能力）解决复杂的组合问题。与传统的捷径学习机制不同，我们的方法引入了一种人类般的理解-思考-回答过程，使模型能够一次性完成所有推理步骤，无需多次推理或借助外部工具。这一创新设计填补了基础视觉能力和通用问答之间的鸿沟，推动LMMs为复杂视觉推理生成忠实且可追溯的回答。此外，我们精心整理了涵盖一般场景和文本丰富场景的334K视觉指令样本，涉及多种基础视觉能力。我们训练的模型Griffon-R具备端到端自动理解、自我思考和推理回答的能力。全面的实验表明，Griffon-R不仅在复杂视觉推理基准（如VSR和CLEVR）中表现优异，还在MMBench和ScienceQA等多模态基准测试中显著提升了多模态能力。相关数据、模型和代码即将发布于https://github.com/jefferyZhan/Griffon/tree/master/Griffon-R。

> Large Multimodal Models (LMMs) have recently demonstrated remarkable visual understanding performance on both vision-language and vision-centric tasks. However, they often fall short in integrating advanced, task-specific capabilities for compositional reasoning, which hinders their progress toward truly competent general vision models. To address this, we present a unified visual reasoning mechanism that enables LMMs to solve complicated compositional problems by leveraging their intrinsic capabilities (e.g. grounding and visual understanding capabilities). Different from the previous shortcut learning mechanism, our approach introduces a human-like understanding-thinking-answering process, allowing the model to complete all steps in a single pass forwarding without the need for multiple inferences or external tools. This design bridges the gap between foundational visual capabilities and general question answering, encouraging LMMs to generate faithful and traceable responses for complex visual reasoning. Meanwhile, we curate 334K visual instruction samples covering both general scenes and text-rich scenes and involving multiple foundational visual capabilities. Our trained model, Griffon-R, has the ability of end-to-end automatic understanding, self-thinking, and reasoning answers. Comprehensive experiments show that Griffon-R not only achieves advancing performance on complex visual reasoning benchmarks including VSR and CLEVR, but also enhances multimodal capabilities across various benchmarks like MMBench and ScienceQA. Data, models, and codes will be release at https://github.com/jefferyZhan/Griffon/tree/master/Griffon-R soon.

[Arxiv](https://arxiv.org/abs/2505.20753)