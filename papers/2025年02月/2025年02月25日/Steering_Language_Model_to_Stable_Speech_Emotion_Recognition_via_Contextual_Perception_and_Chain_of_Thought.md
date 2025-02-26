# # 上下文感知与思维链引导语言模型实现稳定语音情感识别

发布时间：2025年02月25日

`LLM应用` `语音情感识别` `音频处理`

> Steering Language Model to Stable Speech Emotion Recognition via Contextual Perception and Chain of Thought

# 摘要

> 大规模音频语言模型（ALMs）如Qwen2-Audio，具备处理多种音频信号、分析音频并生成文本响应的能力。然而，在语音情感识别（SER）任务中，这类模型常因幻觉现象导致误判或输出无关内容。针对这一问题，我们提出了一种名为【数学公式】的新型ALM，通过结合上下文感知与思维链（CoT）方法，显著提升了SER的稳定性和准确性。该模型整合了Whisper编码器进行语义理解，并采用Emotion2Vec-S实现声学感知，其中Emotion2Vec-S通过半监督学习扩展了原始模型，增强了情感分辨能力。此外，【数学公式】采用逐步推理的思维链方法，结合语音内容和说话风格，进一步优化了识别效果。为了提高模型的稳定性，【数学公式】还引入了从显式思维链到隐式思维链的自蒸馏机制，有效减少了误差积累，显著提升了识别精度。实验结果表明，【数学公式】在语音情感识别任务中的表现显著优于现有主流ALMs（如Qwen2-Audio和SECap），能够提供更加稳定和精准的情感识别结果。我们已公开相关训练代码、检查点和测试集，以支持进一步研究。

> Large-scale audio language models (ALMs), such as Qwen2-Audio, are capable of comprehending diverse audio signal, performing audio analysis and generating textual responses. However, in speech emotion recognition (SER), ALMs often suffer from hallucinations, resulting in misclassifications or irrelevant outputs. To address these challenges, we propose C$^2$SER, a novel ALM designed to enhance the stability and accuracy of SER through Contextual perception and Chain of Thought (CoT). C$^2$SER integrates the Whisper encoder for semantic perception and Emotion2Vec-S for acoustic perception, where Emotion2Vec-S extends Emotion2Vec with semi-supervised learning to enhance emotional discrimination. Additionally, C$^2$SER employs a CoT approach, processing SER in a step-by-step manner while leveraging speech content and speaking styles to improve recognition. To further enhance stability, C$^2$SER introduces self-distillation from explicit CoT to implicit CoT, mitigating error accumulation and boosting recognition accuracy. Extensive experiments show that C$^2$SER outperforms existing popular ALMs, such as Qwen2-Audio and SECap, delivering more stable and precise emotion recognition. We release the training code, checkpoints, and test sets to facilitate further research.

[Arxiv](https://arxiv.org/abs/2502.18186)