# UniTTS: 无需分离声学与语义信息的端到端语音合成系统

发布时间：2025年05月22日

`LLM应用` `语音合成` `多模态学习`

> UniTTS: An end-to-end TTS system without decoupling of acoustic and semantic information

# 摘要

> 多代码本中性音频编解码器（如RVQ和GVQ）的出现显著推动了基于LLM的TTS系统的发展。这些编解码器在分离语义和声学信息方面至关重要，同时能够高效利用语义先验。然而，由于语义和声学信息无法完全对齐，这些方法在应用于基于LLM的TTS时存在一个显著缺点：大型语言模型可能无法充分获取全面的音频信息。为了解决这一限制，我们提出了DistilCodec和UniTTS，它们共同提供了以下优势：1）该方法可以将一个多代码本音频编解码器蒸馏为一个单代码本音频编解码器，包含32,768个代码，同时实现近100%的利用率。2）由于DistilCodec不采用语义对齐方案，因此在训练过程中可以纳入大量高质量的无标签音频（如带有音效的有声读物、歌曲等），进一步扩展数据多样性并拓宽其适用范围。3）借助DistilCodec对全面音频信息的建模能力，我们在UniTTS的预训练框架中集成了三个关键任务：音频模态自回归、文本模态自回归以及语音-文本跨模态自回归。这使得UniTTS能够接受交错的文本和语音/音频提示，同时显著保留LLM的文本能力。4）UniTTS采用三阶段训练过程：预训练、监督微调（SFT）和对齐。源代码和模型检查点可在以下链接获取：https://github.com/IDEA-Emdoor-Lab/UniTTS 和 https://github.com/IDEA-Emdoor-Lab/DistilCodec。

> The emergence of multi-codebook neutral audio codecs such as Residual Vector Quantization (RVQ) and Group Vector Quantization (GVQ) has significantly advanced Large-Language-Model (LLM) based Text-to-Speech (TTS) systems. These codecs are crucial in separating semantic and acoustic information while efficiently harnessing semantic priors. However, since semantic and acoustic information cannot be fully aligned, a significant drawback of these methods when applied to LLM-based TTS is that large language models may have limited access to comprehensive audio information. To address this limitation, we propose DistilCodec and UniTTS, which collectively offer the following advantages: 1) This method can distill a multi-codebook audio codec into a single-codebook audio codec with 32,768 codes while achieving a near 100\% utilization. 2) As DistilCodec does not employ a semantic alignment scheme, a large amount of high-quality unlabeled audio (such as audiobooks with sound effects, songs, etc.) can be incorporated during training, further expanding data diversity and broadening its applicability. 3) Leveraging the comprehensive audio information modeling of DistilCodec, we integrated three key tasks into UniTTS's pre-training framework: audio modality autoregression, text modality autoregression, and speech-text cross-modal autoregression. This allows UniTTS to accept interleaved text and speech/audio prompts while substantially preserving LLM's text capabilities. 4) UniTTS employs a three-stage training process: Pre-Training, Supervised Fine-Tuning (SFT), and Alignment. Source code and model checkpoints are publicly available at https://github.com/IDEA-Emdoor-Lab/UniTTS and https://github.com/IDEA-Emdoor-Lab/DistilCodec.

[Arxiv](https://arxiv.org/abs/2505.17426)