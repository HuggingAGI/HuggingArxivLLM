# 自编码器在ASL数据集分词中的效果对比

发布时间：2025年01月12日

`LLM应用

**理由**：这篇论文主要讨论了基于生成式AI（依托大型语言模型）的多模态应用，特别是针对美国手语（ASL）图像数据集的编码器-解码器架构的开发与评估。虽然论文没有直接提到LLM的具体应用，但其研究背景和方法与生成式AI和多模态AI应用密切相关，因此归类为LLM应用。` `手语识别` `多模态AI`

> Comparison of Autoencoders for tokenization of ASL datasets

# 摘要

> 生成式AI，依托大型语言模型（LLMs），已在文本、音频、图像和视频领域掀起革命。本研究聚焦于美国手语（ASL）图像数据集的编码器-解码器架构开发与评估，该数据集涵盖29个手语类别，共计87,000张图像。我们对比了三种方法：前馈自编码器、卷积自编码器和扩散自编码器。扩散自编码器凭借其概率噪声建模和迭代去噪能力，表现最为出色，取得了最低的均方误差（MSE）和最高的平均意见得分（MOS）。卷积自编码器虽在空间特征提取上表现不俗，但缺乏扩散过程的稳健性；前馈自编码器则作为基线模型，在处理复杂图像数据时显得力不从心。通过客观与主观评估，扩散自编码器在高保真图像重建中的优势得以确认，凸显了其手语识别与生成等多模态AI应用的巨大潜力。本研究为设计鲁棒的编码器-解码器系统，推动多模态AI能力提升，提供了宝贵洞见。

> Generative AI, powered by large language models (LLMs), has revolutionized applications across text, audio, images, and video. This study focuses on developing and evaluating encoder-decoder architectures for the American Sign Language (ASL) image dataset, consisting of 87,000 images across 29 hand sign classes. Three approaches were compared: Feedforward Autoencoders, Convolutional Autoencoders, and Diffusion Autoencoders. The Diffusion Autoencoder outperformed the others, achieving the lowest mean squared error (MSE) and highest Mean Opinion Score (MOS) due to its probabilistic noise modeling and iterative denoising capabilities. The Convolutional Autoencoder demonstrated effective spatial feature extraction but lacked the robustness of the diffusion process, while the Feedforward Autoencoder served as a baseline with limitations in handling complex image data. Objective and subjective evaluations confirmed the superiority of the Diffusion Autoencoder for high-fidelity image reconstruction, emphasizing its potential in multimodal AI applications such as sign language recognition and generation. This work provides critical insights into designing robust encoder-decoder systems to advance multimodal AI capabilities.

[Arxiv](https://arxiv.org/abs/2501.06942)