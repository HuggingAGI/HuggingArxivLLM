# 旅程至关重要：预训练中的平均参数量统一了稀疏与密集的缩放规律

发布时间：2025年01月21日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的稀疏预训练技术，研究了剪枝与预训练的结合，并提出了改进的Chinchilla缩放定律。这些内容属于对LLM的理论研究和优化方法的探索，因此归类为LLM理论。` `人工智能` `机器学习`

> The Journey Matters: Average Parameter Count over Pre-training Unifies Sparse and Dense Scaling Laws

# 摘要

> 剪枝技术通过移除神经网络中的冗余参数，为应对大型语言模型（LLMs）日益增长的计算需求提供了有效解决方案。与常见的训练后剪枝不同，稀疏预训练将剪枝与预训练合二为一，简化了流程。本研究首次系统性地探索了LLMs的最佳稀疏预训练配置，通过分析80种不同稀疏度和训练时长的剪枝方案，发现从总训练计算的25%开始剪枝，至75%结束，可达到接近最优的评估损失。这一发现为LLMs的高效稀疏预训练提供了重要指导。此外，我们提出了一种改进的Chinchilla缩放定律，采用预训练期间的平均参数数量进行建模。实证与理论验证表明，该定律能准确预测稀疏与密集预训练LLMs的评估损失，统一了不同预训练范式下的缩放规律。研究显示，稀疏预训练在相同计算预算下能达到与密集预训练相当的模型质量，同时显著减小模型规模，为推理阶段带来巨大的计算节省潜力。

> Pruning eliminates unnecessary parameters in neural networks; it offers a promising solution to the growing computational demands of large language models (LLMs). While many focus on post-training pruning, sparse pre-training--which combines pruning and pre-training into a single phase--provides a simpler alternative. In this work, we present the first systematic exploration of optimal sparse pre-training configurations for LLMs through an examination of 80 unique pruning schedules across different sparsity levels and training durations. We find that initiating pruning at 25% of total training compute and concluding at 75% achieves near-optimal final evaluation loss. These findings provide valuable insights for efficient and effective sparse pre-training of LLMs. Furthermore, we propose a new scaling law that modifies the Chinchilla scaling law to use the average parameter count over pre-training. Through empirical and theoretical validation, we demonstrate that this modified scaling law accurately models evaluation loss for both sparsely and densely pre-trained LLMs, unifying scaling laws across pre-training paradigms. Our findings indicate that while sparse pre-training achieves the same final model quality as dense pre-training for equivalent compute budgets, it provides substantial benefits through reduced model size, enabling significant potential computational savings during inference.

[Arxiv](https://arxiv.org/abs/2501.12486)