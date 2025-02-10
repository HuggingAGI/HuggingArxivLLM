# PerPO：感知偏好优化借助判别奖励实现

发布时间：2025年02月05日

`LLM应用

LLM应用` `多模态` `计算机视觉`

> PerPO: Perceptual Preference Optimization via Discriminative Rewarding

# 摘要

> 本文提出了一种感知偏好优化方法（PerPO），旨在解决生成式预训练多模态大语言模型（MLLMs）中的视觉辨别挑战。PerPO通过辨别式奖励机制收集多样化的负样本，并利用列表式偏好优化对这些样本进行排序。通过将奖励作为排序的量化指标，PerPO成功实现了生成式偏好优化与辨别式经验风险最小化的结合。该方法显著提升了MLLMs的视觉辨别能力，同时保持了其生成优势，缓解了图像无条件奖励欺骗问题，并确保了视觉任务的一致性表现。这项研究为实现更感知对齐且功能多样的MLLMs迈出了重要一步。我们希望PerPO能够激发社区重新思考MLLM对齐策略。

> This paper presents Perceptual Preference Optimization (PerPO), a perception alignment method aimed at addressing the visual discrimination challenges in generative pre-trained multimodal large language models (MLLMs). To align MLLMs with human visual perception process, PerPO employs discriminative rewarding to gather diverse negative samples, followed by listwise preference optimization to rank them.By utilizing the reward as a quantitative margin for ranking, our method effectively bridges generative preference optimization and discriminative empirical risk minimization. PerPO significantly enhances MLLMs' visual discrimination capabilities while maintaining their generative strengths, mitigates image-unconditional reward hacking, and ensures consistent performance across visual tasks. This work marks a crucial step towards more perceptually aligned and versatile MLLMs. We also hope that PerPO will encourage the community to rethink MLLM alignment strategies.

[Arxiv](https://arxiv.org/abs/2502.04371)