# 记忆助力，虚构误导：多模态大语言模型如何理解视频流事件

发布时间：2025年02月21日

`LLM应用` `视频处理` `计算机视觉`

> Memory Helps, but Confabulation Misleads: Understanding Streaming Events in Videos with MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在全面理解视频方面表现出色，但它们处理流媒体视频的能力——即视频被视为一系列视觉事件——尚未得到充分探索。直觉上，利用过去的事件作为记忆可以增强对当前事件的上下文和时间理解。在本文中，我们展示了将记忆作为上下文可以帮助 MLLMs 更好地理解视频事件。然而，由于这些记忆依赖于对先前事件的预测，它们可能包含错误信息，导致错构并降低性能。为了解决这个问题，我们提出了一种基于记忆增强事件理解的错构感知记忆修改方法，以缓解错构记忆的影响。

> Multimodal large language models (MLLMs) have demonstrated strong performance in understanding videos holistically, yet their ability to process streaming videos-videos are treated as a sequence of visual events-remains underexplored. Intuitively, leveraging past events as memory can enrich contextual and temporal understanding of the current event. In this paper, we show that leveraging memories as contexts helps MLLMs better understand video events. However, because such memories rely on predictions of preceding events, they may contain misinformation, leading to confabulation and degraded performance. To address this, we propose a confabulation-aware memory modification method that mitigates confabulated memory for memory-enhanced event understanding.

[Arxiv](https://arxiv.org/abs/2502.15457)