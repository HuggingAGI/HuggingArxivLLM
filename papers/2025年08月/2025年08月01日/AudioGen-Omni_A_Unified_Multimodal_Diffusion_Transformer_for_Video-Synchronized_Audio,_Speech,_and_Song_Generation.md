# AudioGen-Omni：统一多模态扩散转换器，用于视频同步音频、语音和歌曲生成

发布时间：2025年08月01日

`LLM应用` `音频生成` `多模态`

> AudioGen-Omni: A Unified Multimodal Diffusion Transformer for Video-Synchronized Audio, Speech, and Song Generation

# 摘要

> 我们提出了一种基于多模态扩散变压器（MMDit）的AudioGen-Omni方法，它能够生成与输入视频高度连贯同步的高质量音频、语音和歌曲。通过引入一种全新的联合训练范式，AudioGen-Omni无缝整合了大规模的视频-文本-音频语料库，支持多模态输入条件下的语义丰富、音色多样的音频生成，并能够适应广泛的音频生成任务。该方法采用统一的歌词-语音编码器，将唱诵和说话输入中的音素和音节编码为密集的帧级表示。密集帧级表示通过增强的相位对齐各向异性位置注入（PAAPI）的AdaLN联合注意力机制进行融合，其中RoPE被选择性应用于具有时间结构的模态，以确保精确且稳健的跨模态对齐。通过解冻所有模态并屏蔽缺失输入，AudioGen-Omni缓解了文本冻结范式的语义限制，实现了有效的跨模态调节。这种联合训练方法提升了音频质量、语义对齐和唇同步精度，同时在文本到音频/语音/歌曲任务中达到了最新技术水平。在8秒音频推理仅需1.91秒的情况下，它在效率和通用性方面都取得了显著提升。

> We present AudioGen-Omni - a unified approach based on multimodal diffusion transformers (MMDit), capable of generating high-fidelity audio, speech, and songs coherently synchronized with the input video. AudioGen-Omni introduces a novel joint training paradigm that seamlessly integrates large-scale video-text-audio corpora, enabling a model capable of generating semantically rich, acoustically diverse audio conditioned on multimodal inputs and adaptable to a wide range of audio generation tasks. AudioGen-Omni employs a unified lyrics-transcription encoder that encodes graphemes and phonemes from both sung and spoken inputs into dense frame-level representations. Dense frame-level representations are fused using an AdaLN-based joint attention mechanism enhanced with phase-aligned anisotropic positional infusion (PAAPI), wherein RoPE is selectively applied to temporally structured modalities to ensure precise and robust cross-modal alignment. By unfreezing all modalities and masking missing inputs, AudioGen-Omni mitigates the semantic constraints of text-frozen paradigms, enabling effective cross-modal conditioning. This joint training approach enhances audio quality, semantic alignment, and lip-sync accuracy, while also achieving state-of-the-art results on Text-to-Audio/Speech/Song tasks. With an inference time of 1.91 seconds for 8 seconds of audio, it offers substantial improvements in both efficiency and generality.

[Arxiv](https://arxiv.org/abs/2508.00733)