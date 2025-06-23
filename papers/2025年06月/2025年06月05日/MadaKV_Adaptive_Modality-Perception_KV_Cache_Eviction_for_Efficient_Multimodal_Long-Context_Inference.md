# MadaKV：自适应多模态感知的 KV 缓存替换策略，实现高效多模态长上下文推理

发布时间：2025年06月05日

`LLM应用` `多模态` `模型优化`

> MadaKV: Adaptive Modality-Perception KV Cache Eviction for Efficient Multimodal Long-Context Inference

# 摘要

> 本文提出了一种名为 MadaKV 的模态自适应键值 (KV) 缓存替换策略，旨在提升多模态大语言模型 (MLLM) 在长上下文推理中的效率。在多模态场景中，注意力头对不同模态的偏好各不相同，导致不同注意力头之间的模态重要性存在显著差异。传统的 KV 缓存替换方法专为单模态环境设计，无法捕捉模态特定信息，因此性能有限。MadaKV 通过模态偏好自适应和分层压缩补偿两大核心组件，有效解决了这一问题。通过动态感知注意力头内的模态信息并自适应地保留关键令牌，MadaKV 在保持高精度的同时，大幅减少了 KV 缓存内存占用和模型推理解码延迟（提升 1.3 到 1.5 倍）。在具有代表性的 MLLM 和 MileBench 基准上的广泛实验表明，MadaKV 的有效性显著优于现有的 KV 缓存替换方法。

> This paper introduces MadaKV, a modality-adaptive key-value (KV) cache eviction strategy designed to enhance the efficiency of multimodal large language models (MLLMs) in long-context inference. In multimodal scenarios, attention heads exhibit varying preferences for different modalities, resulting in significant disparities in modality importance across attention heads. Traditional KV cache eviction methods, which are tailored for unimodal settings, fail to capture modality-specific information, thereby yielding suboptimal performance. MadaKV addresses these challenges through two key components: modality preference adaptation and hierarchical compression compensation. By dynamically sensing modality information within attention heads and adaptively retaining critical tokens, MadaKV achieves substantial reductions in KV cache memory footprint and model inference decoding latency (1.3 to 1.5 times improvement) while maintaining high accuracy across various multimodal long-context tasks. Extensive experiments on representative MLLMs and the MileBench benchmark demonstrate the effectiveness of MadaKV compared to existing KV cache eviction methods.

[Arxiv](https://arxiv.org/abs/2506.15724)