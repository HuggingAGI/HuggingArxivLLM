# # InfiniPot-V：内存受限键值缓存压缩技术在流媒体视频理解中的应用

发布时间：2025年06月17日

`LLM应用` `移动设备`

> InfiniPot-V: Memory-Constrained KV Cache Compression for Streaming Video Understanding

# 摘要

> 现代多模态大型语言模型（MLLMs）能够处理长达数小时的视频推理，但它们的键值（KV）缓存会随时间线性增长，很快超出手机、AR眼镜和边缘机器人的固定内存限制。以往的压缩方法要么假设整个视频和用户查询离线可用，要么必须先构建完整缓存，导致内存仍随流长度增长。InfiniPot-V是首个无训练、无查询依赖的框架，为流式视频理解设定了固定且与长度无关的内存上限。在视频编码过程中，InfiniPot-V实时监控缓存，一旦达到用户设定的阈值，立即启动轻量级压缩：通过时间轴冗余（TaR）度量去除冗余标记，利用值范数（VaN）排序保留关键语义标记。在四个开源MLLMs和六个视频基准测试中，InfiniPot-V将GPU峰值内存减少高达94%，保持实时生成能力，甚至在多轮对话中超越完整缓存的准确性。无需重新训练或查询知识，InfiniPot-V突破了KV缓存瓶颈，为设备端流式视频助手铺平了道路。

> Modern multimodal large language models (MLLMs) can reason over hour-long video, yet their key-value (KV) cache grows linearly with time--quickly exceeding the fixed memory of phones, AR glasses, and edge robots. Prior compression schemes either assume the whole video and user query are available offline or must first build the full cache, so memory still scales with stream length. InfiniPot-V is the first training-free, query-agnostic framework that enforces a hard, length-independent memory cap for streaming video understanding. During video encoding it monitors the cache and, once a user-set threshold is reached, runs a lightweight compression pass that (i) removes temporally redundant tokens via Temporal-axis Redundancy (TaR) metric and (ii) keeps semantically significant tokens via Value-Norm (VaN) ranking. Across four open-source MLLMs and four long-video and two streaming-video benchmarks, InfiniPot-V cuts peak GPU memory by up to 94%, sustains real-time generation, and matches or surpasses full-cache accuracy--even in multi-turn dialogues. By dissolving the KV cache bottleneck without retraining or query knowledge, InfiniPot-V closes the gap for on-device streaming video assistants.

[Arxiv](https://arxiv.org/abs/2506.15745)