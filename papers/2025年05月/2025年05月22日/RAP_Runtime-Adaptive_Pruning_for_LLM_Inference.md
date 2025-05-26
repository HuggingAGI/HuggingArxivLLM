# 针对大语言模型推理的运行时自适应剪枝方法

发布时间：2025年05月22日

`LLM应用` `模型压缩` `机器学习模型优化`

> RAP: Runtime-Adaptive Pruning for LLM Inference

# 摘要

> 大型语言模型（LLMs）在语言理解和生成方面表现出色，但其巨大的计算和内存需求却成为了部署的拦路虎。压缩技术为解决这一问题提供了潜在的突破口。然而，现有的方法大多依赖固定的启发式策略，无法适应运行时内存变化或来自不同用户请求的异构 KV 缓存需求。针对这些局限，我们提出了 RAP，这是一个基于强化学习（RL）的弹性剪枝框架，能够在感知运行时的情况下动态调整压缩策略。具体来说，RAP 动态跟踪模型参数与 KV 缓存之间不断变化的比例。由于 FFNs 包含了大部分参数，而参数轻量级的注意力层主导了 KV 缓存的形成，RL 代理仅保留那些在当前内存预算内最大化效用的组件，条件是瞬时工作负载和设备状态。实验结果表明，RAP 在性能上优于现有的最先进基线，首次实现了在运行时同时考虑模型权重和 KV 缓存。

> Large language models (LLMs) excel at language understanding and generation, but their enormous computational and memory requirements hinder deployment. Compression offers a potential solution to mitigate these constraints. However, most existing methods rely on fixed heuristics and thus fail to adapt to runtime memory variations or heterogeneous KV-cache demands arising from diverse user requests. To address these limitations, we propose RAP, an elastic pruning framework driven by reinforcement learning (RL) that dynamically adjusts compression strategies in a runtime-aware manner. Specifically, RAP dynamically tracks the evolving ratio between model parameters and KV-cache across practical execution. Recognizing that FFNs house most parameters, whereas parameter -light attention layers dominate KV-cache formation, the RL agent retains only those components that maximize utility within the current memory budget, conditioned on instantaneous workload and device state. Extensive experiments results demonstrate that RAP outperforms state-of-the-art baselines, marking the first time to jointly consider model weights and KV-cache on the fly.

[Arxiv](https://arxiv.org/abs/2505.17138)