# 高效零样本文本到语音合成的伪自回归神经编码器语言模型

发布时间：2025年04月14日

`LLM应用` `语音合成`

> Pseudo-Autoregressive Neural Codec Language Models for Efficient Zero-Shot Text-to-Speech Synthesis

# 摘要

> 零样本端到端文本到语音（TTS）系统正面临一个关键挑战：自回归（AR）模型因生成速度慢和缺乏时长可控性而受限，而非自回归（NAR）模型则因缺乏时间建模能力而需要复杂的架构设计。本文提出了一种创新的伪自回归（PAR）编解码语言建模方法，成功融合了AR和NAR建模的优势。通过结合AR模型的时间建模能力和NAR模型的并行生成特性，PAR实现了在固定时间步长下动态生成语音片段。基于此，我们开发了PALLE，一个两阶段TTS系统。第一阶段，PAR沿时间维度逐步生成语音令牌，每一步并行预测所有位置，但仅保留最左侧的语音片段。第二阶段则通过全局上下文信息对低置信度的令牌进行并行迭代优化。实验结果表明，PALLE在LibriTTS数据集上训练，不仅在LibriSpeech测试集上实现了优于F5-TTS、E2-TTS和MaskGCT等最先进系统的语音质量、说话人相似度和可懂度，还将推理速度提升了十倍。更多音频示例请访问https://anonymous-palle.github.io。


> Recent zero-shot text-to-speech (TTS) systems face a common dilemma: autoregressive (AR) models suffer from slow generation and lack duration controllability, while non-autoregressive (NAR) models lack temporal modeling and typically require complex designs. In this paper, we introduce a novel pseudo-autoregressive (PAR) codec language modeling approach that unifies AR and NAR modeling. Combining explicit temporal modeling from AR with parallel generation from NAR, PAR generates dynamic-length spans at fixed time steps. Building on PAR, we propose PALLE, a two-stage TTS system that leverages PAR for initial generation followed by NAR refinement. In the first stage, PAR progressively generates speech tokens along the time dimension, with each step predicting all positions in parallel but only retaining the left-most span. In the second stage, low-confidence tokens are iteratively refined in parallel, leveraging the global contextual information. Experiments demonstrate that PALLE, trained on LibriTTS, outperforms state-of-the-art systems trained on large-scale data, including F5-TTS, E2-TTS, and MaskGCT, on the LibriSpeech test-clean set in terms of speech quality, speaker similarity, and intelligibility, while achieving up to ten times faster inference speed. Audio samples are available at https://anonymous-palle.github.io.

[Arxiv](https://arxiv.org/abs/2504.10352)