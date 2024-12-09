# 连续的语音标记让大型语言模型成为强劲的多模态学习者

发布时间：2024年12月06日

`LLM应用` `语音交互` `多模态模型`

> Continuous Speech Tokens Makes LLMs Robust Multi-Modality Learners

# 摘要

> 近期，类似 GPT-4o 的多模态模型取得了显著进展，在直接语音到语音对话方面表现出色，具备实时语音交互体验和强大的语音理解能力。然而，当下的研究侧重于离散语音标记与离散文本标记的对齐以进行语言建模，这依赖于带有残差连接或独立组标记的音频编解码器，此类编解码器通常借助大规模且多样化的数据集训练，以确保离散语音代码对不同领域、噪声、风格的数据重建有良好的表征，以及拥有精心设计的编解码器量化器和编解码器架构用于离散标记语言建模。本文引入了 Flow-Omni，这是一种基于连续语音标记的类似 GPT-4o 的模型，能够实现实时语音交互和低流式延迟。具体来说，其一，我们不单使用交叉熵损失，而是将流匹配损失与预训练的自回归 LLM 以及一个小型 MLP 网络相结合，从语音提示预测连续值语音标记的概率分布。其二，我们将连续语音标记融入 Flow-Omni 多模态训练，从而与离散文本标记共同达成强大的语音到语音性能。实验表明，相较于离散文本和语音的多模态训练及其变体，连续语音标记避免了 LLM 中离散语音代码表示损失的固有缺陷，从而缓解了鲁棒性问题。

> Recent advances in GPT-4o like multi-modality models have demonstrated remarkable progress for direct speech-to-speech conversation, with real-time speech interaction experience and strong speech understanding ability. However, current research focuses on discrete speech tokens to align with discrete text tokens for language modelling, which depends on an audio codec with residual connections or independent group tokens, such a codec usually leverages large scale and diverse datasets training to ensure that the discrete speech codes have good representation for varied domain, noise, style data reconstruction as well as a well-designed codec quantizer and encoder-decoder architecture for discrete token language modelling. This paper introduces Flow-Omni, a continuous speech token based GPT-4o like model, capable of real-time speech interaction and low streaming latency. Specifically, first, instead of cross-entropy loss only, we combine flow matching loss with a pretrained autoregressive LLM and a small MLP network to predict the probability distribution of the continuous-valued speech tokens from speech prompt. second, we incorporated the continuous speech tokens to Flow-Omni multi-modality training, thereby achieving robust speech-to-speech performance with discrete text tokens and continuous speech tokens together. Experiments demonstrate that, compared to discrete text and speech multi-modality training and its variants, the continuous speech tokens mitigate robustness issues by avoiding the inherent flaws of discrete speech code's representation loss for LLM.

[Arxiv](https://arxiv.org/abs/2412.04917)