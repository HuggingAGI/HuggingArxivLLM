# Saten：面向大型语言模型后训练压缩的稀疏增强张量网络

发布时间：2025年05月20日

`LLM应用` `边缘计算`

> Saten: Sparse Augmented Tensor Networks for Post-Training Compression of Large Language Models

# 摘要

> 在资源受限设备上实现大型语言模型 (LLMs) 的高效部署至关重要。低秩张量压缩技术，如张量列车 (TT) 网络，已在超参数化神经网络领域得到广泛应用。然而，由于预训练 LLM 的高秩特性和缺乏预训练数据访问，将其应用于压缩预训练大型语言模型以进行下游任务仍具挑战。本研究聚焦于微调过程中的低秩张量化 LLMs，提出稀疏增强张量网络 (Saten) 以提升性能。Saten 框架实现了全模型压缩，实验结果表明其在张量化语言模型中显著提升了准确性和压缩效率，达到最新技术水平。

> The efficient implementation of large language models (LLMs) is crucial for deployment on resource-constrained devices. Low-rank tensor compression techniques, such as tensor-train (TT) networks, have been widely studied for over-parameterized neural networks. However, their applications to compress pre-trained large language models (LLMs) for downstream tasks (post-training) remains challenging due to the high-rank nature of pre-trained LLMs and the lack of access to pretraining data. In this study, we investigate low-rank tensorized LLMs during fine-tuning and propose sparse augmented tensor networks (Saten) to enhance their performance. The proposed Saten framework enables full model compression. Experimental results demonstrate that Saten enhances both accuracy and compression efficiency in tensorized language models, achieving state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2505.14871)