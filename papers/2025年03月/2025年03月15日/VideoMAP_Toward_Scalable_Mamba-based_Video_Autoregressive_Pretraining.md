# VideoMAP：迈向可扩展的基于Mamba的视频自回归预训练

发布时间：2025年03月15日

`LLM应用

理由：这篇论文主要探讨了VideoMAP作为多模态大型语言模型的视觉编码器的应用，属于将大型语言模型应用于视觉处理领域的具体实践。` `视频处理` `计算机视觉`

> VideoMAP: Toward Scalable Mamba-based Video Autoregressive Pretraining

# 摘要

> 基于Mamba的视频理解架构虽展现了令人鼓舞的计算效率和竞争力，但过拟合问题限制了其扩展能力。为解决这一难题，我们提出了VideoMAP——一个创新的混合Mamba-Transformer框架，采用4:1的Mamba到Transformer比例，有效平衡计算成本与模型容量。结合我们提出的逐帧掩蔽自回归预训练策略，VideoMAP在扩展至更大模型时实现了显著性能提升。此外，VideoMAP展现了卓越的样本效率，即使在训练数据较少的情况下，也远超现有方法。实验结果表明，VideoMAP在Kinetics-400、Something-Something V2、Breakfast和COIN等数据集上均超越现有模型。值得注意的是，VideoMAP还可作为多模态大型语言模型的视觉编码器，具备减少内存使用并支持处理更长视频序列的能力。项目代码已开源，地址为https://github.com/yunzeliu/MAP

> Recent Mamba-based architectures for video understanding demonstrate promising computational efficiency and competitive performance, yet struggle with overfitting issues that hinder their scalability. To overcome this challenge, we introduce VideoMAP, a Hybrid Mamba-Transformer framework featuring a novel pre-training approach. VideoMAP uses a 4:1 Mamba-to-Transformer ratio, effectively balancing computational cost and model capacity. This architecture, combined with our proposed frame-wise masked autoregressive pre-training strategy, delivers significant performance gains when scaling to larger models. Additionally, VideoMAP exhibits impressive sample efficiency, significantly outperforming existing methods with less training data. Experiments show that VideoMAP outperforms existing models across various datasets, including Kinetics-400, Something-Something V2, Breakfast, and COIN. Furthermore, we demonstrate the potential of VideoMAP as a visual encoder for multimodal large language models, highlighting its ability to reduce memory usage and enable the processing of longer video sequences. The code is open-source at https://github.com/yunzeliu/MAP

[Arxiv](https://arxiv.org/abs/2503.12332)