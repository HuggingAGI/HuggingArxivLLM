# 通过动态视觉语言对齐攻击提升多语言大语言模型的对抗迁移能力

发布时间：2025年02月26日

`LLM应用` `人工智能安全` `多模态模型`

> Improving Adversarial Transferability in MLLMs via Dynamic Vision-Language Alignment Attack

# 摘要

> 多模态大型语言模型（MLLMs）凭借其图像识别与理解能力，近期受到了广泛关注。然而，尽管MLLMs易受对抗攻击影响，但这些攻击在不同模型间的转移性仍受限，尤其在针对性攻击场景下。现有方法主要针对视觉特定扰动，但在处理视觉-语言模态对齐的复杂性上存在局限。本研究提出了一种名为动态视觉-语言对齐（DynVLA）攻击的新方法，通过向视觉-语言连接器注入动态扰动，提升跨不同模型的视觉-语言对齐泛化能力。实验结果表明，DynVLA显著增强了BLIP2、InstructBLIP、MiniGPT4、LLaVA及闭源模型如Gemini等多模态大型语言模型间对抗样本的转移性。

> Multimodal Large Language Models (MLLMs), built upon LLMs, have recently gained attention for their capabilities in image recognition and understanding. However, while MLLMs are vulnerable to adversarial attacks, the transferability of these attacks across different models remains limited, especially under targeted attack setting. Existing methods primarily focus on vision-specific perturbations but struggle with the complex nature of vision-language modality alignment. In this work, we introduce the Dynamic Vision-Language Alignment (DynVLA) Attack, a novel approach that injects dynamic perturbations into the vision-language connector to enhance generalization across diverse vision-language alignment of different models. Our experimental results show that DynVLA significantly improves the transferability of adversarial examples across various MLLMs, including BLIP2, InstructBLIP, MiniGPT4, LLaVA, and closed-source models such as Gemini.

[Arxiv](https://arxiv.org/abs/2502.19672)