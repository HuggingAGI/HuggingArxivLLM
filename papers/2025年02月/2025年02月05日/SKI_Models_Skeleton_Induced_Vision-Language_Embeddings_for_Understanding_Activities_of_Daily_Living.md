# SKI 模型：骨架驱动的视觉-语言嵌入，助力日常生活活动理解

发布时间：2025年02月05日

`LLM应用

**理由**：这篇论文主要讨论了如何将3D骨架信息融入视觉-语言模型（VLMs）和大型视觉语言模型（LVLMs），以提升模型在日常生活活动（ADL）视频中的表现。虽然论文涉及视觉和语言模型的结合，但其核心在于如何利用这些模型进行动作识别和视频字幕生成等应用任务。因此，它属于LLM应用的范畴。` `视频分析` `人机交互`

> SKI Models: Skeleton Induced Vision-Language Embeddings for Understanding Activities of Daily Living

# 摘要

> # 摘要
CLIP等视觉-语言模型的问世，推动了基础视频模型的发展，使其能够泛化到未见过的视频和人类动作。然而，这些模型通常基于网络视频训练，难以应对日常生活活动（ADL）视频中的挑战。现有研究通过融合3D骨架和RGB视频，解决了ADL特有的难题，如相似外观、细微动作和多视角问题。但这些方法未与语言结合，限制了其泛化到新动作类的能力。本文提出的SKI模型，将3D骨架融入视觉-语言嵌入空间，通过SkeletonCLIP骨架-语言模型，将骨架信息注入视觉语言模型（VLMs）和大型视觉语言模型（LVLMs）中。值得一提的是，SKI模型在推理时无需骨架数据，提升了其在现实应用中的鲁棒性。该模型在三个ADL数据集上的零样本动作识别和视频字幕生成任务中表现优异。

> The introduction of vision-language models like CLIP has enabled the development of foundational video models capable of generalizing to unseen videos and human actions. However, these models are typically trained on web videos, which often fail to capture the challenges present in Activities of Daily Living (ADL) videos. Existing works address ADL-specific challenges, such as similar appearances, subtle motion patterns, and multiple viewpoints, by combining 3D skeletons and RGB videos. However, these approaches are not integrated with language, limiting their ability to generalize to unseen action classes. In this paper, we introduce SKI models, which integrate 3D skeletons into the vision-language embedding space. SKI models leverage a skeleton-language model, SkeletonCLIP, to infuse skeleton information into Vision Language Models (VLMs) and Large Vision Language Models (LVLMs) through collaborative training. Notably, SKI models do not require skeleton data during inference, enhancing their robustness for real-world applications. The effectiveness of SKI models is validated on three popular ADL datasets for zero-shot action recognition and video caption generation tasks.

[Arxiv](https://arxiv.org/abs/2502.03459)