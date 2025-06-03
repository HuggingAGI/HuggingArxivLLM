# FusionAudio-1.2M：探索基于多模态上下文融合的细粒度音频字幕生成

发布时间：2025年06月01日

`LLM应用` `音频处理` `视频处理`

> FusionAudio-1.2M: Towards Fine-grained Audio Captioning with Multimodal Contextual Fusion

# 摘要

> 高质量、大规模的音频字幕生成对于提升音频理解能力至关重要，但现有自动化方法往往因依赖有限的单模态或浅层多模态信息，导致生成的字幕缺乏精细细节和语境准确性。受人类听觉感知的启发，我们提出了一种新颖的两阶段自动化管道。首先，通过专门的预训练模型提取多样化的语境线索（如语音、音乐、普通声音及视频中的视觉信息），随后利用大型语言模型（LLM）将这些丰富的多模态输入进行合成，生成详细且语境感知的音频字幕。

这项工作的主要贡献包括：
1. 提出了一种用于精细音频字幕生成的可扩展方法；
2. 发布了FusionAudio数据集，包含120万条详细字幕及600万对问答；
3. 基于FusionAudio开发的增强音频模型，特别是基于CLAP的音频编码器，具有更优的音频-文本对齐和指令遵循能力。

这项研究为更细致和准确的复杂音频环境自动化理解奠定了基础。代码和数据可在https://github.com/satsuki2486441738/FusionAudio获取。

> High-quality, large-scale audio captioning is crucial for advancing audio understanding, yet current automated methods often generate captions that lack fine-grained detail and contextual accuracy, primarily due to their reliance on limited unimodal or superficial multimodal information. Drawing inspiration from human auditory perception, which adeptly integrates cross-modal cues and performs sophisticated auditory scene analysis, we introduce a novel two-stage automated pipeline. This pipeline first employs specialized pretrained models to extract diverse contextual cues (e.g., speech, music, general sounds, and visual information from associated video). A large language model (LLM) then synthesizes these rich, multimodal inputs to generate detailed and context-aware audio captions. Key contributions of this work include: (1) the proposed scalable method for fine-grained audio caption generation; (2) FusionAudio, a new large-scale dataset comprising 1.2 million such detailed captions, combined with 6 million QA pairs; and (3) enhanced audio models developed using FusionAudio, specifically a CLAP-based audio encoder with superior audio-text alignment and instruction following. This paper paves the way for more nuanced and accurate automated understanding of complex audio environments. Code and data can be found in https://github.com/satsuki2486441738/FusionAudio.

[Arxiv](https://arxiv.org/abs/2506.01111)