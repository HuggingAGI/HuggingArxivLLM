# 用于交互式视频生成的世界模型学习

发布时间：2025年05月28日

`其他` `计算机视觉` `视频生成`

> Learning World Models for Interactive Video Generation

# 摘要

> 基础世界模型需兼具互动性与时空一致性，方能在动作选择中实现有效规划。然而，现有长视频生成模型受限于累积误差和记忆机制两大难题，其世界建模能力尚显不足。我们通过引入动作条件和自回归框架，增强了图像到视频模型的互动性能，发现自回归视频生成中的累积误差难以避免，而记忆机制的欠缺则导致世界模型的不连贯。为此，我们提出视频检索增强生成（VRAG），借助显式全局状态条件，显著降低了长期累积误差，提升了世界模型的时空一致性。相比之下，单纯扩展上下文窗口或检索增强的自回归生成在视频生成中表现不佳，主要归因于当前视频模型的内在学习能力有限。本研究不仅揭示了视频世界模型的核心挑战，更为提升具备内部世界建模能力的视频生成模型奠定了全面基准。

> Foundational world models must be both interactive and preserve spatiotemporal coherence for effective future planning with action choices. However, present models for long video generation have limited inherent world modeling capabilities due to two main challenges: compounding errors and insufficient memory mechanisms. We enhance image-to-video models with interactive capabilities through additional action conditioning and autoregressive framework, and reveal that compounding error is inherently irreducible in autoregressive video generation, while insufficient memory mechanism leads to incoherence of world models. We propose video retrieval augmented generation (VRAG) with explicit global state conditioning, which significantly reduces long-term compounding errors and increases spatiotemporal consistency of world models. In contrast, naive autoregressive generation with extended context windows and retrieval-augmented generation prove less effective for video generation, primarily due to the limited in-context learning capabilities of current video models. Our work illuminates the fundamental challenges in video world models and establishes a comprehensive benchmark for improving video generation models with internal world modeling capabilities.

[Arxiv](https://arxiv.org/abs/2505.21996)