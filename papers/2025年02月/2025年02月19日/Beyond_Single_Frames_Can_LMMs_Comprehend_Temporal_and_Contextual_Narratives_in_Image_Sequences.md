# 超越单帧图像：大型模型能否理解图像序列中的时空叙事？

发布时间：2025年02月19日

`LLM应用

理由：这篇论文主要探讨了大型多模态模型在视觉-语言任务中的应用，特别是针对图像序列的理解和推理能力。虽然涉及多模态模型，但其核心是评估和应用这些模型，因此归类为LLM应用。`

> Beyond Single Frames: Can LMMs Comprehend Temporal and Contextual Narratives in Image Sequences?

# 摘要

> 大型多模态模型（LMMs）在视觉-语言任务中表现卓越，但现有研究多聚焦于单张图像的理解，对图像序列的分析仍属空白。为此，我们推出StripCipher，一个全面的基准测试，专为评估LMMs对序列图像的理解和推理能力而设计。StripCipher包含人工标注的数据集及三个挑战性子任务：视觉叙事理解、上下文帧预测和时间叙事重新排序。我们对包括GPT-4o和Qwen2.5VL在内的16个先进LMMs进行了评测，发现它们的表现与人类能力差距显著，尤其在需要重新排序被打乱序列图像的任务中。例如，GPT-4o在重新排序任务中的准确率仅为23.93%，比人类低56.07%。深入的定量分析揭示了影响LLMs序列理解表现的因素，如图像输入格式等，凸显了LMMs发展中仍需攻克的核心难题。

> Large Multimodal Models (LMMs) have achieved remarkable success across various visual-language tasks. However, existing benchmarks predominantly focus on single-image understanding, leaving the analysis of image sequences largely unexplored. To address this limitation, we introduce StripCipher, a comprehensive benchmark designed to evaluate capabilities of LMMs to comprehend and reason over sequential images. StripCipher comprises a human-annotated dataset and three challenging subtasks: visual narrative comprehension, contextual frame prediction, and temporal narrative reordering. Our evaluation of $16$ state-of-the-art LMMs, including GPT-4o and Qwen2.5VL, reveals a significant performance gap compared to human capabilities, particularly in tasks that require reordering shuffled sequential images. For instance, GPT-4o achieves only 23.93% accuracy in the reordering subtask, which is 56.07% lower than human performance. Further quantitative analysis discuss several factors, such as input format of images, affecting the performance of LLMs in sequential understanding, underscoring the fundamental challenges that remain in the development of LMMs.

[Arxiv](https://arxiv.org/abs/2502.13925)