# CPath-Omni：一个用于计算病理学中切片和全切片图像分析的统一多模态基础模型

发布时间：2024年12月16日

`LLM应用` `病理学` `医学图像分析`

> CPath-Omni: A Unified Multimodal Foundation Model for Patch and Whole Slide Image Analysis in Computational Pathology

# 摘要

> 大型多模态模型（LMMs）的出现为病理学带来了显著进步。此前的研究主要侧重于分别训练切片级和全切片图像（WSI）级模型，这限制了跨切片和 WSI 所学知识的整合，也导致了模型的冗余。在本研究中，我们推出了 CPath-Omni，这是首个拥有 150 亿参数的 LMM，旨在统一切片和 WSI 级别的图像分析，整合了包括分类、视觉问答、字幕生成和视觉引用提示等多种任务。大量实验表明，CPath-Omni 在 42 个数据集中的 39 个上的七项不同任务中达到了最先进（SOTA）水平，超越或媲美为单个任务训练的特定任务模型。此外，我们为 CPath-Omni 开发了专门的基于病理学 CLIP 的视觉处理器 CPath-CLIP，这是首次整合不同视觉模型，并将大型语言模型作为文本编码器，构建出更强大的 CLIP 模型，在九个零样本和四个少样本数据集中达到了 SOTA 性能。我们的研究成果凸显了 CPath-Omni 统一各类病理学任务的能力，展现了其在精简和推动病理学基础模型领域方面的潜力。

> The emergence of large multimodal models (LMMs) has brought significant advancements to pathology. Previous research has primarily focused on separately training patch-level and whole-slide image (WSI)-level models, limiting the integration of learned knowledge across patches and WSIs, and resulting in redundant models. In this work, we introduce CPath-Omni, the first 15-billion-parameter LMM designed to unify both patch and WSI level image analysis, consolidating a variety of tasks at both levels, including classification, visual question answering, captioning, and visual referring prompting. Extensive experiments demonstrate that CPath-Omni achieves state-of-the-art (SOTA) performance across seven diverse tasks on 39 out of 42 datasets, outperforming or matching task-specific models trained for individual tasks. Additionally, we develop a specialized pathology CLIP-based visual processor for CPath-Omni, CPath-CLIP, which, for the first time, integrates different vision models and incorporates a large language model as a text encoder to build a more powerful CLIP model, which achieves SOTA performance on nine zero-shot and four few-shot datasets. Our findings highlight CPath-Omni's ability to unify diverse pathology tasks, demonstrating its potential to streamline and advance the field of foundation model in pathology.

[Arxiv](https://arxiv.org/abs/2412.12077)