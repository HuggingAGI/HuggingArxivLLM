# # 利用稀疏自动编码器去噪概念向量，优化语言模型控制能力

发布时间：2025年05月20日

`LLM应用` `人工智能`

> Denoising Concept Vectors with Sparse Autoencoders for Improved Language Model Steering

# 摘要

> 线性概念向量在引导大型语言模型（LLMs）方面表现出色。然而，现有的方法如线性探测和均值差分法从LLM的隐藏层表示中提取这些向量时，多样化的数据引入了噪声（即无关特征），影响了引导的鲁棒性。为解决此问题，我们提出稀疏自编码去噪概念向量（SDCV），利用稀疏自编码器从隐藏层表示中过滤噪声特征。当应用于线性探测和均值差分法时，我们的方法显著提高了它们的引导成功率。我们通过反事实实验和特征可视化验证了噪声假说。

> Linear Concept Vectors have proven effective for steering large language models (LLMs). While existing approaches like linear probing and difference-in-means derive these vectors from LLM hidden representations, diverse data introduces noises (i.e., irrelevant features) that challenge steering robustness. To address this, we propose Sparse Autoencoder-Denoised Concept Vectors (SDCV), which uses Sparse Autoencoders to filter out noisy features from hidden representations. When applied to linear probing and difference-in-means, our method improves their steering success rates. We validate our noise hypothesis through counterfactual experiments and feature visualizations.

[Arxiv](https://arxiv.org/abs/2505.15038)