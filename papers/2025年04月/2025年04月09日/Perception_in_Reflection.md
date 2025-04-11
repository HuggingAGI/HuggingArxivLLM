# 静思中的知觉。

发布时间：2025年04月09日

`LLM理论

理由：这篇论文主要探讨了大型视觉语言模型（LVLMs）的改进方法，提出了反思感知范式（RePer）和相关的训练策略，属于模型理论的发展，因此归类为LLM理论。` `计算机视觉` `人工智能`

> Perception in Reflection

# 摘要

> 我们提出了一种反思感知范式，旨在突破现有大型视觉语言模型（LVLMs）的局限性。这些模型虽然被寄予厚望，却常难以完美呈现初始感知。具体而言，我们提出了"反思感知"（RePer），这是一种双模型反射机制，系统性地在策略模型与评估模型之间交替运行，从而实现视觉感知的迭代优化。这一框架由"反思感知学习"（RPL）驱动，通过精心构建的视觉反思数据集和反思式非似然训练方法，强化模型的内在反思能力。详尽的实验评估表明，RePer在图像理解、描述精度和幻觉减少等方面均有显著提升。值得注意的是，RePer实现了模型注意力模式与人类视觉焦点的高度对齐，同时RPL优化了细粒度和自由形式的偏好对齐。这些进展确立了反思感知作为未来多模态智能体的稳健范式，尤其在需要复杂推理和多步骤操作的任务中表现突出。

> We present a perception in reflection paradigm designed to transcend the limitations of current large vision-language models (LVLMs), which are expected yet often fail to achieve perfect perception initially. Specifically, we propose Reflective Perception (RePer), a dual-model reflection mechanism that systematically alternates between policy and critic models, enables iterative refinement of visual perception. This framework is powered by Reflective Perceptual Learning (RPL), which reinforces intrinsic reflective capabilities through a methodically constructed visual reflection dataset and reflective unlikelihood training. Comprehensive experimental evaluation demonstrates RePer's quantifiable improvements in image understanding, captioning precision, and hallucination reduction. Notably, RePer achieves strong alignment between model attention patterns and human visual focus, while RPL optimizes fine-grained and free-form preference alignment. These advancements establish perception in reflection as a robust paradigm for future multimodal agents, particularly in tasks requiring complex reasoning and multi-step manipulation.

[Arxiv](https://arxiv.org/abs/2504.07165)