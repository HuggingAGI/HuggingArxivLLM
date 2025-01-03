# RE-tune: 生物医学视觉-语言模型的增量微调，助力多标签胸部X光分类

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）的能力来引导训练方向，特别是在多模态生物医学视觉-语言模型（VLMs）的微调过程中。虽然论文的核心是生物医学领域的应用，但其方法依赖于LLM的能力来优化模型性能，因此可以归类为LLM应用。` `生物医学`

> RE-tune: Incremental Fine Tuning of Biomedical Vision-Language Models for Multi-label Chest X-ray Classification

# 摘要

> 本文提出了一种名为RE-tune的新方法，用于在增量学习场景中微调预训练的多模态生物医学视觉-语言模型（VLMs），以进行多标签胸部疾病诊断。RE-tune冻结了模型的核心部分，仅在VLM的图像和文本编码器上训练简单的适配器。通过设计疾病的正负文本提示，我们利用大型语言模型的能力来引导训练方向。我们在类增量、标签增量和数据增量三种实际场景中评估了RE-tune。结果显示，生物医学VLMs天生具备持续学习能力，能够有效避免灾难性遗忘。RE-tune不仅实现了高精度的多标签分类，还注重患者隐私保护，并以其卓越的计算效率脱颖而出，非常适合在现实医疗环境中广泛应用。

> In this paper we introduce RE-tune, a novel approach for fine-tuning pre-trained Multimodal Biomedical Vision-Language models (VLMs) in Incremental Learning scenarios for multi-label chest disease diagnosis. RE-tune freezes the backbones and only trains simple adaptors on top of the Image and Text encoders of the VLM. By engineering positive and negative text prompts for diseases, we leverage the ability of Large Language Models to steer the training trajectory. We evaluate RE-tune in three realistic incremental learning scenarios: class-incremental, label-incremental, and data-incremental. Our results demonstrate that Biomedical VLMs are natural continual learners and prevent catastrophic forgetting. RE-tune not only achieves accurate multi-label classification results, but also prioritizes patient privacy and it distinguishes itself through exceptional computational efficiency, rendering it highly suitable for broad adoption in real-world healthcare settings.

[Arxiv](https://arxiv.org/abs/2410.17827)