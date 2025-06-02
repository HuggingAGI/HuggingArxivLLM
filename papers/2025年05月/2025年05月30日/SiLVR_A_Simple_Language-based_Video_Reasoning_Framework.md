# SiLVR：一个简洁的语言驱动视频推理框架

发布时间：2025年05月30日

`LLM应用` `视频处理` `视频分析`

> SiLVR: A Simple Language-based Video Reasoning Framework

# 摘要

> 测试时间优化的最新进展为大型语言模型（LLMs）带来了强大的推理能力，使其能够解决复杂的数学和编程问题。然而，多模态大语言模型（MLLMs）在复杂视频语言任务中的推理能力仍有明显差距。为解决这一问题，我们提出了SiLVR——一个基于语言的简单视频推理框架，将复杂的视频理解分解为两个阶段。第一阶段，SiLVR利用多感官输入（如短视频字幕和音频/语音字幕）将原始视频转换为基于语言的表示形式。第二阶段，将语言描述输入到强大的推理LLM中，以解决复杂的视频语言理解任务。为了处理长上下文的多感官输入，我们采用了一种自适应标记缩减方案，该方案动态确定采样标记的时间粒度。我们的简单、模块化且无需训练的视频推理框架在Video-MME（长）、Video-MMMU（理解）、Video-MMLU、CGBench和EgoLife等基准测试中取得了最佳报告结果。此外，我们的实证研究专注于视频推理能力，结果表明，尽管强大的推理LLM并未经过显式视频训练，但它们仍能有效聚合视频、语音和音频中的多感官输入信息，以处理视频中的复杂时间、因果、长上下文和知识获取推理任务。代码可在https://github.com/CeeZh/SILVR获取。

> Recent advances in test-time optimization have led to remarkable reasoning capabilities in Large Language Models (LLMs), enabling them to solve highly complex problems in math and coding. However, the reasoning capabilities of multimodal LLMs (MLLMs) still significantly lag, especially for complex video-language tasks. To address this issue, we present SiLVR, a Simple Language-based Video Reasoning framework that decomposes complex video understanding into two stages. In the first stage, SiLVR transforms raw video into language-based representations using multisensory inputs, such as short clip captions and audio/speech subtitles. In the second stage, language descriptions are fed into a powerful reasoning LLM to solve complex video-language understanding tasks. To handle long-context multisensory inputs, we use an adaptive token reduction scheme, which dynamically determines the temporal granularity with which to sample the tokens. Our simple, modular, and training-free video reasoning framework achieves the best-reported results on Video-MME (long), Video-MMMU (comprehension), Video-MMLU, CGBench, and EgoLife. Furthermore, our empirical study focused on video reasoning capabilities shows that, despite not being explicitly trained on video, strong reasoning LLMs can effectively aggregate multisensory input information from video, speech, and audio for complex temporal, causal, long-context, and knowledge acquisition reasoning tasks in video. Code is available at https://github.com/CeeZh/SILVR.

[Arxiv](https://arxiv.org/abs/2505.24869)