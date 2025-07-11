# 基于多模态大语言模型的单一到混合模态对齐方法，用于文档图像机器翻译研究

发布时间：2025年07月10日

`LLM应用` `文档处理` `机器翻译`

> Single-to-mix Modality Alignment with Multimodal Large Language Model for Document Image Machine Translation

# 摘要

> # 摘要
文档图像机器翻译（DIMT）旨在将文档图像中的文本进行翻译，但由于训练数据有限以及视觉和文本信息之间复杂的相互作用，DIMT在泛化能力方面面临挑战。为了解决这些问题，我们引入了M4Doc，这是一个基于多模态大型语言模型（MLLMs）的新型单模态到混合模态对齐框架。M4Doc通过大规模文档图像数据集预训练，将仅图像的编码器与MLLM的多模态表示进行对齐。这种对齐使轻量级的DIMT模型能够在训练过程中学习关键的视觉-文本相关性。在推理阶段，M4Doc绕过了MLLM，保持了计算效率的同时，仍然能够利用其多模态知识。全面的实验结果表明，M4Doc在翻译质量方面取得了显著提升，尤其是在跨领域泛化和处理具有挑战性的文档图像场景中。

> Document Image Machine Translation (DIMT) aims to translate text within document images, facing generalization challenges due to limited training data and the complex interplay between visual and textual information. To address these challenges, we introduce M4Doc, a novel single-to-mix modality alignment framework leveraging Multimodal Large Language Models (MLLMs). M4Doc aligns an image-only encoder with the multimodal representations of an MLLM, pre-trained on large-scale document image datasets. This alignment enables a lightweight DIMT model to learn crucial visual-textual correlations during training. During inference, M4Doc bypasses the MLLM, maintaining computational efficiency while benefiting from its multimodal knowledge. Comprehensive experiments demonstrate substantial improvements in translation quality, especially in cross-domain generalization and challenging document image scenarios.

[Arxiv](https://arxiv.org/abs/2507.07572)