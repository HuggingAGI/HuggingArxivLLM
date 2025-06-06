# RSVP：基于视觉提示和多模态思维链的推理分割

发布时间：2025年06月03日

`LLM应用` `计算机视觉` `图像分割`

> RSVP: Reasoning Segmentation via Visual Prompting and Multi-modal Chain-of-Thought

# 摘要

> 多模态大型语言模型（MLLMs）虽然展现了卓越的推理能力，但其在视觉定位和分割方面的能力仍有待提升，导致认知推理与视觉感知之间存在明显差距。针对这一问题，我们提出了一种名为通过视觉提示进行推理分割（Reasoning Segmentation via Visual Prompting，RSVP）的创新框架，该框架巧妙地将多步骤多模态推理与基于视觉的理解相结合。RSVP采用分阶段的结构化设计，整合了推理驱动的定位与分割优化两大核心功能。在推理阶段，RSVP借助多模态链式思维视觉提示，帮助MLLMs深入理解查询并精准推断目标，生成可解释的区域建议，从而显著增强视觉定位效果。进入分割阶段后，RSVP通过视觉语言分割模块（VLSM）对初步建议进行优化，无缝整合文本和视觉线索，最终生成精确的分割掩膜。通过显式建模多模态推理与分割之间的相互作用，RSVP开创了一种全新的可解释推理分割范式。它充分利用MLLMs固有的定位能力，使模型不仅能够进行物体推理，还能生成结构化的视觉表示。实验结果表明，RSVP在性能上实现了重大突破，在ReasonSeg基准测试中，其gIoU和cIoU分别超越现有最优方法高达+6.5和+9.2，在零样本设置下的SegInW测试中达到了49.7 mAP的优异成绩。这些结果充分验证了RSVP作为一种有效且可扩展的框架，成功实现了认知推理与结构化视觉理解的深度结合。

> Multi-modal Large Language Models (MLLMs) have demonstrated remarkable reasoning capability while lack explicit mechanisms for visual grounding and segmentation, creating a gap between cognitive reasoning and visual perception. To bridge this gap, we introduce Reasoning Segmentation via Visual Prompting (RSVP), a novel framework that unifies multi-step multimodal reasoning with grounded visual understanding. RSVP is a two-stage structuralized framework that integrates reasoning-driven localization with segmentation refinement. In the reasoning stage, RSVP employs multimodal chain-of-thought visual prompts to help MLLMs understand queries and infer targets, generating interpretable region proposals that enhance visual grounding. In segmentation stage, RSVP refines these proposals with a Vision-Language Segmentation Module (VLSM), seamlessly integrates textual and visual cues to produce precise segmentation masks. By explicitly modelling the interaction between multimodal reasoning and segmentation, RSVP introduces a new paradigm for interpretable reasoning segmentation. It exploits MLLMs' inherent localization capabilities, enabling the models to not only reason about objects but also generate structured visual representations. Our extensive experiments demonstrate that RSVP achieves state-of-the-art performance, surpasses state-of-the-art methods by up to +6.5 gIoU and +9.2 cIoU on ReasonSeg, and achieves 49.7 mAP on SegInW under zero-shot settings. These results validate RSVP as an effective and scalable framework for integrating cognitive reasoning with structured visual understanding.

[Arxiv](https://arxiv.org/abs/2506.04277)