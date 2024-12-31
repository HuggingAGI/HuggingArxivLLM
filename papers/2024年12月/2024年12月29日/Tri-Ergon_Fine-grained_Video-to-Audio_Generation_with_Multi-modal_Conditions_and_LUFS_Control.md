# Tri-Ergon：具备多模态条件和 LUFS 控制的细粒度视频转音频生成

发布时间：2024年12月29日

`其他`

> Tri-Ergon: Fine-grained Video-to-Audio Generation with Multi-modal Conditions and LUFS Control

# 摘要

> 视频转音频（V2A）生成借助仅有的视频视觉特征来产出与场景相符的逼真声音。然而，当下的 V2A 模型往往在生成音频的细粒度控制上有所欠缺，尤其是在响度变化以及多模态条件融合方面。为突破这些局限，我们推出了 Tri-Ergon，这是一个基于扩散的 V2A 模型，它融合了文本、听觉和像素级视觉提示，能够实现细致且语义丰富的音频合成。另外，我们引入了相对于全量程的响度单位（LUFS）嵌入，这使得能够对各个音频通道的响度随时间的变化进行精准手动控制，让我们的模型可以有效地处理现实世界 Foley 工作流程中视频与音频的复杂关联。Tri-Ergon 能够生成时长最长达 60 秒、不同长度的 44.1 kHz 高保真立体声音频片段，这大大超越了通常生成固定时长单声道音频的现有前沿 V2A 方法。

> Video-to-audio (V2A) generation utilizes visual-only video features to produce realistic sounds that correspond to the scene. However, current V2A models often lack fine-grained control over the generated audio, especially in terms of loudness variation and the incorporation of multi-modal conditions. To overcome these limitations, we introduce Tri-Ergon, a diffusion-based V2A model that incorporates textual, auditory, and pixel-level visual prompts to enable detailed and semantically rich audio synthesis. Additionally, we introduce Loudness Units relative to Full Scale (LUFS) embedding, which allows for precise manual control of the loudness changes over time for individual audio channels, enabling our model to effectively address the intricate correlation of video and audio in real-world Foley workflows. Tri-Ergon is capable of creating 44.1 kHz high-fidelity stereo audio clips of varying lengths up to 60 seconds, which significantly outperforms existing state-of-the-art V2A methods that typically generate mono audio for a fixed duration.

[Arxiv](https://arxiv.org/abs/2412.20378)