# mWhisper-Flamingo：多语言音频-视觉噪声鲁棒语音识别

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何结合预训练的音频模型和视频模型来提升多语言音频-视觉语音识别（AVSR）的效果。虽然论文中提到了预训练模型（如Whisper和AV-HuBERT），但重点在于如何将这些模型应用于多语言AVSR任务中，特别是在噪声环境下的表现提升。因此，这篇论文属于LLM应用类别，因为它涉及将预训练模型应用于具体的多语言任务中。` `语音识别` `多语言处理`

> mWhisper-Flamingo for Multilingual Audio-Visual Noise-Robust Speech Recognition

# 摘要

> # 音频-视觉语音识别 (AVSR)
音频-视觉语音识别 (AVSR) 通过结合唇部视频和音频，能够在噪声环境中提升识别效果。然而，现有方法大多仅针对英语数据进行训练，且缺乏大规模多语言视频数据，导致从头训练模型困难重重。为此，我们提出了 mWhisper-Flamingo，一种多语言 AVSR 模型，融合了预训练音频模型 Whisper 和视频模型 AV-HuBERT 的优势。为了增强多模态集成能力并提升噪声环境下的多语言表现，我们引入了解码器模态丢弃技术，使模型能够在配对的音频-视觉输入及单独的音频/视觉输入上进行训练。mWhisper-Flamingo 在包含 9 种语言的 MuAViC 数据集上取得了最先进的 WER 成绩。在噪声环境下，音频-视觉 mWhisper-Flamingo 在所有语言上的表现均优于仅依赖音频的 Whisper。

> Audio-Visual Speech Recognition (AVSR) combines lip-based video with audio and can improve performance in noise, but most methods are trained only on English data. One limitation is the lack of large-scale multilingual video data, which makes it hard hard to train models from scratch. In this work, we propose mWhisper-Flamingo for multilingual AVSR which combines the strengths of a pre-trained audio model (Whisper) and video model (AV-HuBERT). To enable better multi-modal integration and improve the noisy multilingual performance, we introduce decoder modality dropout where the model is trained both on paired audio-visual inputs and separate audio/visual inputs. mWhisper-Flamingo achieves state-of-the-art WER on MuAViC, an AVSR dataset of 9 languages. Audio-visual mWhisper-Flamingo consistently outperforms audio-only Whisper on all languages in noisy conditions.

[Arxiv](https://arxiv.org/abs/2502.01547)