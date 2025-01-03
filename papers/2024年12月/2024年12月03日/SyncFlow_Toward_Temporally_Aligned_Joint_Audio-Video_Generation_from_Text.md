# SyncFlow: 实现文本到时间对齐的音频-视频联合生成

发布时间：2024年12月03日

`其他

理由：这篇论文主要讨论的是从文本同时生成时间同步的音频和视频的技术，涉及多模态生成和双扩散变换器架构。虽然使用了生成模型，但重点在于多模态生成和同步技术，而不是直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `多媒体` `生成模型`

> SyncFlow: Toward Temporally Aligned Joint Audio-Video Generation from Text

# 摘要

> # 摘要
视频和音频是人类自然感知的紧密相关模态。尽管近期技术已能从文本生成音频或视频，但同时生成这两种模态通常依赖级联过程或多模态对比编码器。然而，这些方法因推理和条件过程中的固有信息损失，往往效果欠佳。本文提出的SyncFlow系统，能够从文本同时生成时间同步的音频和视频。其核心是双扩散变换器（d-DiT）架构，通过信息融合实现视频和音频的联合建模。为降低计算成本，SyncFlow采用多阶段训练策略，先分离学习视频和音频，再进行联合微调。实验表明，SyncFlow生成的音频和视频比基线方法更具相关性，音频质量和视听对应性显著提升。此外，SyncFlow还展示了强大的零样本能力，如零样本视频到音频生成和适应新视频分辨率，无需额外训练。

> Video and audio are closely correlated modalities that humans naturally perceive together. While recent advancements have enabled the generation of audio or video from text, producing both modalities simultaneously still typically relies on either a cascaded process or multi-modal contrastive encoders. These approaches, however, often lead to suboptimal results due to inherent information losses during inference and conditioning. In this paper, we introduce SyncFlow, a system that is capable of simultaneously generating temporally synchronized audio and video from text. The core of SyncFlow is the proposed dual-diffusion-transformer (d-DiT) architecture, which enables joint video and audio modelling with proper information fusion. To efficiently manage the computational cost of joint audio and video modelling, SyncFlow utilizes a multi-stage training strategy that separates video and audio learning before joint fine-tuning. Our empirical evaluations demonstrate that SyncFlow produces audio and video outputs that are more correlated than baseline methods with significantly enhanced audio quality and audio-visual correspondence. Moreover, we demonstrate strong zero-shot capabilities of SyncFlow, including zero-shot video-to-audio generation and adaptation to novel video resolutions without further training.

[Arxiv](https://arxiv.org/abs/2412.15220)