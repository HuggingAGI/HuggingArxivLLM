# SoundSpring: 双功能掩码语言建模的容损音频收发器

发布时间：2025年01月22日

`LLM应用

理由：该论文摘要提到“充分利用了大型语言（基础）模型的强大上下文预测能力”，并讨论了如何将大型语言模型应用于音频通信系统中，以提高音频压缩效率和传输错误弹性。这表明该研究是将大型语言模型应用于特定领域（音频通信）的实际问题，因此属于“LLM应用”分类。` `音频通信` `数字通信`

> SoundSpring: Loss-Resilient Audio Transceiver with Dual-Functional Masked Language Modeling

# 摘要

> 本文提出了一种名为“SoundSpring”的前沿错误弹性音频收发器，它融合了联合源信道编码（JSCC）的鲁棒性优势，同时兼容现有数字通信系统。与近期通过神经网络直接将音频信号映射为模拟信道输入符号的深度JSCC收发器不同，SoundSpring采用分层架构，将音频压缩与数字编码传输分离，并充分利用了大型语言（基础）模型的强大上下文预测能力。结合因果顺序掩码学习策略，我们的单一模型在潜在特征域上运行，兼具双重功能：作为发射端的高效音频压缩器和接收端的丢包隐藏机制。通过联合优化音频压缩效率和传输错误弹性，我们证明了掩码学习的语言模型是强大的上下文预测器，而我们的双重功能压缩与隐藏框架为基础语言模型在音频通信中的应用提供了新视角。大量实验表明，SoundSpring在信号保真度和感知质量评分上显著优于现有音频传输系统。这些发现不仅推动了SoundSpring在基于学习的音频通信系统中的实际应用，还为未来音频语义收发器的发展提供了灵感。

> In this paper, we propose "SoundSpring", a cutting-edge error-resilient audio transceiver that marries the robustness benefits of joint source-channel coding (JSCC) while also being compatible with current digital communication systems. Unlike recent deep JSCC transceivers, which learn to directly map audio signals to analog channel-input symbols via neural networks, our SoundSpring adopts the layered architecture that delineates audio compression from digital coded transmission, but it sufficiently exploits the impressive in-context predictive capabilities of large language (foundation) models. Integrated with the casual-order mask learning strategy, our single model operates on the latent feature domain and serve dual-functionalities: as efficient audio compressors at the transmitter and as effective mechanisms for packet loss concealment at the receiver. By jointly optimizing towards both audio compression efficiency and transmission error resiliency, we show that mask-learned language models are indeed powerful contextual predictors, and our dual-functional compression and concealment framework offers fresh perspectives on the application of foundation language models in audio communication. Through extensive experimental evaluations, we establish that SoundSpring apparently outperforms contemporary audio transmission systems in terms of signal fidelity metrics and perceptual quality scores. These new findings not only advocate for the practical deployment of SoundSpring in learning-based audio communication systems but also inspire the development of future audio semantic transceivers.

[Arxiv](https://arxiv.org/abs/2501.12696)