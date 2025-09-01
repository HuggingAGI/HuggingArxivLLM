# MIDAS：基于实时自回归视频生成的多模态交互式数字人类合成

发布时间：2025年08月28日

`LLM应用` `媒体与娱乐`

> MIDAS: Multimodal Interactive Digital-humAn Synthesis via Real-time Autoregressive Video Generation

# 摘要

> 近年来，交互式数字人视频生成备受关注，成果斐然。然而，现有方法在构建能实时响应多种输入信号的实用系统时仍面临挑战——计算成本高昂且可控性有限。为此，我们提出一种自回归视频生成框架，可通过流式方式实现交互式多模态控制与低延迟外推。该框架仅需对标准大型语言模型（LLM）稍作调整，即可接收音频、姿态、文本等多模态条件编码，并输出空间与语义连贯的表示，以指导扩散头的去噪过程。为支撑这一框架，我们从多源构建了约2万小时的大规模对话数据集，为训练提供丰富的对话场景。我们还引入深度压缩自编码器，压缩比最高达【数学公式】，有效缓解了自回归模型的长序列推理压力。在双向对话、多语言人物合成及交互式世界模型等任务上的大量实验表明，我们的方法在低延迟、高效率及细粒度多模态可控性方面优势显著。

> Recently, interactive digital human video generation has attracted widespread attention and achieved remarkable progress. However, building such a practical system that can interact with diverse input signals in real time remains challenging to existing methods, which often struggle with heavy computational cost and limited controllability. In this work, we introduce an autoregressive video generation framework that enables interactive multimodal control and low-latency extrapolation in a streaming manner. With minimal modifications to a standard large language model (LLM), our framework accepts multimodal condition encodings including audio, pose, and text, and outputs spatially and semantically coherent representations to guide the denoising process of a diffusion head. To support this, we construct a large-scale dialogue dataset of approximately 20,000 hours from multiple sources, providing rich conversational scenarios for training. We further introduce a deep compression autoencoder with up to 64$\times$ reduction ratio, which effectively alleviates the long-horizon inference burden of the autoregressive model. Extensive experiments on duplex conversation, multilingual human synthesis, and interactive world model highlight the advantages of our approach in low latency, high efficiency, and fine-grained multimodal controllability.

[Arxiv](https://arxiv.org/abs/2508.19320)