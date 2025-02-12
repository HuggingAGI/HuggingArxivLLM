# LongReD：通过恢复蒸馏技术缓解长上下文大型语言模型的短文本性能退化问题

发布时间：2025年02月11日

`LLM理论`

> LongReD: Mitigating Short-Text Degradation of Long-Context Large Language Models via Restoration Distillation

# 摘要

> 大型语言模型（LLMs）通过扩展位置编码和轻量级持续预训练获得了更长的上下文窗口。然而，这一改进却导致了短文本任务性能的下降，而这一现象的原因尚未被充分研究。本研究识别出两个主要原因：隐藏状态和注意力分数中的分布漂移，以及持续预训练过程中的灾难性遗忘。为了解决这些问题，我们提出了Long Context Pre-training with Restoration Distillation（LongReD），这是一种通过最小化扩展模型与原模型之间的分布差异来缓解短文本性能下降的新方法。LongReD不仅在长文本上进行训练，还从原模型中蒸馏短文本的选定层隐藏状态。此外，LongReD还引入了一种短到长的蒸馏方法，通过利用跳过的位置索引，使短文本和长文本的输出分布保持一致。实验结果表明，LongReD在保持模型短文本性能的同时，处理长文本的能力与基线方法相比甚至更优。

> Large language models (LLMs) have gained extended context windows through scaling positional encodings and lightweight continual pre-training. However, this often leads to degraded performance on short-text tasks, while the reasons for this degradation remain insufficiently explored. In this work, we identify two primary factors contributing to this issue: distribution drift in hidden states and attention scores, and catastrophic forgetting during continual pre-training. To address these challenges, we propose Long Context Pre-training with Restoration Distillation (LongReD), a novel approach designed to mitigate short-text performance degradation through minimizing the distribution discrepancy between the extended and original models. Besides training on long texts, LongReD distills the hidden state of selected layers from the original model on short texts. Additionally, LongReD also introduces a short-to-long distillation, aligning the output distribution on short texts with that on long texts by leveraging skipped positional indices. Experiments on common text benchmarks demonstrate that LongReD effectively preserves the model's short-text performance while maintaining comparable or even better capacity to handle long texts than baselines.

[Arxiv](https://arxiv.org/abs/2502.07365)