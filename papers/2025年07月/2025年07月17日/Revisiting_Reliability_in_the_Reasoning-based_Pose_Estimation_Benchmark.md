# 重新审视推理式姿态估计基准中的可靠性

发布时间：2025年07月17日

`其他` `计算机视觉` `人工智能`

> Revisiting Reliability in the Reasoning-based Pose Estimation Benchmark

# 摘要

> 基于推理的姿态估计（RPE）基准已成为评估感知姿态的多模态大语言模型（MLLMs）的通用标准。然而，我们发现该基准在可重复性和质量上存在关键问题，影响了公平一致的定量评估。首先，RPE基准使用的图像索引与原3DPW数据集不同，这迫使研究人员进行繁琐且易出错的手动匹配来获取准确的地面真实（GT）标注（如MPJPE、PA-MPJPE）。此外，该基准还存在多重固有缺陷：图像冗余严重、场景分布不均、姿势过于简单以及文本描述模糊，这些问题共同影响了评估的可靠性。为解决这些问题，我们通过细致的视觉匹配优化了GT标注，并将其作为开源资源公开发布，以促进更一致的定量评估并推动人体姿态感知推理技术的进一步发展。

> The reasoning-based pose estimation (RPE) benchmark has emerged as a widely adopted evaluation standard for pose-aware multimodal large language models (MLLMs). Despite its significance, we identified critical reproducibility and benchmark-quality issues that hinder fair and consistent quantitative evaluations. Most notably, the benchmark utilizes different image indices from those of the original 3DPW dataset, forcing researchers into tedious and error-prone manual matching processes to obtain accurate ground-truth (GT) annotations for quantitative metrics (\eg, MPJPE, PA-MPJPE). Furthermore, our analysis reveals several inherent benchmark-quality limitations, including significant image redundancy, scenario imbalance, overly simplistic poses, and ambiguous textual descriptions, collectively undermining reliable evaluations across diverse scenarios. To alleviate manual effort and enhance reproducibility, we carefully refined the GT annotations through meticulous visual matching and publicly release these refined annotations as an open-source resource, thereby promoting consistent quantitative evaluations and facilitating future advancements in human pose-aware multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2507.13314)