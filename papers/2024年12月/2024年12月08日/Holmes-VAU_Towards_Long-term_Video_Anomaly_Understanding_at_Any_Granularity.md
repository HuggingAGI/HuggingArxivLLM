# Holmes-VAU：致力于实现任何粒度下的长期视频异常理解

发布时间：2024年12月08日

`LLM应用` `异常检测`

> Holmes-VAU: Towards Long-term Video Anomaly Understanding at Any Granularity

# 摘要

> 怎样才能让模型理解在不同时间尺度和情境中出现的视频异常呢？传统的视频异常理解（VAU）方法着重于帧级别的异常预测，常常忽视了复杂多样的现实世界异常的可解释性。近期的多模态方法虽利用了视觉和文本数据，却缺少能捕捉短期和长期异常的分层标注。为应对此挑战，我们推出了 HIVAU-70k，这是一个用于任何粒度分层视频异常理解的大规模基准。我们研发了一个半自动标注引擎，将手动视频分割与利用大型语言模型（LLMs）的递归自由文本标注相结合，高效地拓展了高质量标注。由此产生了超过 70,000 个在剪辑级、事件级和视频级段组织的多粒度标注。为在长视频中实现有效的异常检测，我们提出了异常聚焦的时间采样器（ATS）。ATS 把异常评分器与密度感知采样器相融合，依据异常分数自适应地选取帧，保证多模态 LLM 聚焦于异常丰富的区域，这极大地提升了效率和准确性。大量实验表明，我们的分层指令数据显著增强了异常理解能力。集成的 ATS 和视觉语言模型在处理长视频时优于传统方法。我们的基准和模型可在 https://github.com/pipixin321/HolmesVAU 公开获取。

> How can we enable models to comprehend video anomalies occurring over varying temporal scales and contexts? Traditional Video Anomaly Understanding (VAU) methods focus on frame-level anomaly prediction, often missing the interpretability of complex and diverse real-world anomalies. Recent multimodal approaches leverage visual and textual data but lack hierarchical annotations that capture both short-term and long-term anomalies. To address this challenge, we introduce HIVAU-70k, a large-scale benchmark for hierarchical video anomaly understanding across any granularity. We develop a semi-automated annotation engine that efficiently scales high-quality annotations by combining manual video segmentation with recursive free-text annotation using large language models (LLMs). This results in over 70,000 multi-granular annotations organized at clip-level, event-level, and video-level segments. For efficient anomaly detection in long videos, we propose the Anomaly-focused Temporal Sampler (ATS). ATS integrates an anomaly scorer with a density-aware sampler to adaptively select frames based on anomaly scores, ensuring that the multimodal LLM concentrates on anomaly-rich regions, which significantly enhances both efficiency and accuracy. Extensive experiments demonstrate that our hierarchical instruction data markedly improves anomaly comprehension. The integrated ATS and visual-language model outperform traditional methods in processing long videos. Our benchmark and model are publicly available at https://github.com/pipixin321/HolmesVAU.

[Arxiv](https://arxiv.org/abs/2412.06171)