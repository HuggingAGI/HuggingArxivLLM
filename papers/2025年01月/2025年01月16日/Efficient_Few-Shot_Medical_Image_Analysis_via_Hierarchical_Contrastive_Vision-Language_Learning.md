# 基于分层对比视觉-语言学习的高效少样本医学图像分析

发布时间：2025年01月16日

`LLM应用

理由：该论文提出了一种名为HiCA的自适应视觉-语言微调框架，结合分层对比对齐，利用大型视觉-语言模型（LVLMs）进行医学图像分析。虽然论文主要关注的是视觉-语言模型在医学图像分类中的应用，但LVLMs通常与大型语言模型（LLMs）相关，尤其是在多模态任务中。因此，该论文可以被归类为LLM应用，因为它涉及将LLMs（或类似的模型）应用于特定领域（医学图像分类）的实际问题。` `医学图像分析`

> Efficient Few-Shot Medical Image Analysis via Hierarchical Contrastive Vision-Language Learning

# 摘要

> # 摘要
医学图像分类中的少样本学习因标注数据稀缺和图像复杂性而颇具挑战。本文提出了一种名为HiCA的自适应视觉-语言微调框架，结合分层对比对齐，利用大型视觉-语言模型（LVLMs）进行医学图像分析。HiCA采用两阶段微调策略，融合领域预训练与分层对比学习，实现多层次的视觉-文本对齐。我们在胸部X光和乳腺超声两个基准数据集上验证了该方法的有效性，在少样本和零样本场景下均取得了领先性能。进一步分析表明，该方法具备良好的鲁棒性、泛化性和可解释性，性能显著优于现有基线。本研究凸显了分层对比策略在应对医学成像任务挑战中的巨大潜力。

> Few-shot learning in medical image classification presents a significant challenge due to the limited availability of annotated data and the complex nature of medical imagery. In this work, we propose Adaptive Vision-Language Fine-tuning with Hierarchical Contrastive Alignment (HiCA), a novel framework that leverages the capabilities of Large Vision-Language Models (LVLMs) for medical image analysis. HiCA introduces a two-stage fine-tuning strategy, combining domain-specific pretraining and hierarchical contrastive learning to align visual and textual representations at multiple levels. We evaluate our approach on two benchmark datasets, Chest X-ray and Breast Ultrasound, achieving state-of-the-art performance in both few-shot and zero-shot settings. Further analyses demonstrate the robustness, generalizability, and interpretability of our method, with substantial improvements in performance compared to existing baselines. Our work highlights the potential of hierarchical contrastive strategies in adapting LVLMs to the unique challenges of medical imaging tasks.

[Arxiv](https://arxiv.org/abs/2501.09294)