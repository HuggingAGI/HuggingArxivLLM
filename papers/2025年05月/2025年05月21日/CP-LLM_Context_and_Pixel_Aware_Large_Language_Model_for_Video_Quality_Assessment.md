# CP-LLM：结合上下文与像素感知的大型语言模型，专为视频质量评估而设计

发布时间：2025年05月21日

`LLM应用` `视频技术` `视频质量评估`

> CP-LLM: Context and Pixel Aware Large Language Model for Video Quality Assessment

# 摘要

> # 摘要  
视频质量评估（VQA）是一项具有广泛应用前景的极具挑战性的研究课题。有效的视频质量评估不仅需要对像素级失真保持敏感，还需要全面理解视频上下文，以准确评估失真对视觉感知的影响。传统基于手工设计和学习的VQA模型主要关注像素级失真，缺乏上下文理解能力，而近期基于LLM的模型则在对小失真的敏感性方面存在问题，或者将质量评分和描述视为独立任务处理。为了解决这些不足，我们引入了CP-LLM：一种感知上下文与像素的大型语言模型。CP-LLM是一种新型的多模态LLM架构，配备双视觉编码器，分别用于独立分析视频质量在高层次（视频上下文）和低层次（像素失真）粒度下的表现，随后语言解码器对这些方面的相互作用进行推理。这一设计使CP-LLM能够同时生成稳健的质量评分和可解释的质量描述，对像素失真（例如压缩伪影）的敏感性也得到了显著提升。该模型通过一个多任务训练管道进行优化，旨在提升评分预测、描述生成和成对比较的能力。实验结果表明，CP-LLM在 established VQA基准测试中实现了跨数据集的最先进性能，并在像素失真方面表现出色，证实了其在现实场景中进行全面且实用的视频质量评估的有效性。


> Video quality assessment (VQA) is a challenging research topic with broad applications. Effective VQA necessitates sensitivity to pixel-level distortions and a comprehensive understanding of video context to accurately determine the perceptual impact of distortions. Traditional hand-crafted and learning-based VQA models mainly focus on pixel-level distortions and lack contextual understanding, while recent LLM-based models struggle with sensitivity to small distortions or handle quality scoring and description as separate tasks. To address these shortcomings, we introduce CP-LLM: a Context and Pixel aware Large Language Model. CP-LLM is a novel multimodal LLM architecture featuring dual vision encoders designed to independently analyze perceptual quality at both high-level (video context) and low-level (pixel distortion) granularity, along with a language decoder subsequently reasons about the interplay between these aspects. This design enables CP-LLM to simultaneously produce robust quality scores and interpretable quality descriptions, with enhanced sensitivity to pixel distortions (e.g. compression artifacts). The model is trained via a multi-task pipeline optimizing for score prediction, description generation, and pairwise comparisons. Experiment results demonstrate that CP-LLM achieves state-of-the-art cross-dataset performance on established VQA benchmarks and superior robustness to pixel distortions, confirming its efficacy for comprehensive and practical video quality assessment in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2505.16025)