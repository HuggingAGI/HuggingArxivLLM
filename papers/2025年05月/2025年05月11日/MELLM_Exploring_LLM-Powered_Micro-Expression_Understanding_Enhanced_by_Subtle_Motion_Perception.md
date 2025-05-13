# MELLM：探索基于LLM的微表情理解，通过微妙动作感知增强

发布时间：2025年05月11日

`LLM应用` `心理学` `计算机视觉`

> MELLM: Exploring LLM-Powered Micro-Expression Understanding Enhanced by Subtle Motion Perception

# 摘要

> 微表情（MEs）是关键的心理反应，具有重要的情感计算潜力。然而，现有的自动微表情识别（MER）研究主要集中在离散情绪分类上，忽视了对细微动态动作和潜在情感线索的深入分析。多模态大语言模型（MLLMs）的快速发展，以其强大的多模态理解和语言生成能力，为微表情识别提供了新的可能性。MLLMs在多种视觉-语言任务中表现出色，这表明它们具备全面理解微表情的潜力，包括精细的动作模式和潜在的情感语义。然而，由于微表情的细微强度和短暂持续时间，现有的MLLMs并未设计用于捕捉如此精细的帧级别面部动态。在本文中，我们提出了一种新型的微表情大语言模型（MELLM），它结合了微妙面部运动感知策略和MLLMs强大的推理能力，这是首次探索MLLMs在微表情分析领域的应用。具体而言，我们通过融合起始-顶点光流动态与对应的灰度起始帧，构建了一个可解释的运动增强彩色图作为模型输入，以明确引导MELLM关注运动敏感区域。此外，我们采用了专门的微调策略，以进一步提升模型对微表情的视觉感知能力。此外，我们基于面部动作编码系统（FACS）注释和情感标签构建了一个指令-描述数据集，用于训练我们的MELLM。在多个基准数据集上的全面评估表明，我们的模型在微表情理解（MEU）方面表现出色，具有优越的鲁棒性和泛化能力。代码可在https://github.com/zyzhangUstc/MELLM获取。

> Micro-expressions (MEs) are crucial psychological responses with significant potential for affective computing. However, current automatic micro-expression recognition (MER) research primarily focuses on discrete emotion classification, neglecting a convincing analysis of the subtle dynamic movements and inherent emotional cues. The rapid progress in multimodal large language models (MLLMs), known for their strong multimodal comprehension and language generation abilities, offers new possibilities. MLLMs have shown success in various vision-language tasks, indicating their potential to understand MEs comprehensively, including both fine-grained motion patterns and underlying emotional semantics. Nevertheless, challenges remain due to the subtle intensity and short duration of MEs, as existing MLLMs are not designed to capture such delicate frame-level facial dynamics. In this paper, we propose a novel Micro-Expression Large Language Model (MELLM), which incorporates a subtle facial motion perception strategy with the strong inference capabilities of MLLMs, representing the first exploration of MLLMs in the domain of ME analysis. Specifically, to explicitly guide the MLLM toward motion-sensitive regions, we construct an interpretable motion-enhanced color map by fusing onset-apex optical flow dynamics with the corresponding grayscale onset frame as the model input. Additionally, specialized fine-tuning strategies are incorporated to further enhance the model's visual perception of MEs. Furthermore, we construct an instruction-description dataset based on Facial Action Coding System (FACS) annotations and emotion labels to train our MELLM. Comprehensive evaluations across multiple benchmark datasets demonstrate that our model exhibits superior robustness and generalization capabilities in ME understanding (MEU). Code is available at https://github.com/zyzhangUstc/MELLM.

[Arxiv](https://arxiv.org/abs/2505.07007)