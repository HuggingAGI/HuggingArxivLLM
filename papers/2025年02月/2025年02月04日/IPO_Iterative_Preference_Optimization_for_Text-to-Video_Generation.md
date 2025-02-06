# IPO: 文本到视频生成的迭代偏好优化

发布时间：2025年02月04日

`LLM应用

**理由**：该论文主要讨论了如何通过迭代偏好优化（IPO）策略，将视频基础模型与人类偏好对齐，从而提升视频生成质量。虽然涉及视频生成，但其核心方法依赖于多模态大语言模型（LLM）的整合，用于自动分配偏好标签和优化生成效果。因此，该研究属于LLM在视频生成领域的应用，符合“LLM应用”分类。` `视频生成` `人工智能`

> IPO: Iterative Preference Optimization for Text-to-Video Generation

# 摘要

> # 摘要
视频基础模型在网络升级和模型规模扩大的推动下取得了显著进展，但由于生成质量不尽如人意，仍难以满足实际应用需求。为此，本文提出从后训练的角度出发，将视频基础模型与人类偏好对齐。我们引入了一种迭代偏好优化（IPO）策略，通过整合人类反馈来提升视频生成质量。具体而言，IPO利用评判模型对视频生成进行成对排序（如直接偏好优化）或点对点评分（如卡尼曼-特沃斯基优化），并基于偏好反馈信号优化视频基础模型，从而在主题一致性、运动平滑度和美学质量等方面显著提升生成效果。此外，IPO将评判模型与多模态大语言模型结合，使其能够自动分配偏好标签，无需重新训练或标注。通过这种方式，IPO能够高效地进行多轮迭代优化，避免了繁琐的手动标注。实验表明，IPO不仅有效提升了预训练模型的视频生成质量，还使仅2B参数的模型超越了5B参数的模型。同时，IPO在VBench基准测试中刷新了最新性能记录。我们将开源代码、模型和数据集，以推动未来研究和应用的发展。

> Video foundation models have achieved significant advancement with the help of network upgrade as well as model scale-up. However, they are still hard to meet requirements of applications due to unsatisfied generation quality. To solve this problem, we propose to align video foundation models with human preferences from the perspective of post-training in this paper. Consequently, we introduce an Iterative Preference Optimization strategy to enhance generated video quality by incorporating human feedback. Specifically, IPO exploits a critic model to justify video generations for pairwise ranking as in Direct Preference Optimization or point-wise scoring as in Kahneman-Tversky Optimization. Given this, IPO optimizes video foundation models with guidance of signals from preference feedback, which helps improve generated video quality in subject consistency, motion smoothness and aesthetic quality, etc. In addition, IPO incorporates the critic model with the multi-modality large language model, which enables it to automatically assign preference labels without need of retraining or relabeling. In this way, IPO can efficiently perform multi-round preference optimization in an iterative manner, without the need of tediously manual labeling. Comprehensive experiments demonstrate that the proposed IPO can effectively improve the video generation quality of a pretrained model and help a model with only 2B parameters surpass the one with 5B parameters. Besides, IPO achieves new state-of-the-art performance on VBench benchmark. We will release our source codes, models as well as dataset to advance future research and applications.

[Arxiv](https://arxiv.org/abs/2502.02088)