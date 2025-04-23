# AdaViP：通过自适应视觉增强的偏好优化实现多模态大语言模型的对齐

发布时间：2025年04月22日

`LLM应用` `人工智能` `计算机视觉`

> AdaViP: Aligning Multi-modal LLMs via Adaptive Vision-enhanced Preference Optimization

# 摘要

> 通过直接偏好优化（DPO）实现偏好对齐，在使多模态大型语言模型（MLLMs）与人类偏好对齐方面表现出显著有效性。然而，现有方法大多关注语言偏好，却忽略了至关重要的视觉上下文。本文中，我们提出了一种自适应视觉增强偏好优化（AdaViP），通过两大关键创新来克服这些限制：（1）基于视觉的偏好对构建，该方法整合了多个视觉基础模型，战略性地从图像中移除关键视觉元素，从而增强了MLLMs对视觉细节的敏感度；（2）自适应偏好优化，该方法动态平衡视觉和语言偏好，以实现更精准的对齐。在不同基准上的广泛评估证明了我们的有效性。值得注意的是，我们的AdaViP-7B在Object HalBench上分别在响应级别和提及级别实现了93.7%和96.4%的幻觉减少，显著超越了当前最先进方法。

> Preference alignment through Direct Preference Optimization (DPO) has demonstrated significant effectiveness in aligning multimodal large language models (MLLMs) with human preferences. However, existing methods focus primarily on language preferences while neglecting the critical visual context. In this paper, we propose an Adaptive Vision-enhanced Preference optimization (AdaViP) that addresses these limitations through two key innovations: (1) vision-based preference pair construction, which integrates multiple visual foundation models to strategically remove key visual elements from the image, enhancing MLLMs' sensitivity to visual details; and (2) adaptive preference optimization that dynamically balances vision- and language-based preferences for more accurate alignment. Extensive evaluations across different benchmarks demonstrate our effectiveness. Notably, our AdaViP-7B achieves 93.7% and 96.4% reductions in response-level and mentioned-level hallucination respectively on the Object HalBench, significantly outperforming current state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2504.15619)