# Neptune：长视频理解基准测试的漫长征程

发布时间：2024年12月12日

`LLM应用` `数据集`

> Neptune: The Long Orbit to Benchmarking Long Video Understanding

# 摘要

> 本文介绍了一种半自动的流程，用于为理解长视频生成颇具挑战性的问答诱饵集。现有的许多视频数据集和模型都聚焦于短视频片段（10 秒 - 30 秒）。虽说确实存在一些长视频数据集，但其往往能通过对视频中的每一帧（且通常是极少的帧）应用强大的图像模型来解决，并且通常是高成本人工标注的。为了化解这两个难题，我们提出了一种可扩展的数据集创建流程，借助大型模型（VLMs 和 LLMs），自动生成密集且时间对齐的视频字幕，以及针对视频片段（最长 15 分钟）的高难度问答诱饵集。我们的 Neptune 数据集涵盖了广泛的长视频推理能力，还包含一个侧重于多模态推理的子集。由于现有的开放式问答指标要么基于规则，要么可能依赖于专有模型，我们提供了一种新的基于开源模型的指标 GEM，用于对 Neptune 上的开放式回答进行评分。基准评估显示，大多数当前的开源长视频模型在 Neptune 上表现欠佳，尤其是在测试时间顺序、计数和状态变化的问题上。通过 Neptune，我们旨在促进开发更先进的、能够理解长视频的模型。该数据集可在 https://github.com/google-deepmind/neptune 获取。

> This paper describes a semi-automatic pipeline to generate challenging question-answer-decoy sets for understanding long videos. Many existing video datasets and models are focused on short clips (10s-30s). While some long video datasets do exist, they can often be solved by powerful image models applied per frame (and often to very few frames) in a video, and are usually manually annotated at high cost. In order to mitigate both these problems, we propose a scalable dataset creation pipeline which leverages large models (VLMs and LLMs), to automatically generate dense, time-aligned video captions, as well as tough question answer decoy sets for video segments (up to 15 minutes in length). Our dataset Neptune covers a broad range of long video reasoning abilities and consists of a subset that emphasizes multimodal reasoning. Since existing metrics for open-ended question answering are either rule-based or may rely on proprietary models, we provide a new open source model-based metric GEM to score open-ended responses on Neptune. Benchmark evaluations reveal that most current open-source long video models perform poorly on Neptune, particularly on questions testing temporal ordering, counting and state changes. Through Neptune, we aim to spur the development of more advanced models capable of understanding long videos. The dataset is available at https://github.com/google-deepmind/neptune

[Arxiv](https://arxiv.org/abs/2412.09582)