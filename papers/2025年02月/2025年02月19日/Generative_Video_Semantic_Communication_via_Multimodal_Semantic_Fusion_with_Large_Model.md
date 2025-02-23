# 基于大模型的多模态语义融合生成视频语义通信

发布时间：2025年02月19日

`LLM应用` `人工智能`

> Generative Video Semantic Communication via Multimodal Semantic Fusion with Large Model

# 摘要

> 尽管基于香农理论的传统通信技术取得了显著进展，但面对6G沉浸式通信需求，这些方法在复杂传输条件下仍显力不从心。随着生成式人工智能（GenAI）的快速发展，利用高层次语义信息重建视频成为可能。本文提出了一种可扩展的生成视频语义通信框架，通过提取和传输语义信息实现高质量视频重建。具体来说，在发送端，我们从源视频中提取描述和其他条件信号（如第一帧、草图等），分别作为文本和结构化语义；在接收端，利用基于扩散的GenAI大模型融合多模态语义以实现视频重建。仿真结果表明，即使在超低信道带宽比（CBR）下，我们的方案仍能有效捕获语义信息，在不同信噪比条件下实现符合人类感知的视频重建。特别值得注意的是，提出的“第一帧+描述”方案在CBR=0.0057且SNR>0 dB时，CLIP评分始终保持在0.92以上，这充分证明了其在低SNR条件下的卓越鲁棒性能。

> Despite significant advancements in traditional syntactic communications based on Shannon's theory, these methods struggle to meet the requirements of 6G immersive communications, especially under challenging transmission conditions. With the development of generative artificial intelligence (GenAI), progress has been made in reconstructing videos using high-level semantic information. In this paper, we propose a scalable generative video semantic communication framework that extracts and transmits semantic information to achieve high-quality video reconstruction. Specifically, at the transmitter, description and other condition signals (e.g., first frame, sketches, etc.) are extracted from the source video, functioning as text and structural semantics, respectively. At the receiver, the diffusion-based GenAI large models are utilized to fuse the semantics of the multiple modalities for reconstructing the video. Simulation results demonstrate that, at an ultra-low channel bandwidth ratio (CBR), our scheme effectively captures semantic information to reconstruct videos aligned with human perception under different signal-to-noise ratios. Notably, the proposed ``First Frame+Desc." scheme consistently achieves CLIP score exceeding 0.92 at CBR = 0.0057 for SNR > 0 dB. This demonstrates its robust performance even under low SNR conditions.

[Arxiv](https://arxiv.org/abs/2502.13838)