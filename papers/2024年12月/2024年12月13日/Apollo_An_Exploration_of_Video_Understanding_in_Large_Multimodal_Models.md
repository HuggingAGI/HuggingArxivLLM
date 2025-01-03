# Apollo: 探索大型多模态模型中的视频理解

发布时间：2024年12月13日

`LLM应用

理由：这篇论文主要探讨了大型多模态模型（LMMs）在视频理解方面的应用，特别是如何通过优化视频采样、架构、数据组成和训练计划等来提高视频-LMMs的性能。论文还介绍了Apollo系列模型，这些模型在多个基准测试中表现出色，展示了LMMs在实际应用中的潜力。因此，这篇论文属于LLM应用类别。` `视频理解` `多模态模型`

> Apollo: An Exploration of Video Understanding in Large Multimodal Models

# 摘要

> 尽管视频感知能力已迅速融入大型多模态模型（LMMs），但其视频理解的底层机制仍不为人所知。因此，该领域的许多设计决策缺乏合理依据或分析。训练和评估此类模型的高计算成本，加上有限的开放研究，阻碍了视频-LMMs的发展。为此，我们提出了一项全面研究，旨在揭示LMMs中视频理解的有效驱动因素。
    我们首先深入分析了视频-LMM研究中的高计算需求，并发现了扩展一致性：在较小模型和数据集（达到临界规模）上做出的设计和训练决策，能够有效迁移到更大模型上。基于这些见解，我们探索了视频-LMMs的多个视频特定方面，包括视频采样、架构、数据组成、训练计划等。例如，我们证明了训练期间使用fps采样远优于均匀帧采样，并确定了最适合视频表示的视觉编码器。
    在这些发现的指导下，我们推出了Apollo，这是一系列最先进的LMMs，在不同模型尺寸上均表现出色。我们的模型能够高效感知长达一小时的视频，其中Apollo-3B在LongVideoBench上以55.1的分数超越了大多数现有的7B模型。Apollo-7B在MLVU上以70.9的分数和Video-MME上以63.3的分数，与7B LMMs相比处于最先进水平。

> Despite the rapid integration of video perception capabilities into Large Multimodal Models (LMMs), the underlying mechanisms driving their video understanding remain poorly understood. Consequently, many design decisions in this domain are made without proper justification or analysis. The high computational cost of training and evaluating such models, coupled with limited open research, hinders the development of video-LMMs. To address this, we present a comprehensive study that helps uncover what effectively drives video understanding in LMMs.
  We begin by critically examining the primary contributors to the high computational requirements associated with video-LMM research and discover Scaling Consistency, wherein design and training decisions made on smaller models and datasets (up to a critical size) effectively transfer to larger models. Leveraging these insights, we explored many video-specific aspects of video-LMMs, including video sampling, architectures, data composition, training schedules, and more. For example, we demonstrated that fps sampling during training is vastly preferable to uniform frame sampling and which vision encoders are the best for video representation.
  Guided by these findings, we introduce Apollo, a state-of-the-art family of LMMs that achieve superior performance across different model sizes. Our models can perceive hour-long videos efficiently, with Apollo-3B outperforming most existing $7$B models with an impressive 55.1 on LongVideoBench. Apollo-7B is state-of-the-art compared to 7B LMMs with a 70.9 on MLVU, and 63.3 on Video-MME.

[Arxiv](https://arxiv.org/abs/2412.10360)