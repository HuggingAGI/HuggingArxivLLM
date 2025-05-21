# U-SAM：统一语音、音频与音乐理解的音频语言模型

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于音频处理任务，特别是通过结合语音、音频和音乐编码器，并引入新的对比损失模块来提高跨模态对齐。研究的重点在于模型的应用和性能提升，属于LLM应用的范畴。` `音频处理`

> U-SAM: An audio language Model for Unified Speech, Audio, and Music Understanding

# 摘要

> 音频任务的文本生成范式为统一音频理解开辟了新可能。然而，现有模型在处理语音、普通音频事件和音乐等多种音频类型时，仍面临全面理解的挑战。此外，这些模型仅依赖交叉熵损失进行对齐，效果有限，因为它们未能区分冗余音频特征，导致跨模态对齐不足。为解决这些问题，本文提出了U-SAM，一种先进的音频语言模型。U-SAM整合了语音、音频和音乐的专用编码器与预训练大型语言模型（LLM），并采用任务感知的专家混合（MoE）投影器，动态融合特定领域编码器的输出。此外，U-SAM引入语义感知对比损失模块，显式识别冗余音频特征，并在语言监督下校正其语义和频谱表示，从而增强跨模态对齐。实验结果显示，U-SAM在多个基准测试中超越现有模型，并在未见过的任务上展现出潜力，证明了其良好的泛化能力。代码已开源（https://github.com/Honee-W/U-SAM/）。

> The text generation paradigm for audio tasks has opened new possibilities for unified audio understanding. However, existing models face significant challenges in achieving a comprehensive understanding across diverse audio types, such as speech, general audio events, and music. Furthermore, their exclusive reliance on cross-entropy loss for alignment often falls short, as it treats all tokens equally and fails to account for redundant audio features, leading to weaker cross-modal alignment. To deal with the above challenges, this paper introduces U-SAM, an advanced audio language model that integrates specialized encoders for speech, audio, and music with a pre-trained large language model (LLM). U-SAM employs a Mixture of Experts (MoE) projector for task-aware feature fusion, dynamically routing and integrating the domain-specific encoder outputs. Additionally, U-SAM incorporates a Semantic-Aware Contrastive Loss Module, which explicitly identifies redundant audio features under language supervision and rectifies their semantic and spectral representations to enhance cross-modal alignment. Extensive experiments demonstrate that U-SAM consistently outperforms both specialized models and existing audio language models across multiple benchmarks. Moreover, it exhibits emergent capabilities on unseen tasks, showcasing its generalization potential. Code is available (https://github.com/Honee-W/U-SAM/).

[Arxiv](https://arxiv.org/abs/2505.13880)