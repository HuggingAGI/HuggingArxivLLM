# 通过仅解码器模型优化视觉-语言交互

发布时间：2024年12月14日

`LLM应用

理由：这篇论文主要讨论了一种新的多模态模型（MUDAIF），它通过创新的方法融合视觉和文本输入，提升了跨模态理解能力。虽然论文中提到了视觉-语言模型（VLMs），但其核心是改进多模态任务的表现，特别是视觉问答（VQA）、图像描述和多模态推理等任务。这些任务属于LLM在实际应用中的扩展和优化，因此归类为LLM应用。` `视觉问答` `多模态学习`

> Optimizing Vision-Language Interactions Through Decoder-Only Models

# 摘要

> # 摘要
视觉-语言模型（VLMs）是多模态任务的核心技术，但其依赖独立视觉编码器，导致效率、可扩展性和模态对齐方面的挑战。为此，我们提出了MUDAIF（多模态统一解码器），它通过创新的视觉-令牌适配器（VTA）和自适应共注意力机制，无缝融合视觉与文本输入。MUDAIF无需视觉编码器，显著提升了效率、灵活性和跨模态理解能力。在4500万图像-文本对的大规模数据集上训练后，MUDAIF在视觉问答（VQA）、图像描述和多模态推理等任务中表现卓越，超越了现有方法。通过深入分析和人类评估，MUDAIF展现了强大的鲁棒性、泛化能力和实用性，成为无编码器视觉-语言模型的新标杆。

> Vision-Language Models (VLMs) have emerged as key enablers for multimodal tasks, but their reliance on separate visual encoders introduces challenges in efficiency, scalability, and modality alignment. To address these limitations, we propose MUDAIF (Multimodal Unified Decoder with Adaptive Input Fusion), a decoder-only vision-language model that seamlessly integrates visual and textual inputs through a novel Vision-Token Adapter (VTA) and adaptive co-attention mechanism. By eliminating the need for a visual encoder, MUDAIF achieves enhanced efficiency, flexibility, and cross-modal understanding. Trained on a large-scale dataset of 45M image-text pairs, MUDAIF consistently outperforms state-of-the-art methods across multiple benchmarks, including VQA, image captioning, and multimodal reasoning tasks. Extensive analyses and human evaluations demonstrate MUDAIF's robustness, generalization capabilities, and practical usability, establishing it as a new standard in encoder-free vision-language models.

[Arxiv](https://arxiv.org/abs/2412.10758)