# Long-VITA：将大型多模态模型扩展至100万tokens，同时保持领先短上下文准确性

发布时间：2025年02月07日

`LLM应用` `视觉-语言模型` `多模态`

> Long-VITA: Scaling Large Multi-modal Models to 1 Million Tokens with Leading Short-Context Accuray

# 摘要

> 构建长上下文能力对于大型视觉-语言模型在视频理解、高分辨率图像理解、多模态智能体及推理方面具有重要意义。我们推出Long-VITA——一款简单而强大的长上下文多模态模型，专为处理长上下文视觉-语言任务而设计。它不仅能够同时处理和分析图像、视频和文本等多模态信息，处理规模可达4K帧或100万级文本分词，更在短上下文多模态任务中表现出色。我们提出了一种创新的多模态训练方案，从大型语言模型出发，依次完成视觉-语言对齐、通用知识学习，以及两个阶段的长序列微调。为实现高效推理，我们引入上下文并行分布式推理和带掩码的逻辑回归语言建模头，使Long-VITA能够处理无限长度的图像和文本输入。在数据方面，Long-VITA仅基于公开数据集的1700万个样本构建，相较于使用内部数据的近期先进模型，在多个多模态基准测试中展现出卓越的性能。Long-VITA完全可复现，支持NPU和GPU平台进行训练和测试。我们期待Long-VITA能够作为极具竞争力的基线模型，为开源社区在推进长上下文多模态理解方面提供有价值的参考和启示。

> Establishing the long-context capability of large vision-language models is crucial for video understanding, high-resolution image understanding, multi-modal agents and reasoning. We introduce Long-VITA, a simple yet effective large multi-modal model for long-context visual-language understanding tasks. It is adept at concurrently processing and analyzing modalities of image, video, and text over 4K frames or 1M tokens while delivering advanced performances on short-context multi-modal tasks. We propose an effective multi-modal training schema that starts with large language models and proceeds through vision-language alignment, general knowledge learning, and two sequential stages of long-sequence fine-tuning. We further implement context-parallelism distributed inference and logits-masked language modeling head to scale Long-VITA to infinitely long inputs of images and texts during model inference. Regarding training data, Long-VITA is built on a mix of $17$M samples from public datasets only and demonstrates the state-of-the-art performance on various multi-modal benchmarks, compared against recent cutting-edge models with internal data. Long-VITA is fully reproducible and supports both NPU and GPU platforms for training and testing. We hope Long-VITA can serve as a competitive baseline and offer valuable insights for the open-source community in advancing long-context multi-modal understanding.

[Arxiv](https://arxiv.org/abs/2502.05177)