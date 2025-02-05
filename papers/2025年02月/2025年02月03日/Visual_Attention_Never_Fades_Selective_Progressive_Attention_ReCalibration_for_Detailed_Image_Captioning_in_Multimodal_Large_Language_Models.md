# 视觉注意力永不消退：多模态大语言模型中渐进式选择性注意力重校准助力精细图像描述

发布时间：2025年02月03日

`LLM应用

**理由**：该论文主要讨论的是多模态大型语言模型（MLLMs）在详细图像描述任务中的应用，特别是通过提出的SPARC方法来改进模型的性能。虽然涉及多模态和视觉注意力等复杂概念，但其核心仍然是关于如何应用和改进大型语言模型来解决实际问题，因此应归类为LLM应用。` `计算机视觉` `辅助技术`

> Visual Attention Never Fades: Selective Progressive Attention ReCalibration for Detailed Image Captioning in Multimodal Large Language Models

# 摘要

> # 详细图像描述
详细图像描述在数据生成和辅助视障人士等任务中至关重要。高质量的描述需要在精确度和召回率之间找到平衡，这对当前的多模态大型语言模型（MLLMs）来说仍具挑战性。我们假设这一限制源于随着描述变长，视觉注意力逐渐减弱且噪声增加。为此，我们提出了SPARC（选择性渐进注意力重新校准），一种无需训练的方法，能在解码过程中增强视觉标记的贡献。SPARC基于三个关键发现：（1）增加所有视觉标记的影响会降低召回率，因此SPARC选择性地放大视觉标记；（2）随着描述变长，视觉注意力噪声增加，SPARC通过时间步间的注意力差异识别关键视觉标记；（3）视觉注意力逐渐减弱，SPARC通过强化注意力来保持其影响力。实验表明，现有方法以召回率为代价提升精确度，而SPARC则以最小计算开销同时提升精确度和召回率。

> Detailed image captioning is essential for tasks like data generation and aiding visually impaired individuals. High-quality captions require a balance between precision and recall, which remains challenging for current multimodal large language models (MLLMs). In this work, we hypothesize that this limitation stems from weakening and increasingly noisy visual attention as responses lengthen. To address this issue, we propose SPARC (Selective Progressive Attention ReCalibration), a training-free method that enhances the contribution of visual tokens during decoding. SPARC is founded on three key observations: (1) increasing the influence of all visual tokens reduces recall; thus, SPARC selectively amplifies visual tokens; (2) as captions lengthen, visual attention becomes noisier, so SPARC identifies critical visual tokens by leveraging attention differences across time steps; (3) as visual attention gradually weakens, SPARC reinforces it to preserve its influence. Our experiments, incorporating both automated and human evaluations, demonstrate that existing methods improve the precision of MLLMs at the cost of recall. In contrast, our proposed method enhances both precision and recall with minimal computational overhead.

[Arxiv](https://arxiv.org/abs/2502.01419)