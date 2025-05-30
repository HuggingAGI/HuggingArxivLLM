# FlashFormer：全模型内核实现高效低批量推理

发布时间：2025年05月28日

`LLM应用` `高性能计算` `计算机系统`

> FlashFormer: Whole-Model Kernels for Efficient Low-Batch Inference

# 摘要

> 现代大型语言模型的规模和计算特性激发了开发专用训练与推理内核的热潮。现有内核主要针对大批次场景优化计算利用率，但在内存带宽和启动开销显著的低批次推理中，仍有许多重要应用如边缘部署和低延迟场景需要关注。本文提出FlashFormer概念验证内核，专注于加速基于Transformer的大型语言模型单批次推理。实验结果显示，在不同模型规模和量化设置下，FlashFormer相比现有最优推理内核实现了显著的速度提升。

> The size and compute characteristics of modern large language models have led to an increased interest in developing specialized kernels tailored for training and inference. Existing kernels primarily optimize for compute utilization, targeting the large-batch training and inference settings. However, low-batch inference, where memory bandwidth and kernel launch overheads contribute are significant factors, remains important for many applications of interest such as in edge deployment and latency-sensitive applications. This paper describes FlashFormer, a proof-of-concept kernel for accelerating single-batch inference for transformer-based large language models. Across various model sizes and quantizations settings, we observe nontrivial speedups compared to existing state-of-the-art inference kernels.

[Arxiv](https://arxiv.org/abs/2505.22758)