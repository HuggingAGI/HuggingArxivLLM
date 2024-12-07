# WSI-LLaVA：一种用于全切片图像的多模态大型语言模型

发布时间：2024年12月02日

`LLM应用` `病理学`

> WSI-LLaVA: A Multimodal Large Language Model for Whole Slide Image

# 摘要

> 近期在计算病理学领域取得的进展催生了补丁级别的多模态大型语言模型（MLLMs），然而这些模型存在局限性，无法全面分析全切片图像（WSIs），还容易忽略病理学家诊断所依赖的关键形态特征。为应对这些挑战，我们率先引入 WSI-Bench，这是一个大规模的具备形态感知能力的基准，涵盖了来自 30 种癌症类型的 9850 个 WSIs 的 18 万个 VQA 对，旨在评估 MLLMs 对精准诊断所需形态特征的理解程度。基于此基准，我们推出 WSI-LLaVA，这是一个用于千兆像素 WSI 理解的新型框架，采用了三阶段训练方式：WSI - 文本对齐、特征空间对齐以及特定任务指令调整。为更有效地评估病理情境下的模型性能，我们开发了两个专门的 WSI 指标：WSI - 精度和 WSI - 相关性。实验结果显示，WSI - LLaVA 在所有能力维度上均超越现有模型，在形态分析方面有显著提升，清晰地建立起了形态理解与诊断准确性之间的关联。

> Recent advancements in computational pathology have produced patch-level Multi-modal Large Language Models (MLLMs), but these models are limited by their inability to analyze whole slide images (WSIs) comprehensively and their tendency to bypass crucial morphological features that pathologists rely on for diagnosis. To address these challenges, we first introduce WSI-Bench, a large-scale morphology-aware benchmark containing 180k VQA pairs from 9,850 WSIs across 30 cancer types, designed to evaluate MLLMs' understanding of morphological characteristics crucial for accurate diagnosis. Building upon this benchmark, we present WSI-LLaVA, a novel framework for gigapixel WSI understanding that employs a three-stage training approach: WSI-text alignment, feature space alignment, and task-specific instruction tuning. To better assess model performance in pathological contexts, we develop two specialized WSI metrics: WSI-Precision and WSI-Relevance. Experimental results demonstrate that WSI-LLaVA outperforms existing models across all capability dimensions, with a significant improvement in morphological analysis, establishing a clear correlation between morphological understanding and diagnostic accuracy.

[Arxiv](https://arxiv.org/abs/2412.02141)