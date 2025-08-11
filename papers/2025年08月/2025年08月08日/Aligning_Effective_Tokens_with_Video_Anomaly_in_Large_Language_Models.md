# 大型语言模型中有效标记与视频异常的对齐

发布时间：2025年08月08日

`LLM应用` `视频分析` `异常检测`

> Aligning Effective Tokens with Video Anomaly in Large Language Models

# 摘要

> 视频异常事件理解是跨领域应用中一项重要且具挑战性的任务。当前多模态大型语言模型（MLLMs）虽能分析常规视频，但在处理异常事件时表现欠佳，主要源于异常事件的空间-时间稀疏性导致冗余信息干扰。为解决这一难题，我们提出了VA-GPT——一款结合视觉语言模型（VLMs）与大型语言模型（LLMs）优势的创新MLLM，专注于视频异常事件的总结与定位。通过空间有效令牌选择（SETS）和时间有效令牌生成（TETG）两大模块，VA-GPT实现了视觉编码器与语言模型的有效对齐，精准捕捉分析异常事件的时空特征，显著提升了响应精度。此外，我们构建了专门用于微调视频异常感知MLLMs的指令数据集，并基于XD-Violence数据集打造跨领域评估基准。实验结果表明，VA-GPT在各项基准测试中均超越现有最优方法。


> Understanding abnormal events in videos is a vital and challenging task that has garnered significant attention in a wide range of applications. Although current video understanding Multi-modal Large Language Models (MLLMs) are capable of analyzing general videos, they often struggle to handle anomalies due to the spatial and temporal sparsity of abnormal events, where the redundant information always leads to suboptimal outcomes. To address these challenges, exploiting the representation and generalization capabilities of Vison Language Models (VLMs) and Large Language Models (LLMs), we propose VA-GPT, a novel MLLM designed for summarizing and localizing abnormal events in various videos. Our approach efficiently aligns effective tokens between visual encoders and LLMs through two key proposed modules: Spatial Effective Token Selection (SETS) and Temporal Effective Token Generation (TETG). These modules enable our model to effectively capture and analyze both spatial and temporal information associated with abnormal events, resulting in more accurate responses and interactions. Furthermore, we construct an instruction-following dataset specifically for fine-tuning video-anomaly-aware MLLMs, and introduce a cross-domain evaluation benchmark based on XD-Violence dataset. Our proposed method outperforms existing state-of-the-art methods on various benchmarks.

[Arxiv](https://arxiv.org/abs/2508.06350)