# LayoutVLM：借助视觉语言模型实现 3D 布局的可微优化

发布时间：2024年12月03日

`LLM应用` `3D 布局` `视觉语言模型`

> LayoutVLM: Differentiable Optimization of 3D Layout via Vision-Language Models

# 摘要

> Open-universe 3D 布局生成会依据语言指令来排列未标记的 3D 资产。大型语言模型（LLMs）在生成符合物理规律的 3D 场景以及遵循输入指令方面颇为吃力，在杂乱场景中更是如此。我们推出了 LayoutVLM，这是一种框架和场景布局的表示形式，它借助了视觉语言模型（VLMs）的语义知识，并支持可微优化以保障物理合理性。LayoutVLM 运用 VLMs 从带有视觉标记的图像中生成两种相互强化的表示，还有一个自洽的解码过程来优化 VLMs 的空间规划。我们的实验表明，LayoutVLM 克服了现有 LLM 和基于约束的方法的局限，生成了更符合输入语言指令语义意图、物理上合理的 3D 布局。同时，我们也证实，使用从现有场景数据集中提取的所提议的场景布局表示对 VLMs 进行微调能够提升性能。

> Open-universe 3D layout generation arranges unlabeled 3D assets conditioned on language instruction. Large language models (LLMs) struggle with generating physically plausible 3D scenes and adherence to input instructions, particularly in cluttered scenes. We introduce LayoutVLM, a framework and scene layout representation that exploits the semantic knowledge of Vision-Language Models (VLMs) and supports differentiable optimization to ensure physical plausibility. LayoutVLM employs VLMs to generate two mutually reinforcing representations from visually marked images, and a self-consistent decoding process to improve VLMs spatial planning. Our experiments show that LayoutVLM addresses the limitations of existing LLM and constraint-based approaches, producing physically plausible 3D layouts better aligned with the semantic intent of input language instructions. We also demonstrate that fine-tuning VLMs with the proposed scene layout representation extracted from existing scene datasets can improve performance.

[Arxiv](https://arxiv.org/abs/2412.02193)