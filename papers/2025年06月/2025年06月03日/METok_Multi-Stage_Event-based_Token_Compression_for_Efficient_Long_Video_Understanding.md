# METok：多阶段事件驱动的Token压缩技术，助力高效长视频理解

发布时间：2025年06月03日

`LLM应用` `视频处理` `数据压缩`

> METok: Multi-Stage Event-based Token Compression for Efficient Long Video Understanding

# 摘要

> 近期，视频大型语言模型（VLLMs）在理解视频内容方面取得了显著进展。然而，处理长视频仍面临计算需求高和视觉数据冗余的挑战。为此，我们提出了METok——一个无需训练的多阶段事件驱动的令牌压缩框架，旨在加速VLLMs推理同时保持准确性。METok通过三个关键阶段逐步消除冗余视觉令牌：（1）视觉编码过程中的事件感知压缩，（2）预填充阶段基于语义对齐和事件重要性的分层令牌剪枝，（3）解码阶段的KV缓存优化，进一步减少内存消耗。实验结果表明，METok通过动态选择信息丰富的视觉令牌，在效率与准确性之间实现了最佳平衡。例如，配备METok的LongVA-7B实现了80.6%的浮点运算次数减少和93.5%的KV缓存内存节省，同时保持了相当甚至更优的准确性。

> Recent advances in Video Large Language Models (VLLMs) have significantly enhanced their ability to understand video content. Nonetheless, processing long videos remains challenging due to high computational demands and the redundancy present in the visual data. In this work, we propose METok, a training-free, Multi-stage Event-based Token compression framework designed to accelerate VLLMs' inference while preserving accuracy. METok progressively eliminates redundant visual tokens across three critical stages: (1) event-aware compression during vision encoding, (2) hierarchical token pruning in the prefilling stage based on semantic alignment and event importance, and (3) a decoding-stage KV Cache optimization that further reduces memory consumption. Our experiments on diverse video benchmarks demonstrate that METok achieves an optimal trade-off between efficiency and accuracy by dynamically selecting informative visual tokens. For instance, equipping LongVA-7B with METok realizes an 80.6% FLOPs reduction and 93.5% KV Cache memory savings, all while maintaining comparable or even superior accuracy.

[Arxiv](https://arxiv.org/abs/2506.02850)