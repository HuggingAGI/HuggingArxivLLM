# ToDMA：大模型驱动的基于Token域多访问机制，面向语义通信

发布时间：2025年05月16日

`LLM应用` `物联网`

> ToDMA: Large Model-Driven Token-Domain Multiple Access for Semantic Communications

# 摘要

> Token通信（TokCom）是一种新兴的生成式语义通信概念，通过利用上下文和多模态大型语言模型（MLLM）的标记处理来降低传输速率，其中标记作为跨模态的通用语义单元。本文提出了一种基于标记域的语义多访问方案——ToDMA，其中大量设备共享一个标记码本和一个调制码本，分别用于源编码和信道编码。具体来说，每个发射机首先对源信号进行标记化处理，然后将每个标记调制为一个码字。接收端通过压缩感知从叠加信号中检测活跃标记及其信道状态信息（CSI），并在多个时间槽上聚类与标记相关的CSI以重构源标记序列。当发生标记冲突时，部分活跃标记无法分配，重构序列中会出现空位。我们提出使用预训练的MLLM利用上下文预测被遮蔽的标记，从而缓解冲突。仿真结果表明，ToDMA框架在文本和图像传输中表现出色，相比不考虑上下文的正交通信方案，延迟显著降低；相比最先进的不考虑上下文的非正交通信方法，失真和感知质量更优。

> Token communications (TokCom) is an emerging generative semantic communication concept that reduces transmission rates by using context and multimodal large language model (MLLM)-based token processing, with tokens serving as universal semantic units across modalities. In this paper, we propose a semantic multiple access scheme in the token domain, referred to as token domain multiple access (ToDMA), where a large number of devices share a token codebook and a modulation codebook for source and channel coding, respectively. Specifically, each transmitter first tokenizes its source signal and modulate each token to a codeword. At the receiver, compressed sensing is employed first to detect active tokens and the corresponding channel state information (CSI) from the superposed signals. Then, the source token sequences are reconstructed by clustering the token-associated CSI across multiple time slots. In case of token collisions, some active tokens cannot be assigned and some positions in the reconstructed token sequences are empty. We propose to use pre-trained MLLMs to leverage the context, predict masked tokens, and thus mitigate token collisions. Simulation results demonstrate the effectiveness of the proposed ToDMA framework for both text and image transmission tasks, achieving significantly lower latency compared to context-unaware orthogonal communication schemes, while also delivering superior distortion and perceptual quality compared to state-of-the-art context-unaware non-orthogonal communication methods.

[Arxiv](https://arxiv.org/abs/2505.10946)