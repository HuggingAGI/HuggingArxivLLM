# 稀疏自编码器在视觉语言模型中学习单义特征

发布时间：2025年04月03日

`LLM理论` `计算机视觉` `多模态`

> Sparse Autoencoders Learn Monosemantic Features in Vision-Language Models

# 摘要

> 稀疏自动编码器（SAEs）在提升大型语言模型（LLMs）的可解释性和可控性方面表现出色。本研究将SAEs的应用扩展至视觉语言模型（VLMs），如CLIP，并提出了一种全面框架来评估视觉表示的单义性。实验结果表明，针对VLMs训练的SAEs不仅显著提升了单个神经元的单义性，还展现了与专家定义结构（如iNaturalist分类法）高度一致的层次化表示。尤为重要的是，我们成功展示了通过将SAEs应用于CLIP视觉编码器进行干预，可以直接引导多模态LLMs（如LLaVA）的输出，且无需对底层模型进行任何修改。这些发现凸显了SAEs作为无监督方法在增强VLMs可解释性和控制能力方面的实用性和有效性。

> Sparse Autoencoders (SAEs) have recently been shown to enhance interpretability and steerability in Large Language Models (LLMs). In this work, we extend the application of SAEs to Vision-Language Models (VLMs), such as CLIP, and introduce a comprehensive framework for evaluating monosemanticity in vision representations. Our experimental results reveal that SAEs trained on VLMs significantly enhance the monosemanticity of individual neurons while also exhibiting hierarchical representations that align well with expert-defined structures (e.g., iNaturalist taxonomy). Most notably, we demonstrate that applying SAEs to intervene on a CLIP vision encoder, directly steer output from multimodal LLMs (e.g., LLaVA) without any modifications to the underlying model. These findings emphasize the practicality and efficacy of SAEs as an unsupervised approach for enhancing both the interpretability and control of VLMs.

[Arxiv](https://arxiv.org/abs/2504.02821)