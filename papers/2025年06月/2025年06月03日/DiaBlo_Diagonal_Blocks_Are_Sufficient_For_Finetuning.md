# # DiaBlo: 对角块足以应对微调任务

发布时间：2025年06月03日

`LLM应用

理由：这篇论文讨论了参数高效微调（PEFT）方法，提出了一种新的方法 DiaBlo，用于优化大型语言模型的微调过程。论文的重点在于如何有效应用微调方法以提高模型在特定任务中的性能，属于 LLM 的应用层面。` `人工智能`

> DiaBlo: Diagonal Blocks Are Sufficient For Finetuning

# 摘要

> 微调是将大型语言模型（LLMs）适配到特定领域下游任务的关键步骤。为有效缓解全模型微调带来的巨大计算和内存成本，参数高效微调（Parameter-Efficient Finetuning, PEFT）方法应运而生，仅需更新模型参数的一小部分。然而，PEFT方法与全模型微调之间仍存在性能差距。在本研究中，我们提出了一种简单而有效的PEFT方法——DiaBlo，仅更新所选模型权重矩阵的对角块。与低秩适配（Low Rank Adaptation, LoRA）及其变体不同，DiaBlo消除了对低秩矩阵乘法的需求，从而避免依赖辅助初始化方案或定制优化策略来提升收敛性。这种设计在保持与LoRA相当的内存效率和训练速度的同时，实现了稳定且鲁棒的收敛。我们通过涵盖常识推理、算术推理、代码生成和安全对齐等多类任务的广泛实验，评估了DiaBlo的有效性和效率。在这些基准测试中，DiaBlo展现出强劲且一致的性能，同时保持了高内存效率和快速微调速度。代码可在https://github.com/ziyangjoy/DiaBlo获取。

> Finetuning is a critical step for adapting large language models (LLMs) to domain-specific downstream tasks. To mitigate the substantial computational and memory costs of full-model fine-tuning, Parameter-Efficient Finetuning (PEFT) methods have been proposed to update only a small subset of model parameters. However, performance gaps between PEFT approaches and full-model fine-tuning still exist. In this work, we present DiaBlo, a simple yet effective PEFT approach that updates only the diagonal blocks of selected model weight matrices. Unlike Low Rank Adaptation (LoRA) and its variants, DiaBlo eliminates the need for low rank matrix products, thereby avoiding the reliance on auxiliary initialization schemes or customized optimization strategies to improve convergence. This design leads to stable and robust convergence while maintaining comparable memory efficiency and training speed to LoRA. We conduct extensive experiments across a range of tasks, including commonsense reasoning, arithmetic reasoning, code generation, and safety alignment, to evaluate the effectiveness and efficiency of DiaBlo. Across these benchmarks, DiaBlo demonstrates strong and consistent performance while maintaining high memory efficiency and fast finetuning speed. Codes are available at https://github.com/ziyangjoy/DiaBlo.

[Arxiv](https://arxiv.org/abs/2506.03230)