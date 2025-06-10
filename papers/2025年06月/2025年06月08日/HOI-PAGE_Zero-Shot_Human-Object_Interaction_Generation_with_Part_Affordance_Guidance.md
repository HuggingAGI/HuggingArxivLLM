# # HOI-PAGE：基于部件使用可能性引导的零样本人-物交互生成

发布时间：2025年06月08日

`LLM应用` `计算机图形学` `计算机视觉`

> HOI-PAGE: Zero-Shot Human-Object Interaction Generation with Part Affordance Guidance

# 摘要

> 我们提出了HOI-PAGE，一种全新的零样本4D人-物互动（HOI）生成方法，通过基于部位的可用性推理驱动。与以往专注于全局整体身体-物体运动的4D HOI合成方法不同，我们发现生成逼真且多样的HOI需要更精细的理解——即人体部位与物体部位的交互方式。因此，我们引入了基于大型语言模型（LLMs）提炼的Part Affordance Graphs（PAGs），这是一种结构化的HOI表示方法，编码了精细的部位信息以及接触关系。随后，我们利用这些PAGs指导一个三阶段的合成过程：首先，将输入的3D物体分解为几何部位；其次，从文本提示生成参考HOI视频，并从中提取基于部位的运动约束；最后，优化4D HOI运动序列，使其不仅模仿参考动态，同时满足部位级别的接触约束。大量实验表明，我们的方法灵活且能够生成复杂的多物体或多人体交互序列，在零样本4D HOI生成中显著提升了真实感和文本对齐效果。

> We present HOI-PAGE, a new approach to synthesizing 4D human-object interactions (HOIs) from text prompts in a zero-shot fashion, driven by part-level affordance reasoning. In contrast to prior works that focus on global, whole body-object motion for 4D HOI synthesis, we observe that generating realistic and diverse HOIs requires a finer-grained understanding -- at the level of how human body parts engage with object parts. We thus introduce Part Affordance Graphs (PAGs), a structured HOI representation distilled from large language models (LLMs) that encodes fine-grained part information along with contact relations. We then use these PAGs to guide a three-stage synthesis: first, decomposing input 3D objects into geometric parts; then, generating reference HOI videos from text prompts, from which we extract part-based motion constraints; finally, optimizing for 4D HOI motion sequences that not only mimic the reference dynamics but also satisfy part-level contact constraints. Extensive experiments show that our approach is flexible and capable of generating complex multi-object or multi-person interaction sequences, with significantly improved realism and text alignment for zero-shot 4D HOI generation.

[Arxiv](https://arxiv.org/abs/2506.07209)