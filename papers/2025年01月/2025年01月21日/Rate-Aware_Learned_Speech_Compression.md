# 速率感知的智能语音压缩

发布时间：2025年01月21日

`其他

理由：这篇论文主要讨论的是语音压缩技术，特别是基于深度学习的神经语音编解码器的改进。虽然提到了大型语言模型（LLM）的发展背景，但论文的核心内容并不直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `语音处理`

> Rate-Aware Learned Speech Compression

# 摘要

> 实时通信和大型语言模型的迅猛发展使得语音压缩变得尤为重要。基于深度学习的神经语音编解码器在率失真（RD）性能上已超越传统信号级编解码器。通常，这些神经编解码器采用编码器-量化器-解码器架构，先将音频转换为潜在特征表示，再转为离散标记。然而，该架构存在两大缺陷导致RD性能不足：（1）量化器性能欠佳，训练过程复杂，且易出现代码本崩溃；（2）编码器和解码器的表示能力有限，难以满足多比特率下的特征需求。本文提出了一种速率感知的学习语音压缩方案，用先进的通道熵模型替代量化器，以提升RD性能、简化训练并避免代码本崩溃。我们采用多尺度卷积和线性注意力混合块，增强编码器和解码器的表示能力与灵活性。实验结果显示，该方法在RD性能上达到业界领先水平，平均节省53.51%的BD-Rate比特率，并实现0.26 BD-VisQol和0.44 BD-PESQ的增益。

> The rapid rise of real-time communication and large language models has significantly increased the importance of speech compression. Deep learning-based neural speech codecs have outperformed traditional signal-level speech codecs in terms of rate-distortion (RD) performance. Typically, these neural codecs employ an encoder-quantizer-decoder architecture, where audio is first converted into latent code feature representations and then into discrete tokens. However, this architecture exhibits insufficient RD performance due to two main drawbacks: (1) the inadequate performance of the quantizer, challenging training processes, and issues such as codebook collapse; (2) the limited representational capacity of the encoder and decoder, making it difficult to meet feature representation requirements across various bitrates. In this paper, we propose a rate-aware learned speech compression scheme that replaces the quantizer with an advanced channel-wise entropy model to improve RD performance, simplify training, and avoid codebook collapse. We employ multi-scale convolution and linear attention mixture blocks to enhance the representational capacity and flexibility of the encoder and decoder. Experimental results demonstrate that the proposed method achieves state-of-the-art RD performance, obtaining 53.51% BD-Rate bitrate saving in average, and achieves 0.26 BD-VisQol and 0.44 BD-PESQ gains.

[Arxiv](https://arxiv.org/abs/2501.11999)