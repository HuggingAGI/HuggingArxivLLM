# Turbo-ICL：基于上下文学习的Turbo均衡方法

发布时间：2025年05月09日

`LLM应用` `通信系统` `信号处理`

> Turbo-ICL: In-Context Learning-Based Turbo Equalization

# 摘要

> 本文提出了一种创新的上下文学习（ICL）框架，灵感源自大规模语言模型（LLMs），旨在解决编码多输入多输出（MIMO）系统中的软输入软输出信道均衡问题。该方法通过分析导频信号和解码器反馈的提示，直接推断后验符号分布。其核心创新在于采用提示增强技术，将解码器输出的外信息作为额外上下文，使ICL模型能够在turbo解码迭代中逐步优化符号估计。基于Transformer和状态空间架构，我们开发了两种模型变体，并通过实验验证了其性能。仿真结果表明，在传统线性假设失效的情况下，如低分辨率量化场景中，ICL均衡器的表现超越了传统基于模型的基线方法，即便后者拥有完美信道状态信息。此外，实验还展示了Transformer模型在训练数据有限情况下的优势，以及状态空间模型在资源受限环境中的高效性。

> This paper introduces a novel in-context learning (ICL) framework, inspired by large language models (LLMs), for soft-input soft-output channel equalization in coded multiple-input multiple-output (MIMO) systems. The proposed approach learns to infer posterior symbol distributions directly from a prompt of pilot signals and decoder feedback. A key innovation is the use of prompt augmentation to incorporate extrinsic information from the decoder output as additional context, enabling the ICL model to refine its symbol estimates iteratively across turbo decoding iterations. Two model variants, based on Transformer and state-space architectures, are developed and evaluated. Extensive simulations demonstrate that, when traditional linear assumptions break down, e.g., in the presence of low-resolution quantization, ICL equalizers consistently outperform conventional model-based baselines, even when the latter are provided with perfect channel state information. Results also highlight the advantage of Transformer-based models under limited training diversity, as well as the efficiency of state-space models in resource-constrained scenarios.

[Arxiv](https://arxiv.org/abs/2505.06175)