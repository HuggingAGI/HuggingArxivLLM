# DATE: 动态绝对时间增强助力长视频理解

发布时间：2025年09月11日

`LLM应用` `媒体与娱乐`

> DATE: Dynamic Absolute Time Enhancement for Long Video Understanding

# 摘要

> 长视频理解一直是多模态大型语言模型（MLLMs）面临的核心挑战，尤其是在需要精确时间推理和事件定位的任务上。现有方法通常采用均匀帧采样，并依赖隐式位置编码来建模时间顺序，但这些方法难以处理长程依赖，导致关键信息丢失，时间理解能力也随之下降。为此，我们提出动态绝对时间增强（DATE）方法，通过时间戳注入机制（TIM）和语义引导的时间感知相似性采样（TASS）策略，增强MLLMs的时间感知能力。具体而言，我们将视频帧嵌入与文本时间戳标记交织，构建连续的时间参考系统；同时将视频采样问题重新定义为视觉-语言检索任务，并提出两阶段算法以兼顾语义相关性和时间覆盖——先将每个查询扩展为描述性标题，使其与视觉特征更好地对齐，再通过相似性驱动的时间正则化贪心策略采样关键事件。我们的方法在绝对时间理解和关键事件定位上取得了显著提升，在时长一小时的视频基准测试中，7B和72B模型均达到了最先进性能。值得注意的是，我们的7B模型在部分基准测试中甚至超越了许多72B模型。

> Long video understanding remains a fundamental challenge for multimodal large language models (MLLMs), particularly in tasks requiring precise temporal reasoning and event localization. Existing approaches typically adopt uniform frame sampling and rely on implicit position encodings to model temporal order. However, these methods struggle with long-range dependencies, leading to critical information loss and degraded temporal comprehension. In this paper, we propose Dynamic Absolute Time Enhancement (DATE) that enhances temporal awareness in MLLMs through the Timestamp Injection Mechanism (TIM) and a semantically guided Temporal-Aware Similarity Sampling (TASS) strategy. Specifically, we interleave video frame embeddings with textual timestamp tokens to construct a continuous temporal reference system. We further reformulate the video sampling problem as a vision-language retrieval task and introduce a two-stage algorithm to ensure both semantic relevance and temporal coverage: enriching each query into a descriptive caption to better align with the vision feature, and sampling key event with a similarity-driven temporally regularized greedy strategy. Our method achieves remarkable improvements w.r.t. absolute time understanding and key event localization, resulting in state-of-the-art performance among 7B and 72B models on hour-long video benchmarks. Particularly, our 7B model even exceeds many 72B models on some benchmarks.

[Arxiv](https://arxiv.org/abs/2509.09263)