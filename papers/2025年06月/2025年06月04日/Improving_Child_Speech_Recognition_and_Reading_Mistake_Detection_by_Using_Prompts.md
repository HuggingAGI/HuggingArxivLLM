# 利用提示改进儿童语音识别与阅读错误检测

发布时间：2025年06月04日

`LLM应用` `语音识别`

> Improving Child Speech Recognition and Reading Mistake Detection by Using Prompts

# 摘要

> 自动朗读评估能为教师提供有力支持，帮助他们更高效地评估阅读练习。然而，关于阅读评估系统和应用的研究仍然有限。我们提出了一种新颖的多模态方法，结合音频和文本资源的知识。特别是，我们探讨了利用Whisper和带有提示词的指令微调大型语言模型（LLMs）来提升儿童语音识别的转录质量，以及它们在下游阅读错误检测中的有效性。我们的研究结果表明，与没有提示词的基线Whisper模型相比，提示Whisper和提示LLM的方法更加有效。最佳系统在荷兰儿童朗读语音识别中达到了最先进的性能，词错误率（WER）为5.1%，显著优于基线的9.4%。此外，该系统在阅读错误检测方面也表现出色，将F1分数从0.39提升至0.73。

> Automatic reading aloud evaluation can provide valuable support to teachers by enabling more efficient scoring of reading exercises. However, research on reading evaluation systems and applications remains limited. We present a novel multimodal approach that leverages audio and knowledge from text resources. In particular, we explored the potential of using Whisper and instruction-tuned large language models (LLMs) with prompts to improve transcriptions for child speech recognition, as well as their effectiveness in downstream reading mistake detection. Our results demonstrate the effectiveness of prompting Whisper and prompting LLM, compared to the baseline Whisper model without prompting. The best performing system achieved state-of-the-art recognition performance in Dutch child read speech, with a word error rate (WER) of 5.1%, improving the baseline WER of 9.4%. Furthermore, it significantly improved reading mistake detection, increasing the F1 score from 0.39 to 0.73.

[Arxiv](https://arxiv.org/abs/2506.11079)