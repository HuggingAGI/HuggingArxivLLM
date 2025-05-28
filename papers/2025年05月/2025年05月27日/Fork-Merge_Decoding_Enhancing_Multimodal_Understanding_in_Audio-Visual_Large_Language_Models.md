# Fork-Merge Decoding: 分叉合并解码，以提升视听大型语言模型的多模态理解能力

发布时间：2025年05月27日

`LLM应用`

> Fork-Merge Decoding: Enhancing Multimodal Understanding in Audio-Visual Large Language Models

# 摘要

> 本研究旨在通过解决模态偏见问题，提升音频-视觉大语言模型 (AV-LLMs) 的平衡多模态理解能力，且无需额外训练。目前，AV-LLMs 通常在解码器中联合处理音频和视频特征，虽然这促进了统一的多模态理解，但也可能导致模态偏见，即模型因训练信号不平衡而过度依赖某一模态。为解决这一问题，我们提出了 Fork-Merge 解码 (FMD)，这是一种简单有效的推理时策略，无需额外训练或架构修改。FMD 通过处理仅音频和仅视频输入在早期解码器层中进行模态特定推理（分叉阶段），然后将得到的隐藏状态合并以在剩余层中进行联合推理（合并阶段）。这种方法不仅平衡了模态贡献，还充分利用了跨模态的互补信息。我们在 VideoLLaMA2 和 video-SALMONN 两个代表性的 AV-LLMs 上进行了评估，使用了三个基准数据集。实验结果表明，在音频、视频和联合音频-视觉推理任务上，性能均得到了显著提升，证明了推理时干预在增强稳健多模态理解中的有效性。

> The goal of this work is to enhance balanced multimodal understanding in audio-visual large language models (AV-LLMs) by addressing modality bias without requiring additional training. In current AV-LLMs, audio and video features are typically processed jointly in the decoder. While this strategy facilitates unified multimodal understanding, it may introduce modality bias, where the model tends to over-rely on one modality due to imbalanced training signals. To mitigate this, we propose Fork-Merge Decoding (FMD), a simple yet effective inference-time strategy that requires no additional training or architectural modifications. FMD first performs modality-specific reasoning by processing audio-only and video-only inputs through the early decoder layers (a fork phase), and then merges the resulting hidden states for joint reasoning in the remaining layers (a merge phase). This approach promotes balanced modality contributions and leverages complementary information across modalities. We evaluate our method on two representative AV-LLMs, VideoLLaMA2 and video-SALMONN, using three benchmark datasets. Experimental results demonstrate consistent performance improvements on tasks focused on audio, video, and combined audio-visual reasoning, demonstrating the effectiveness of inference-time interventions for robust multimodal understanding.

[Arxiv](https://arxiv.org/abs/2505.20873)