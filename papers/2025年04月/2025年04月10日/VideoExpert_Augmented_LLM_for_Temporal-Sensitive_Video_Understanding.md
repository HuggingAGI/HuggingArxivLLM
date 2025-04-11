# VideoExpert：增强版LLM助力时间敏感视频理解

发布时间：2025年04月10日

`LLM应用` `视频分析` `计算机视觉`

> VideoExpert: Augmented LLM for Temporal-Sensitive Video Understanding

# 摘要

> 视频理解的核心挑战在于感知视频内容随时间的动态变化。然而，多模态大语言模型在处理时间敏感的视频任务时表现欠佳，这类任务需要生成时间戳以标记特定事件的发生。现有策略要求MLLMs直接生成绝对或相对时间戳，但我们发现这些模型往往更依赖语言模式而非视觉线索，这严重影响了其性能表现。为解决这一问题，我们提出了VideoExpert，一个适用于多种时间敏感视频任务的通用MLLM。受专家概念启发，VideoExpert集成了两个并行模块：时间专家和空间专家。时间专家负责建模时间序列并执行时间定位，处理高帧率但压缩后的视频片段以捕捉视频中的动态变化，并包含一个轻量级预测头以实现精准的事件定位。空间专家专注于内容细节分析和指令遵循，处理专门设计的空间标记和语言输入，旨在生成与内容相关联的响应。这两个专家通过特殊标记无缝协作，确保时间定位和内容生成的协调一致。值得注意的是，时间专家和空间专家各自拥有独立的参数集。通过将时间定位与内容生成分离，VideoExpert避免了在时间戳预测中出现文本模式偏见。此外，我们引入了一个空间压缩模块以获取空间标记。该模块在保留关键信息的同时过滤并压缩图像块标记，为空间专家提供紧凑但细节丰富的输入。大量实验验证了VideoExpert的有效性和多功能性。

> The core challenge in video understanding lies in perceiving dynamic content changes over time. However, multimodal large language models struggle with temporal-sensitive video tasks, which requires generating timestamps to mark the occurrence of specific events. Existing strategies require MLLMs to generate absolute or relative timestamps directly. We have observed that those MLLMs tend to rely more on language patterns than visual cues when generating timestamps, affecting their performance. To address this problem, we propose VideoExpert, a general-purpose MLLM suitable for several temporal-sensitive video tasks. Inspired by the expert concept, VideoExpert integrates two parallel modules: the Temporal Expert and the Spatial Expert. The Temporal Expert is responsible for modeling time sequences and performing temporal grounding. It processes high-frame-rate yet compressed tokens to capture dynamic variations in videos and includes a lightweight prediction head for precise event localization. The Spatial Expert focuses on content detail analysis and instruction following. It handles specially designed spatial tokens and language input, aiming to generate content-related responses. These two experts collaborate seamlessly via a special token, ensuring coordinated temporal grounding and content generation. Notably, the Temporal and Spatial Experts maintain independent parameter sets. By offloading temporal grounding from content generation, VideoExpert prevents text pattern biases in timestamp predictions. Moreover, we introduce a Spatial Compress module to obtain spatial tokens. This module filters and compresses patch tokens while preserving key information, delivering compact yet detail-rich input for the Spatial Expert. Extensive experiments demonstrate the effectiveness and versatility of the VideoExpert.

[Arxiv](https://arxiv.org/abs/2504.07519)