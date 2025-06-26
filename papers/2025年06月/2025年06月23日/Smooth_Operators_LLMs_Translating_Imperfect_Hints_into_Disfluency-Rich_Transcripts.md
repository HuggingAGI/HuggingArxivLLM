# # 平滑操作者：LLMs 如何将不完美的提示转换为包含不流畅的转录文本

发布时间：2025年06月23日

`LLM应用` `语音识别`

> Smooth Operators: LLMs Translating Imperfect Hints into Disfluency-Rich Transcripts

# 摘要

> 准确识别口语中的不流畅之处，不仅能够提升自动语音和语言处理系统的性能，还能助力开发更加包容的语音和语言技术。借助大型语言模型（LLMs）这一多功能工具，我们提出了一种创新方法，通过将不流畅之处转录为带有时间戳的显式标记，生成完整标注的不流畅转录本。我们的方法结合了从音频编码器提取的声学特征与多种质量的文本输入：无不流畅的干净转录本、对齐器生成的时间对齐转录本，以及基于音素的ASR输出——所有这些都可能包含不完美之处。实验表明，文本输入无需完美，只要包含时间戳相关提示，LLMs就能有效处理并生成完整标注的不流畅转录本，展现出其在应对不完美提示时的强大稳健性。

> Accurate detection of disfluencies in spoken language is crucial for enhancing the performance of automatic speech and language processing systems, as well as fostering the development of more inclusive speech and language technologies. Leveraging the growing trend of large language models (LLMs) as versatile learners capable of processing both lexical and non-lexical inputs (e.g., audio and video), we propose a novel approach to transcribing disfluencies as explicit tokens with timestamps, enabling the generation of fully annotated disfluency-rich transcripts. Our method integrates acoustic representations extracted from an audio encoder with textual inputs of varying quality: clean transcriptions without disfluencies, time-aligned transcriptions from aligners, or outputs from phoneme-based ASR models -- all of which may contain imperfections. Importantly, our experiments demonstrate that textual inputs do not need to be flawless. As long as they include timestamp-related cues, LLMs can effectively smooth the input and produce fully disfluency-annotated transcripts, underscoring their robustness in handling imperfect hints.

[Arxiv](https://arxiv.org/abs/2506.18510)