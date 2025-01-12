# 重新聆听与观察：音视频语音识别的生成式纠错

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进视听语音识别（AVSR）系统，特别是通过生成错误纠正（GER）的方法。论文提出了一种新的范式AVGER，结合了多模态同步编码器和LLMs，以提高转录的准确性。这属于LLM在实际应用中的使用，因此归类为LLM应用。` `语音识别` `多模态学习`

> Listening and Seeing Again: Generative Error Correction for Audio-Visual Speech Recognition

# 摘要

> 与传统自动语音识别（ASR）不同，视听语音识别（AVSR）同时利用音频和视觉信号进行转录推断。近期研究表明，大型语言模型（LLMs）能够通过从ASR生成的N-best假设中预测最佳转录，有效应用于生成错误纠正（GER）。然而，这些LLMs无法同时理解音频和视觉信息，导致GER方法在AVSR中难以实施。为此，我们提出了一种名为AVGER的新范式，遵循“再次听和看”的理念。具体而言，我们首先利用强大的AVSR系统读取音频和视觉信号，生成N-best假设；随后，通过基于Q-former的多模态同步编码器再次读取音频和视觉信息，并将其转换为LLM可理解的压缩表示。这些视听压缩表示与N-best假设共同构成跨模态提示，指导LLM生成最佳转录。此外，我们还引入了多级一致性约束训练准则，涵盖logits级、话语级和表示级，以提升纠正准确性并增强视听压缩表示的可解释性。在LRS3数据集上的实验结果显示，我们的方法优于当前主流AVSR系统，单词错误率（WER）降低了24%。代码和模型可在以下链接获取：https://github.com/CircleRedRain/AVGER。

> Unlike traditional Automatic Speech Recognition (ASR), Audio-Visual Speech Recognition (AVSR) takes audio and visual signals simultaneously to infer the transcription. Recent studies have shown that Large Language Models (LLMs) can be effectively used for Generative Error Correction (GER) in ASR by predicting the best transcription from ASR-generated N-best hypotheses. However, these LLMs lack the ability to simultaneously understand audio and visual, making the GER approach challenging to apply in AVSR. In this work, we propose a novel GER paradigm for AVSR, termed AVGER, that follows the concept of ``listening and seeing again''. Specifically, we first use the powerful AVSR system to read the audio and visual signals to get the N-Best hypotheses, and then use the Q-former-based Multimodal Synchronous Encoder to read the audio and visual information again and convert them into an audio and video compression representation respectively that can be understood by LLM. Afterward, the audio-visual compression representation and the N-Best hypothesis together constitute a Cross-modal Prompt to guide the LLM in producing the best transcription. In addition, we also proposed a Multi-Level Consistency Constraint training criterion, including logits-level, utterance-level and representations-level, to improve the correction accuracy while enhancing the interpretability of audio and visual compression representations. The experimental results on the LRS3 dataset show that our method outperforms current mainstream AVSR systems. The proposed AVGER can reduce the Word Error Rate (WER) by 24% compared to them. Code and models can be found at: https://github.com/CircleRedRain/AVGER.

[Arxiv](https://arxiv.org/abs/2501.04038)