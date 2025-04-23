# PipeWeaver：通过动态交错管道，解决大型多模态模型训练中的数据动态性问题。

发布时间：2025年04月18日

`其他

理由：这篇论文讨论了大型多模态模型（LMMs）的训练效率问题，并提出了一种动态管道调度框架PipeWeaver来解决训练中的关键挑战。虽然涉及大型模型的训练，但其核心是关于训练框架和优化方法，属于系统层面的研究，而不是直接讨论LLM的应用或理论。因此，分类为其他。` `模型训练` `多模态模型`

> PipeWeaver: Addressing Data Dynamicity in Large Multimodal Model Training with Dynamic Interleaved Pipeline

# 摘要

> 大型多模态模型（LMMs）在多模态理解和生成任务中表现优异，但其训练效率却受到两大问题的困扰：异构架构引发的流水线阶段失衡，以及多模态数据多样性导致的训练数据动态性。

本文提出了PipeWeaver——一款专为LMM训练设计的动态管道调度框架。PipeWeaver的核心是动态交错管道机制，能根据当前训练批次实时优化调度方案。通过自适应模态感知分区和分层调度空间下的高效搜索，PipeWeaver有效解决了LMM训练中的关键挑战。同时，借助SEMU训练模拟器和时空子图重用技术，PipeWeaver实现了性能评估的加速与优化。实验结果表明，PipeWeaver较现有系统可将LMM训练效率提升97.3%，并展现出对多模态数据动态性的卓越适应性。

> Large multimodal models (LMMs) have demonstrated excellent capabilities in both understanding and generation tasks with various modalities. While these models can accept flexible combinations of input data, their training efficiency suffers from two major issues: pipeline stage imbalance caused by heterogeneous model architectures, and training data dynamicity stemming from the diversity of multimodal data.
  In this paper, we present PipeWeaver, a dynamic pipeline scheduling framework designed for LMM training. The core of PipeWeaver is dynamic interleaved pipeline, which searches for pipeline schedules dynamically tailored to current training batches. PipeWeaver addresses issues of LMM training with two techniques: adaptive modality-aware partitioning and efficient pipeline schedule search within a hierarchical schedule space. Meanwhile, PipeWeaver utilizes SEMU (Step Emulator), a training simulator for multimodal models, for accurate performance estimations, accelerated by spatial-temporal subgraph reuse to improve search efficiency. Experiments show that PipeWeaver can enhance LMM training efficiency by up to 97.3% compared to state-of-the-art systems, and demonstrate excellent adaptivity to LMM training's data dynamicity.

[Arxiv](https://arxiv.org/abs/2504.14145)