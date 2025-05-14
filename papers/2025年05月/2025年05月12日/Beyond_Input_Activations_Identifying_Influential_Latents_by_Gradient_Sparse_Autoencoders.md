# # 超越输入激活：梯度稀疏自动编码器识别关键潜在变量

发布时间：2025年05月12日

`LLM理论` `人工智能` `机器学习`

> Beyond Input Activations: Identifying Influential Latents by Gradient Sparse Autoencoders

# 摘要

> 稀疏自编码器（SAEs）作为一种新兴工具，能够有效解释和引导大型语言模型（LLMs）的内部表示。然而，传统方法在分析SAEs时，往往仅关注输入侧的激活信息，而忽略了潜在特征与模型输出之间的因果关系。本研究基于两个核心假设展开：首先，被激活的潜在特征对模型输出的构建并非同等重要；其次，仅当潜在特征具有显著的因果影响力时，才能有效用于模型引导。为验证这些假设，我们提出了一种名为梯度稀疏自编码器（GradSAE）的创新方法。该方法通过引入输出侧梯度信息，能够精准识别对模型输出影响最大的潜在特征。

> Sparse Autoencoders (SAEs) have recently emerged as powerful tools for interpreting and steering the internal representations of large language models (LLMs). However, conventional approaches to analyzing SAEs typically rely solely on input-side activations, without considering the causal influence between each latent feature and the model's output. This work is built on two key hypotheses: (1) activated latents do not contribute equally to the construction of the model's output, and (2) only latents with high causal influence are effective for model steering. To validate these hypotheses, we propose Gradient Sparse Autoencoder (GradSAE), a simple yet effective method that identifies the most influential latents by incorporating output-side gradient information.

[Arxiv](https://arxiv.org/abs/2505.08080)