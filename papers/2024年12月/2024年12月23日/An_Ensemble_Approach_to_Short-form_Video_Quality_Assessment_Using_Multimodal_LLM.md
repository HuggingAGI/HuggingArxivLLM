# 一种借助多模态 LLM 来评估短视频质量的集成式方法

发布时间：2024年12月23日

`LLM应用` `质量评估`

> An Ensemble Approach to Short-form Video Quality Assessment Using Multimodal LLM

# 摘要

> 短形式视频兴起，其内容丰富、编辑风格多样、人工制品各异，这给基于学习的盲视频质量评估（BVQA）模型带来严峻挑战。以出色泛化能力著称的多模态大型语言模型（MLLMs）带来了颇具前景的解决方案。本文着重于有效利用预训练的 MLLM 来评估短形式视频质量，探讨预处理和响应变异性的影响，以及 MLLM 与 BVQA 模型结合的思路。我们先是研究了帧预处理和采样技术对 MLLM 性能的影响。接着，引入了一种轻量级基于学习的集成方法，能自适应整合 MLLM 和先进的 BVQA 模型的预测。我们的成果显示，所提出的集成方法泛化性能优越。此外，对内容感知集成权重的分析表明，一些视频特征未被现有 BVQA 模型充分体现，揭示了进一步优化 BVQA 模型的潜在方向。

> The rise of short-form videos, characterized by diverse content, editing styles, and artifacts, poses substantial challenges for learning-based blind video quality assessment (BVQA) models. Multimodal large language models (MLLMs), renowned for their superior generalization capabilities, present a promising solution. This paper focuses on effectively leveraging a pretrained MLLM for short-form video quality assessment, regarding the impacts of pre-processing and response variability, and insights on combining the MLLM with BVQA models. We first investigated how frame pre-processing and sampling techniques influence the MLLM's performance. Then, we introduced a lightweight learning-based ensemble method that adaptively integrates predictions from the MLLM and state-of-the-art BVQA models. Our results demonstrated superior generalization performance with the proposed ensemble approach. Furthermore, the analysis of content-aware ensemble weights highlighted that some video characteristics are not fully represented by existing BVQA models, revealing potential directions to improve BVQA models further.

[Arxiv](https://arxiv.org/abs/2412.18060)