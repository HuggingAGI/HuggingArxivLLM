# LLaVE: 集成Hardness-Weighted对比学习的大型语言与视觉嵌入模型

发布时间：2025年03月04日

`LLM应用` `人工智能` `信息检索`

> LLaVE: Large Language and Vision Embedding Models with Hardness-Weighted Contrastive Learning

# 摘要

> 通用的多模态嵌入模型在图像文本检索、多模态 RAG 以及多模态聚类等任务中发挥着重要作用。然而，我们的研究发现，现有基于 LMM 并采用标准 InfoNCE 损失训练的嵌入模型在区分困难负样本对时存在显著挑战，主要因为正负样本对的相似度分布高度重叠。为解决这一问题，我们提出了一种简单而有效的框架，该框架能够根据负样本对的判别难度动态优化嵌入模型的表征学习能力。在这一框架下，我们开发了 LLaVE 系列模型，并在涵盖 4 个元任务和 36 个数据集的 MMEB 基准测试中进行了全面评估。实验结果表明，LLaVE 不仅达到了目前最优（SOTA）性能，还展现了出色的可扩展性和效率。具体而言，LLaVE-2B 的表现超越了之前的 7B SOTA 模型，而 LLaVE-7B 更是实现了 6.2 个百分点的性能提升。尽管 LLaVE 是基于图像文本数据进行训练，但它能够以零样本的方式成功推广至文本视频检索任务并取得优异表现，充分展现了其在迁移至其他嵌入任务方面的巨大潜力。

> Universal multimodal embedding models play a critical role in tasks such as interleaved image-text retrieval, multimodal RAG, and multimodal clustering. However, our empirical results indicate that existing LMM-based embedding models trained with the standard InfoNCE loss exhibit a high degree of overlap in similarity distribution between positive and negative pairs, making it challenging to distinguish hard negative pairs effectively. To deal with this issue, we propose a simple yet effective framework that dynamically improves the embedding model's representation learning for negative pairs based on their discriminative difficulty. Within this framework, we train a series of models, named LLaVE, and evaluate them on the MMEB benchmark, which covers 4 meta-tasks and 36 datasets. Experimental results show that LLaVE establishes stronger baselines that achieve state-of-the-art (SOTA) performance while demonstrating strong scalability and efficiency. Specifically, LLaVE-2B surpasses the previous SOTA 7B models, while LLaVE-7B achieves a further performance improvement of 6.2 points. Although LLaVE is trained on image-text data, it can generalize to text-video retrieval tasks in a zero-shot manner and achieve strong performance, demonstrating its remarkable potential for transfer to other embedding tasks.

[Arxiv](https://arxiv.org/abs/2503.04812)