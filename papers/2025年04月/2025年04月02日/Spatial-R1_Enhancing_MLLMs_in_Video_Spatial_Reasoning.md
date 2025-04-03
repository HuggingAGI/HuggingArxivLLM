# Space-R1：增强视频空间推理中的多模态大语言模型能力

发布时间：2025年04月02日

`LLM应用` `视频分析` `计算机视觉`

> Spatial-R1: Enhancing MLLMs in Video Spatial Reasoning

# 摘要

> 提升多模态大型语言模型（MLLMs）在视频理解中的空间推理能力至关重要且充满挑战。我们提出了Spatial-R1，一种针对性方法，包含两个关键贡献：整理SR，一个从ScanNet创建的新视频空间推理数据集，涵盖七种任务类型，自动生成QA对；以及应用任务特定组相对策略优化（GRPO）进行微调。通过在SR上使用GRPO训练Qwen2.5-VL-7B-Instruct模型，Spatial-R1在VSI-Bench基准上显著提升了性能，相比基线提升了7.4%，超越了当前强大的模型。这项工作验证了专门数据整理和优化技术在提升视频MLLMs复杂空间推理方面的有效性。

> Enhancing the spatial reasoning capabilities of Multi-modal Large Language Models (MLLMs) for video understanding is crucial yet challenging. We present Spatial-R1, a targeted approach involving two key contributions: the curation of SR, a new video spatial reasoning dataset from ScanNet with automatically generated QA pairs across seven task types, and the application of Task-Specific Group Relative Policy Optimization (GRPO) for fine-tuning. By training the Qwen2.5-VL-7B-Instruct model on SR using GRPO, Spatial-R1 significantly advances performance on the VSI-Bench benchmark, achieving a 7.4\% gain over the baseline and outperforming strong contemporary models. This work validates the effectiveness of specialized data curation and optimization techniques for improving complex spatial reasoning in video MLLMs.

[Arxiv](https://arxiv.org/abs/2504.01805)