# # 动态上下文导向分解方法
本研究提出一种动态上下文导向分解方法，旨在实现任务感知的低秩适应，同时减少遗忘并加快收敛速度。

发布时间：2025年06月16日

`LLM理论` `模型适配`

> Dynamic Context-oriented Decomposition for Task-aware Low-rank Adaptation with Less Forgetting and Faster Convergence

# 摘要

> 传统低秩适配方法在构建适配器时忽略了数据上下文，导致微调效果欠佳，并且严重遗忘模型中预训练的知识。本文提出了一种面向上下文的分解适配方法（CorDA），该方法以任务感知的方式初始化适配器。具体而言，我们开发了面向上下文的奇异值分解技术，其中我们通过从目标任务中采样数据，收集每个线性层输入激活的协方差矩阵，并对权重矩阵及其对应协方差矩阵的乘积进行奇异值分解。通过这种方式，任务特定的能力被压缩到主成分中。得益于任务感知能力，我们的方法支持两种可选的适配模式：知识保留模式（KPM）和指令预览模式（IPM），允许用户选择冻结主成分以保留相关知识，或对其进行调整以更好地学习新任务。我们进一步开发了CorDA++，通过引入一个反映任务特定主成分紧凑性的指标，并基于该指标引入动态协方差选择和动态秩分配策略。这两个策略分别为每一层提供最具代表性的协方差矩阵和适当的秩分配。实验结果表明，CorDA++显著优于CorDA。在KPM模式下，CorDA++不仅在微调性能上超越LoRA，还能有效缓解大型语言模型和视觉语言模型中预训练知识的遗忘问题。对于IPM模式，我们的方法展现出更快的收敛速度，例如比QLoRA快4.5倍，并在各种场景下提升适配性能，超越强基线方法。我们的方法已集成到Hugging Face开发的PEFT库中。

> Conventional low-rank adaptation methods build adapters without considering data context, leading to sub-optimal fine-tuning performance and severe forgetting of inherent world knowledge. In this paper, we propose context-oriented decomposition adaptation (CorDA), a novel method that initializes adapters in a task-aware manner. Concretely, we develop context-oriented singular value decomposition, where we collect covariance matrices of input activations for each linear layer using sampled data from the target task, and apply SVD to the product of weight matrix and its corresponding covariance matrix. By doing so, the task-specific capability is compacted into the principal components. Thanks to the task awareness, our method enables two optional adaptation modes, knowledge-preserved mode (KPM) and instruction-previewed mode (IPM), providing flexibility to choose between freezing the principal components to preserve their associated knowledge or adapting them to better learn a new task. We further develop CorDA++ by deriving a metric that reflects the compactness of task-specific principal components, and then introducing dynamic covariance selection and dynamic rank allocation strategies based on the same metric. The two strategies provide each layer with the most representative covariance matrix and a proper rank allocation. Experimental results show that CorDA++ outperforms CorDA by a significant margin. CorDA++ in KPM not only achieves better fine-tuning performance than LoRA, but also mitigates the forgetting of pre-trained knowledge in both large language models and vision language models. For IPM, our method exhibits faster convergence, \emph{e.g.,} 4.5x speedup over QLoRA, and improves adaptation performance in various scenarios, outperforming strong baseline methods. Our method has been integrated into the PEFT library developed by Hugging Face.

[Arxiv](https://arxiv.org/abs/2506.13187)