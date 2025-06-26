# # 平滑操作：LLMs 将不完美的提示转化为包含不流畅内容的转录文本

发布时间：2025年06月23日

`LLM应用` `语音处理`

> Smooth Operators: LLMs Translating Imperfect Hints into Disfluency-Rich Transcripts

# 摘要

> 精准识别口语中的不流畅现象不仅有助于提升自动语音和语言处理系统的性能，还能推动更包容的语音和语言技术的发展。借助大型语言模型（LLMs）日益增长的趋势，这些模型能够处理词汇和非词汇输入（例如音频和视频），我们提出了一种将不流畅现象转录为带有时间戳的显式标记的新方法，从而生成完整标注的不流畅丰富转录。我们的方法结合了从音频编码器中提取的声学表示与质量各异的文本输入：无不流畅的干净转录、与时间对齐的对齐器转录，或基于音素的ASR模型输出——所有这些输入可能包含不完美之处。重要的是，我们的实验表明，文本输入无需完美无缺。只要它们包含时间戳相关提示，LLMs就能有效平滑输入并生成完整标注的不流畅转录，突显了它们在处理不完美提示方面的鲁棒性。

> Accurate detection of disfluencies in spoken language is crucial for enhancing the performance of automatic speech and language processing systems, as well as fostering the development of more inclusive speech and language technologies. Leveraging the growing trend of large language models (LLMs) as versatile learners capable of processing both lexical and non-lexical inputs (e.g., audio and video), we propose a novel approach to transcribing disfluencies as explicit tokens with timestamps, enabling the generation of fully annotated disfluency-rich transcripts. Our method integrates acoustic representations extracted from an audio encoder with textual inputs of varying quality: clean transcriptions without disfluencies, time-aligned transcriptions from aligners, or outputs from phoneme-based ASR models -- all of which may contain imperfections. Importantly, our experiments demonstrate that textual inputs do not need to be flawless. As long as they include timestamp-related cues, LLMs can effectively smooth the input and produce fully disfluency-annotated transcripts, underscoring their robustness in handling imperfect hints.

[Arxiv](https://arxiv.org/abs/2506.18510)