# SynPO：协同描述性与偏好优化实现视频详细字幕生成

发布时间：2025年06月01日

`LLM应用` `视频处理` `人工智能`

> SynPO: Synergizing Descriptiveness and Preference Optimization for Video Detailed Captioning

# 摘要

> 细粒度视频描述生成旨在生成详细且时间连贯的视频内容描述。然而，现有方法在捕捉视频的细微动态和丰富的详细信息方面存在困难。本文中，我们利用偏好学习来提升视觉语言模型在细粒度视频描述生成中的性能，同时缓解直接偏好优化（DPO）固有的几个限制。首先，我们提出了一种利用视觉语言模型固有特性并结合大型语言模型部分辅助的偏好对构建管道，实现了成本与数据质量之间的最优平衡。其次，我们提出了协同偏好优化（SynPO），这是一种相较于DPO及其变体具有显著优势的新优化方法。SynPO能够防止负面偏好主导优化过程，显式保留模型的语言能力以避免优化目标偏离，并通过消除对参考模型的需求来提高训练效率。我们在视频描述生成基准（如VDC、VDD、VATEX）以及一系列成熟的NLP任务（包括通用语言理解和偏好评估）上，使用多种预训练模型对SynPO进行了全面评估。结果表明，SynPO在训练效率上比DPO变体提高了20%，并且在性能上持续优于它们。代码可在https://github.com/longmalongma/SynPO获取。

> Fine-grained video captioning aims to generate detailed, temporally coherent descriptions of video content. However, existing methods struggle to capture subtle video dynamics and rich detailed information. In this paper, we leverage preference learning to enhance the performance of vision-language models in fine-grained video captioning, while mitigating several limitations inherent to direct preference optimization (DPO). First, we propose a pipeline for constructing preference pairs that leverages the intrinsic properties of VLMs along with partial assistance from large language models, achieving an optimal balance between cost and data quality. Second, we propose Synergistic Preference Optimization (SynPO), a novel optimization method offering significant advantages over DPO and its variants. SynPO prevents negative preferences from dominating the optimization, explicitly preserves the model's language capability to avoid deviation of the optimization objective, and improves training efficiency by eliminating the need for the reference model. We extensively evaluate SynPO not only on video captioning benchmarks (e.g., VDC, VDD, VATEX) but also across well-established NLP tasks, including general language understanding and preference evaluation, using diverse pretrained models. Results demonstrate that SynPO consistently outperforms DPO variants while achieving 20\% improvement in training efficiency. Code is available at https://github.com/longmalongma/SynPO

[Arxiv](https://arxiv.org/abs/2506.00835)