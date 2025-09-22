# Mamba-2 音频描述生成：设计空间的探索与分析

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> Mamba-2 audio captioning: design space exploration and analysis

# 摘要

> 我们提出了一种基于Mamba-2大型语言模型主干的音频描述模型，Mamba-2是最先进的（SOTA）状态空间模型（SSM）。我们系统探索了设计空间：LLM规模、LoRA秩，以及利用Mamba-2在序列长度上的线性时间复杂度的连接器设计。在各项基准测试中，我们的模型虽然参数更少，但与在相同数据集上训练的更大语言模型相比，仍展现出优异的描述性能。我们首次深入分析了LLM参数数量、音频编码器微调策略、音频特征多样性以及不同的特征缩减或扩展技术对性能的影响。

> We present an audio captioning model built on the Mamba-2 large language model backbone, which is a state-of-the-art (SOTA) state-space model (SSM). We systematically explore the design space: LLM sizes, LoRA ranks, and connector designs leveraging Mamba-2's linear-time complexity with respect to sequence length. Across benchmarks, our models achieve strong captioning performance compared with larger language models trained on the same dataset, despite using fewer parameters. For the first time, we conduct an in-depth analysis of how the number of LLM parameters, audio encoder fine-tuning strategies, audio feature diversity, and different feature reduction or expansion techniques affect performance.

[Arxiv](https://arxiv.org/abs/2509.15680)