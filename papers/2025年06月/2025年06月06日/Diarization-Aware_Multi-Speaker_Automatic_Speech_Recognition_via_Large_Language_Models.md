# 借助大型语言模型实现说话人分离感知的多说话人自动语音识别

发布时间：2025年06月06日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在多说话者自动语音识别（MS-ASR）中的应用，展示了LLMs在处理复杂语音场景中的潜力。具体来说，论文提出了一种结合说话人分离和LLM转录的新方法，并在多语言和复杂场景中进行了验证。这属于LLM的应用研究。` `会议记录` `对话分析`

> Diarization-Aware Multi-Speaker Automatic Speech Recognition via Large Language Models

# 摘要

> 多说话者自动语音识别（MS-ASR）在处理重叠语音转录方面面临重大挑战，这对于会议记录和对话分析等应用至关重要。虽然基于序列输出训练（SOT）的方法是常见的解决方案，但它们通常会丢弃绝对时间信息，限制了其在时间敏感场景中的实用性。我们借助大型语言模型（LLMs）在对话音频处理方面的最新进展，提出了一种新型的说话人感知多说话者 ASR 系统，巧妙结合说话人分离与基于 LLM 的转录。我们的框架同时处理结构化的说话人分离输入和帧级说话人及语义嵌入，使 LLM 能够生成分段级别的转录。实验结果表明，该系统在多语言双人对话中表现出稳健性能，并在复杂、高度重叠的多说话者会议场景中展现出卓越表现。这项工作凸显了 LLM 作为联合说话人感知分割和转录的统一后端的潜力。

> Multi-speaker automatic speech recognition (MS-ASR) faces significant challenges in transcribing overlapped speech, a task critical for applications like meeting transcription and conversational analysis. While serialized output training (SOT)-style methods serve as common solutions, they often discard absolute timing information, limiting their utility in time-sensitive scenarios. Leveraging recent advances in large language models (LLMs) for conversational audio processing, we propose a novel diarization-aware multi-speaker ASR system that integrates speaker diarization with LLM-based transcription. Our framework processes structured diarization inputs alongside frame-level speaker and semantic embeddings, enabling the LLM to generate segment-level transcriptions. Experiments demonstrate that the system achieves robust performance in multilingual dyadic conversations and excels in complex, high-overlap multi-speaker meeting scenarios. This work highlights the potential of LLMs as unified back-ends for joint speaker-aware segmentation and transcription.

[Arxiv](https://arxiv.org/abs/2506.05796)