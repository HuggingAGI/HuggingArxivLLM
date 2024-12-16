# Llama 3 与 MoE 相遇：高效的升级改造

发布时间：2024年12月13日

`LLM应用` `语言模型` `模型训练`

> Llama 3 Meets MoE: Efficient Upcycling

# 摘要

> 扩展大型语言模型（LLMs）能显著提升性能，可计算成本高昂。混合专家（MoE）模型是高效之选，能增加容量，且计算需求不会同比上升。然而，从零开始训练 MoE 模型存在过拟合和路由不稳定等难题。我们给出了一种借助预训练密集检查点的高效训练方案，从 Llama 3-8B 训练一个 8 专家 Top-2 MoE 模型，其计算量不足典型预训练的 1％。我们的方法提升了学术基准的下游性能，在 MMLU 上的 0-shot 准确率提高 2％，训练时使用我们的框架能达到 46.8％的模型 FLOPs 利用率（MFU）。我们还在 NeMo 中集成了在线升级，以无缝使用预训练权重，助力高容量 MoE 模型的低成本高效开发。

> Scaling large language models (LLMs) significantly improves performance but comes with prohibitive computational costs. Mixture-of-Experts (MoE) models offer an efficient alternative, increasing capacity without a proportional rise in compute requirements. However, training MoE models from scratch poses challenges like overfitting and routing instability. We present an efficient training recipe leveraging pre-trained dense checkpoints, training an 8-Expert Top-2 MoE model from Llama 3-8B with less than $1\%$ of typical pre-training compute. Our approach enhances downstream performance on academic benchmarks, achieving a $\textbf{2%}$ improvement in 0-shot accuracy on MMLU, while reaching a Model FLOPs Utilization (MFU) of $\textbf{46.8%}$ during training using our framework. We also integrate online upcycling in NeMo for seamless use of pre-trained weights, enabling cost-effective development of high-capacity MoE models.

[Arxiv](https://arxiv.org/abs/2412.09952)