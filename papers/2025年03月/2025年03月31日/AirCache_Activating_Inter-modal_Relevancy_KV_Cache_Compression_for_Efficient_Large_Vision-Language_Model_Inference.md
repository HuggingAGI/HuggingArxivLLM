# AirCache：实现高效的大视觉-语言模型推理，通过激活跨模态相关性键值缓存压缩。

发布时间：2025年03月31日

`LLM应用` `计算机视觉` `人工智能`

> AirCache: Activating Inter-modal Relevancy KV Cache Compression for Efficient Large Vision-Language Model Inference

# 摘要

> 大型视觉语言模型（LVLMs）凭借其强大的推理能力和泛化能力吸引了广泛关注。然而，处理大量视觉token和生成长上下文输出带来了巨大的计算开销，导致对KV缓存的需求激增。为解决这一瓶颈，我们提出了一种名为AirCache的新型KV缓存压缩方法，旨在加速LVLMs的推理。本研究系统分析了LVLMs注意力机制中视觉和文本token的相关性。实证分析发现，缓存中的视觉token存在显著冗余，通过有策略地消除这些token，可以在保持性能的同时大幅加快上下文生成。基于此发现，我们引入了“精英观察窗口”，用于评估KV缓存中视觉组件的重要性，重点关注稳定跨模态相关性建模和多视角一致性增强。此外，我们开发了一种自适应分层预算分配策略，充分利用了token重要性分布的强度和偏态，相较于均匀分配策略，其效率更优。在多个LVLMs和基准测试中的综合评估表明，我们的方法在仅保留10%视觉KV缓存的情况下，性能与全缓存方法相当，同时将解码延迟降低了29%至66%，适用于各种批量大小和提示长度的输入。值得注意的是，随着缓存保留率的降低，我们的方法相较于现有方法的优势愈发明显。


> Recent advancements in Large Visual Language Models (LVLMs) have gained significant attention due to their remarkable reasoning capabilities and proficiency in generalization. However, processing a large number of visual tokens and generating long-context outputs impose substantial computational overhead, leading to excessive demands for key-value (KV) cache. To address this critical bottleneck, we propose AirCache, a novel KV cache compression method aimed at accelerating LVLMs inference. This work systematically investigates the correlations between visual and textual tokens within the attention mechanisms of LVLMs. Our empirical analysis reveals considerable redundancy in cached visual tokens, wherein strategically eliminating these tokens preserves model performance while significantly accelerating context generation. Inspired by these findings, we introduce an elite observation window for assessing the importance of visual components in the KV cache, focusing on stable inter-modal relevancy modeling with enhanced multi-perspective consistency. Additionally, we develop an adaptive layer-wise budget allocation strategy that capitalizes on the strength and skewness of token importance distribution, showcasing superior efficiency compared to uniform allocation. Comprehensive evaluations across multiple LVLMs and benchmarks demonstrate that our method achieves comparable performance to the full cache while retaining only 10% of visual KV cache, thereby reducing decoding latency by 29% to 66% across various batch size and prompt length of inputs. Notably, as cache retention rates decrease, our method exhibits increasing performance advantages over existing approaches.

[Arxiv](https://arxiv.org/abs/2503.23956)