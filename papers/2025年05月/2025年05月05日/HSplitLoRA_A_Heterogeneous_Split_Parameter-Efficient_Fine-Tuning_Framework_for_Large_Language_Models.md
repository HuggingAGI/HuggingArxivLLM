# HSplitLoRA：用于大型语言模型的异构分割参数高效微调框架

发布时间：2025年05月05日

`LLM应用

理由：这篇论文讨论了如何在联邦学习框架下高效微调大型语言模型，特别是针对异构客户端设备的计算资源限制。它提出了一种名为HSplitLoRA的框架，结合拆分学习和低秩适配技术，以优化LLMs的微调过程。这一工作属于LLM应用领域，因为它专注于如何在实际应用中优化LLMs的使用和微调，而不是研究LLM本身的理论或机制。` `人工智能` `机器学习`

> HSplitLoRA: A Heterogeneous Split Parameter-Efficient Fine-Tuning Framework for Large Language Models

# 摘要

> 大型语言模型 (LLMs) 近期取得的显著突破不仅深刻改变了自然语言处理领域，更拓展至其他诸多领域。然而，由于模型参数规模庞大，利用私有数据对这些模型进行微调以适应多样化的下游任务已经成为主流。虽然联邦学习 (FL) 为在不共享原始数据的情况下微调 LLMs 提供了有前景的解决方案，但其巨大的计算成本阻碍了这一技术的普及。此外，在实际应用中，私有客户端设备通常具备异构计算资源，进一步增加了 LLM 微调的复杂性。为应对这些挑战，我们提出了一种名为 HSplitLoRA 的异构参数高效微调 (PEFT) 框架，该框架基于拆分学习 (SL) 和低秩适配 (LoRA) 微调技术，能够在异构客户端设备上高效微调 LLMs。HSplitLoRA 首先根据权重对 LLM 训练的贡献程度，识别出重要的权重。然后，它会根据所选权重动态配置 LoRA 适配器的分解秩，并根据客户端设备不同的计算预算确定模型的拆分点。最后，设计了一种无噪声的适配器聚合机制，支持异构适配器的聚合而不引入噪声。大量实验表明，HSplitLoRA 在训练准确性和收敛速度方面均超越了现有的最先进基准。

> Recently, large language models (LLMs) have achieved remarkable breakthroughs, revolutionizing the natural language processing domain and beyond. Due to immense parameter sizes, fine-tuning these models with private data for diverse downstream tasks has become mainstream. Though federated learning (FL) offers a promising solution for fine-tuning LLMs without sharing raw data, substantial computing costs hinder its democratization. Moreover, in real-world scenarios, private client devices often possess heterogeneous computing resources, further complicating LLM fine-tuning. To combat these challenges, we propose HSplitLoRA, a heterogeneous parameter-efficient fine-tuning (PEFT) framework built on split learning (SL) and low-rank adaptation (LoRA) fine-tuning, for efficiently fine-tuning LLMs on heterogeneous client devices. HSplitLoRA first identifies important weights based on their contributions to LLM training. It then dynamically configures the decomposition ranks of LoRA adapters for selected weights and determines the model split point according to varying computing budgets of client devices. Finally, a noise-free adapter aggregation mechanism is devised to support heterogeneous adapter aggregation without introducing noise. Extensive experiments demonstrate that HSplitLoRA outperforms state-of-the-art benchmarks in training accuracy and convergence speed.

[Arxiv](https://arxiv.org/abs/2505.02795)