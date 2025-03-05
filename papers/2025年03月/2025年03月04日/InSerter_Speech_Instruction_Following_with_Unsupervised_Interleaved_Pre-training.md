# InSerter: 语音指令遵循与无监督交错预训练结合

发布时间：2025年03月04日

`LLM应用` `语音处理` `智能助手`

> InSerter: Speech Instruction Following with Unsupervised Interleaved Pre-training

# 摘要

> 语音大语言模型（SpeechLLMs）的最新进展引发了广泛关注。然而，现有方法在遵循语音指令方面表现欠佳，尤其是与直接处理文本输入相比，模型在处理语音输入时的智能水平显著降低。先前研究尝试通过表征和行为对齐等技术缓解语音与文本表示的语义不一致，但需要在后训练阶段精心设计数据对。本文提出了一种简单且可扩展的训练方法——InSerter（交错语音-文本表征预训练）。InSerter旨在预训练大规模无监督的语音-文本序列，其中语音是通过文本转语音转换从大型文本语料库的随机段落中合成的。因此，模型能够根据提供的语音段落生成对应的文本延续，无需进行繁琐的数据设计工作。为了系统评估语音指令遵循能力，我们推出了SpeechInstructBench，这是首个专为语音导向指令遵循任务设计的全面基准测试。我们的InSerter在SpeechInstructBench中实现了SOTA性能，并在多种语音处理任务中展现出优异或具有竞争力的结果。

> Recent advancements in speech large language models (SpeechLLMs) have attracted considerable attention. Nonetheless, current methods exhibit suboptimal performance in adhering to speech instructions. Notably, the intelligence of models significantly diminishes when processing speech-form input as compared to direct text-form input. Prior work has attempted to mitigate this semantic inconsistency between speech and text representations through techniques such as representation and behavior alignment, which involve the meticulous design of data pairs during the post-training phase. In this paper, we introduce a simple and scalable training method called InSerter, which stands for Interleaved Speech-Text Representation Pre-training. InSerter is designed to pre-train large-scale unsupervised speech-text sequences, where the speech is synthesized from randomly selected segments of an extensive text corpus using text-to-speech conversion. Consequently, the model acquires the ability to generate textual continuations corresponding to the provided speech segments, obviating the need for intensive data design endeavors. To systematically evaluate speech instruction-following capabilities, we introduce SpeechInstructBench, the first comprehensive benchmark specifically designed for speech-oriented instruction-following tasks. Our proposed InSerter achieves SOTA performance in SpeechInstructBench and demonstrates superior or competitive results across diverse speech processing tasks.

[Arxiv](https://arxiv.org/abs/2503.02769)