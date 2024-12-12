# “少即是多”：适用于大型语言模型高效微调的极端梯度提升排名 1 适配

发布时间：2024年10月25日

`LLM应用` `模型微调`

> Less is More: Extreme Gradient Boost Rank-1 Adaption for Efficient Finetuning of LLMs

# 摘要

> 微调大型语言模型（LLMs）已成为让预训练模型适配下游任务的关键技术。然而，LLMs 的庞大体量在计算复杂度和资源需求方面带来严峻挑战。低秩适应（LoRA）成为颇具前景的解决方案。但低秩适应的实际表现与理论最优值存在差距。在此项工作中，我们提出了极端梯度提升 LoRA（XGBLoRA），这一全新框架借助集成学习的力量来填补这一空缺。受梯度提升的启发，XGBLoRA 迭代学习并融合一系列 LoRA 适应来优化模型预测。它比标准的 LoRA 性能更优，同时具备秩 -1 适应的计算效率。我们进行了理论分析以展现我们方法的收敛性和最优性，并在众多自然语言处理任务上开展了广泛实验。结果显示，XGBLoRA 始终优于标准的 LoRA，在可训练参数大幅减少的情况下，实现了与全微调相媲美的性能。这项工作推动了 LLMs 的参数高效微调，为 LLMs 适配下游任务同时优化性能和效率提供了极具潜力的解决方案。

> Fine-tuning Large Language Models (LLMs) has become a crucial technique for adapting pre-trained models to downstream tasks. However, the enormous size of LLMs poses significant challenges in terms of computational complexity and resource requirements. Low-Rank Adaptation (LoRA) has emerged as a promising solution. However, there exists a gap between the practical performance of low-rank adaptations and its theoretical optimum. In this work, we propose eXtreme Gradient Boosting LoRA (XGBLoRA), a novel framework that bridges this gap by leveraging the power of ensemble learning. Inspired by gradient boosting, XGBLoRA iteratively learns and merges a sequence of LoRA adaptations to refine model predictions. It achieves better performance than the standard LoRA, while enjoying the computational efficiency of rank-1 adaptations. We provide theoretical analysis to show the convergence and optimality of our approach, and conduct extensive experiments on a range of natural language processing tasks. The results demonstrate that XGBLoRA consistently outperforms standard LoRA and achieves performance comparable to full fine-tuning with significantly fewer trainable parameters. This work advances parameter-efficient fine-tuning for LLMs, and offers a promising solution for adapting LLMs to downstream tasks while optimizing performance and efficiency.

[Arxiv](https://arxiv.org/abs/2410.19694)