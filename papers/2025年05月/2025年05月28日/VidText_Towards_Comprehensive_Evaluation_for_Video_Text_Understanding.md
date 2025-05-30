# VidText：推进视频文本的全面理解评估

发布时间：2025年05月28日

`其他` `视频分析` `多模态`

> VidText: Towards Comprehensive Evaluation for Video Text Understanding

# 摘要

> 视频中的视觉文本承载着丰富的语义信息，这对于全面理解视频内容以及推理局部人类行为至关重要。然而，现有视频理解基准大多忽视了文本信息，而专注于OCR的基准又局限于静态图像，这限制了它们捕捉文本与动态视觉环境之间交互的能力。为了解决这一问题，我们提出了VidText，这是一个全新的基准，旨在全面深入地评估视频文本理解能力。VidText具有以下关键特点：1) 它涵盖了广泛的真实世界场景，并支持多语言内容，包含视频文本自然出现的各种设置。2) 它引入了一个分层评估框架，包括视频级别、片段级别和实例级别的任务，能够评估全局总结和局部检索能力。3) 该基准还引入了一系列配对感知推理任务，从视觉文本感知到文本与视觉信息之间的跨模态推理。在18个最先进的大型多模态模型（LMMs）上的广泛实验表明，当前模型在大多数任务上表现挣扎，仍有很大的改进空间。进一步分析表明，模型的内在因素（如输入分辨率和OCR能力）以及外部因素（如辅助信息的使用和Chain-of-Thought推理策略）都对结果有显著影响。我们希望VidText能够填补现有视频理解基准的空白，并为未来在动态环境中结合视频文本的多模态推理研究奠定基础。

> Visual texts embedded in videos carry rich semantic information, which is crucial for both holistic video understanding and fine-grained reasoning about local human actions. However, existing video understanding benchmarks largely overlook textual information, while OCR-specific benchmarks are constrained to static images, limiting their ability to capture the interaction between text and dynamic visual contexts. To address this gap, we propose VidText, a new benchmark designed for comprehensive and in-depth evaluation of video text understanding. VidText offers the following key features: 1) It covers a wide range of real-world scenarios and supports multilingual content, encompassing diverse settings where video text naturally appears. 2) It introduces a hierarchical evaluation framework with video-level, clip-level, and instance-level tasks, enabling assessment of both global summarization and local retrieval capabilities. 3) The benchmark also introduces a set of paired perception reasoning tasks, ranging from visual text perception to cross-modal reasoning between textual and visual information. Extensive experiments on 18 state-of-the-art Large Multimodal Models (LMMs) reveal that current models struggle across most tasks, with significant room for improvement. Further analysis highlights the impact of both model-intrinsic factors, such as input resolution and OCR capability, and external factors, including the use of auxiliary information and Chain-of-Thought reasoning strategies. We hope VidText will fill the current gap in video understanding benchmarks and serve as a foundation for future research on multimodal reasoning with video text in dynamic environments.

[Arxiv](https://arxiv.org/abs/2505.22810)