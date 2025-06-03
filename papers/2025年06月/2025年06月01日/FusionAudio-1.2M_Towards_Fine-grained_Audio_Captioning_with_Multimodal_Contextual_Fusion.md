# FusionAudio-1.2M：探索基于多模态上下文融合的细粒度音频字幕生成

发布时间：2025年06月01日

`LLM应用` `知识图谱`

> FusionAudio-1.2M: Towards Fine-grained Audio Captioning with Multimodal Contextual Fusion

# 摘要

> <翻译失败>

> High-quality, large-scale audio captioning is crucial for advancing audio understanding, yet current automated methods often generate captions that lack fine-grained detail and contextual accuracy, primarily due to their reliance on limited unimodal or superficial multimodal information. Drawing inspiration from human auditory perception, which adeptly integrates cross-modal cues and performs sophisticated auditory scene analysis, we introduce a novel two-stage automated pipeline. This pipeline first employs specialized pretrained models to extract diverse contextual cues (e.g., speech, music, general sounds, and visual information from associated video). A large language model (LLM) then synthesizes these rich, multimodal inputs to generate detailed and context-aware audio captions. Key contributions of this work include: (1) the proposed scalable method for fine-grained audio caption generation; (2) FusionAudio, a new large-scale dataset comprising 1.2 million such detailed captions, combined with 6 million QA pairs; and (3) enhanced audio models developed using FusionAudio, specifically a CLAP-based audio encoder with superior audio-text alignment and instruction following. This paper paves the way for more nuanced and accurate automated understanding of complex audio environments. Code and data can be found in https://github.com/satsuki2486441738/FusionAudio.

[Arxiv](https://arxiv.org/abs/2506.01111)