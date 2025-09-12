# 有限标量量化赋能低比特率下具备冗余性与传输稳健性的神经音频压缩

发布时间：2025年09月11日

`其他` `媒体与娱乐`

> Finite Scalar Quantization Enables Redundant and Transmission-Robust Neural Audio Compression at Low Bit-rates

# 摘要

> 神经音频编解码器（NACs）凭借出色的率失真性能，以及作为音频生成的离散特征表示与大型语言模型（LLMs）的良好兼容性，在语音处理任务中的应用日益广泛。现有编解码器多依赖残差矢量量化（RVQ），而有限标量量化（FSQ）作为新兴替代方案，不仅简化了训练过程，还原生支持单码本。我们提出了基于FSQ的神经音频编解码器NeuCodec，并发现FSQ编码具有内置冗余，使其生成的编码在噪声信道传输中表现出强鲁棒性。首先，编码器蒸馏实验表明：使用相同量化器和解码器时，两个不同编码器可将相同音频编码为差异显著的码序列，且重建质量相当。其次，通过模拟噪声信道传输并对比RVQ与FSQ编解码器性能，证实FSQ的比特级扰动鲁棒性显著更优。

> Neural Audio Codecs (NACs) have become increasingly adopted in speech processing tasks due to their excellent rate-distortion performance and compatibility with Large Language Models (LLMs) as discrete feature representations for audio generation. While most existing codecs rely on Residual Vector Quantization (RVQ), Finite Scalar Quantization (FSQ) has recently emerged as a compelling alternative that simplifies training and natively supports single codebooks. We introduce NeuCodec, an FSQ-based NAC, and show that FSQ encodes baked-in redundancy which produces an encoding which is robust when transmitted through noisy channels. First, through an encoder distillation experiment, we show that two different encoders can learn to encode identical audio into vastly different code sequences whilst maintaining comparable reconstruction quality with the same quantizer and decoder. Second, we demonstrate that FSQ has vastly superior bit-level perturbation robustness by comparing the performance of RVQ and FSQ codecs when simulating the transmission of code sequences through a noisy channel.

[Arxiv](https://arxiv.org/abs/2509.09550)