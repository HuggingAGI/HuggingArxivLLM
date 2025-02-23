# Re-Align: 基于检索增强的直接偏好优化方法实现视觉-语言模型的再对齐

发布时间：2025年02月18日

`LLM应用` `视觉语言模型` `跨模态应用`

> Re-Align: Aligning Vision Language Models via Retrieval-Augmented Direct Preference Optimization

# 摘要

> 大型视觉语言模型（VLMs）通过整合视觉模态，拓宽了单模态大型语言模型（LLMs）的应用范围和能力，从而在多种实际场景中解锁了跨模态应用的变革性潜力。尽管VLMs表现优异，但它们容易出现显著的幻觉，尤其是在跨模态不一致方面。基于从人类反馈中进行强化学习（RLHF）在对齐LLMs方面的成功，最近的研究重点在于通过在精心策划的数据集上应用直接偏好优化（DPO）来缓解这些问题。然而，此类方法通常以一种 brute-force 的方式引入偏好信号，忽视了视觉信息在对齐过程中至关重要的作用。在本文中，我们引入了Re-Align，这是一个新颖的对齐框架，它利用图像检索构建一个双偏好数据集，有效整合了文本和视觉偏好信号。我们进一步引入了rDPO，这是标准直接偏好优化的扩展版本，在微调过程中额外引入了视觉偏好目标。我们的实验结果表明，与以往方法相比，Re-Align不仅更有效地缓解了幻觉问题，还在通用视觉问答（VQA）任务中带来了显著的性能提升。此外，我们展示了Re-Align在各种VLM规模和架构中保持了强大的稳健性和可扩展性。这项工作在对齐多模态LLMs方面迈出了重要一步，为更可靠和有效的跨模态应用铺平了道路。我们发布了所有代码在https://github.com/taco-group/Re-Align。

> The emergence of large Vision Language Models (VLMs) has broadened the scope and capabilities of single-modal Large Language Models (LLMs) by integrating visual modalities, thereby unlocking transformative cross-modal applications in a variety of real-world scenarios. Despite their impressive performance, VLMs are prone to significant hallucinations, particularly in the form of cross-modal inconsistencies. Building on the success of Reinforcement Learning from Human Feedback (RLHF) in aligning LLMs, recent advancements have focused on applying direct preference optimization (DPO) on carefully curated datasets to mitigate these issues. Yet, such approaches typically introduce preference signals in a brute-force manner, neglecting the crucial role of visual information in the alignment process. In this paper, we introduce Re-Align, a novel alignment framework that leverages image retrieval to construct a dual-preference dataset, effectively incorporating both textual and visual preference signals. We further introduce rDPO, an extension of the standard direct preference optimization that incorporates an additional visual preference objective during fine-tuning. Our experimental results demonstrate that Re-Align not only mitigates hallucinations more effectively than previous methods but also yields significant performance gains in general visual question-answering (VQA) tasks. Moreover, we show that Re-Align maintains robustness and scalability across a wide range of VLM sizes and architectures. This work represents a significant step forward in aligning multimodal LLMs, paving the way for more reliable and effective cross-modal applications. We release all the code in https://github.com/taco-group/Re-Align.

[Arxiv](https://arxiv.org/abs/2502.13146)