# DeCAF：通过去中心化共识与分解实现基础模型的低秩适配

发布时间：2025年05月27日

`LLM理论` `机器学习`

> DeCAF: Decentralized Consensus-And-Factorization for Low-Rank Adaptation of Foundation Models

# 摘要

> 低秩适配（LoRA）已成为训练视觉语言模型（VLMs）和大型语言模型（LLMs）中最有效且计算可行的微调方法之一。通过冻结预训练权重并注入可训练的低秩矩阵，LoRA实现了对基础模型的高效学习，即使在边缘设备上也能轻松实现。然而，去中心化环境中的LoRA研究仍不充分，尤其是其理论基础，因缺乏平滑性保证和模型共识干扰（下文正式定义）而未被充分探索。本研究通过确保梯度平滑，将去中心化LoRA（DLoRA）的收敛速率提升至与去中心化SGD相当。我们还引入了DeCAF，一种结合DLoRA与基于截断奇异值分解（TSVD）的矩阵分解的新型算法，以解决共识干扰问题。理论分析表明，TSVD的近似误差是有界的，且随着秩的增加，DLoRA与DeCAF之间的共识差异消失，从而实现了DeCAF的匹配收敛速率。在视觉/语言任务上的广泛实验表明，我们的算法在IID和非IID数据分布下，均超越了本地训练和联邦学习的性能。

> Low-Rank Adaptation (LoRA) has emerged as one of the most effective, computationally tractable fine-tuning approaches for training Vision-Language Models (VLMs) and Large Language Models (LLMs). LoRA accomplishes this by freezing the pre-trained model weights and injecting trainable low-rank matrices, allowing for efficient learning of these foundation models even on edge devices. However, LoRA in decentralized settings still remains under explored, particularly for the theoretical underpinnings due to the lack of smoothness guarantee and model consensus interference (defined formally below). This work improves the convergence rate of decentralized LoRA (DLoRA) to match the rate of decentralized SGD by ensuring gradient smoothness. We also introduce DeCAF, a novel algorithm integrating DLoRA with truncated singular value decomposition (TSVD)-based matrix factorization to resolve consensus interference. Theoretical analysis shows TSVD's approximation error is bounded and consensus differences between DLoRA and DeCAF vanish as rank increases, yielding DeCAF's matching convergence rate. Extensive experiments across vision/language tasks demonstrate our algorithms outperform local training and rivals federated learning under both IID and non-IID data distributions.

[Arxiv](https://arxiv.org/abs/2505.21382)