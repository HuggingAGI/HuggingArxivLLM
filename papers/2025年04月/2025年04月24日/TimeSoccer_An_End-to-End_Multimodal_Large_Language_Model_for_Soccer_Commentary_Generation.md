# TimeSoccer：端到端多模态大语言模型的足球评论生成方案

发布时间：2025年04月24日

`LLM应用

摘要讨论了多模态大型语言模型在足球评论生成中的应用，提出了一个新的模型TimeSoccer，用于端到端处理足球视频并生成评论。这属于LLM的具体应用，因此归类为LLM应用。` `视频处理`

> TimeSoccer: An End-to-End Multimodal Large Language Model for Soccer Commentary Generation

# 摘要

> 足球作为一项全球备受喜爱的运动，以其漫长的比赛和独特的精彩瞬间著称。近年来，多模态大型语言模型（MLLMs）在时间定位和视频理解方面取得了显著进展，为足球评论生成提供了可能。然而，足球评论生成需要在长视频中实现精准的时间定位和语义丰富的描述。现有足球MLLMs通常依赖时间先验来进行字幕生成，导致无法对足球视频进行端到端处理。传统方法虽然采用两步范式，但复杂且难以捕捉全局上下文，影响了性能。为了解决这些问题，我们提出了TimeSoccer，这是首个专为完整比赛视频设计的端到端足球MLLM，用于单点密集视频字幕生成（SDVC）任务。TimeSoccer在一个过程中同时预测时间戳并生成字幕，能够在45分钟的比赛中进行全局上下文建模。为了支持对足球比赛长视频的理解，我们引入了MoFA-Select，一个无需训练、基于运动感知的帧压缩模块。它通过粗到细的策略自适应地选择代表性帧，并结合互补的训练范式，增强了模型处理长时序的能力。大量实验表明，TimeSoccer在端到端形式下，在SDVC任务中达到了最先进（SoTA）的性能，生成的评论不仅时间对齐准确，而且语义相关性强，质量高。

> Soccer is a globally popular sporting event, typically characterized by long matches and distinctive highlight moments. Recent advances in Multimodal Large Language Models (MLLMs) offer promising capabilities in temporal grounding and video understanding, soccer commentary generation often requires precise temporal localization and semantically rich descriptions over long-form video. However, existing soccer MLLMs often rely on the temporal a priori for caption generation, so they cannot process the soccer video end-to-end. While some traditional approaches follow a two-step paradigm that is complex and fails to capture the global context to achieve suboptimal performance. To solve the above issues, we present TimeSoccer, the first end-to-end soccer MLLM for Single-anchor Dense Video Captioning (SDVC) in full-match soccer videos. TimeSoccer jointly predicts timestamps and generates captions in a single pass, enabling global context modeling across 45-minute matches. To support long video understanding of soccer matches, we introduce MoFA-Select, a training-free, motion-aware frame compression module that adaptively selects representative frames via a coarse-to-fine strategy, and incorporates complementary training paradigms to strengthen the model's ability to handle long temporal sequences. Extensive experiments demonstrate that our TimeSoccer achieves State-of-The-Art (SoTA) performance on the SDVC task in an end-to-end form, generating high-quality commentary with accurate temporal alignment and strong semantic relevance.

[Arxiv](https://arxiv.org/abs/2504.17365)