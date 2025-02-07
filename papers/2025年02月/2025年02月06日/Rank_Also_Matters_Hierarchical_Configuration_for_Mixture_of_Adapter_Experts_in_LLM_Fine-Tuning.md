# 排名同样关键：LLM微调中混合适配器专家的分层配置

发布时间：2025年02月06日

`LLM理论

**解释**：这篇论文主要讨论了大型语言模型（LLMs）的微调方法，特别是参数高效微调（PEFT）方法，如低秩适应（LoRA）和专家混合（MoE）架构的结合。论文提出了一种新的分层方案HILO，用于动态调整适配器专家的数量和秩，以提高微调性能。这些内容属于对LLMs的理论研究和优化方法的探讨，因此分类为LLM理论。` `机器学习`

> Rank Also Matters: Hierarchical Configuration for Mixture of Adapter Experts in LLM Fine-Tuning

# 摘要

> 大型语言模型（LLMs）在各类任务中表现卓越，其参数规模也在持续增长。参数高效微调（PEFT）方法，如低秩适应（LoRA），通过大幅减少可训练参数，有效应对了LLMs微调的挑战。近期研究将LoRA与专家混合（MoE）架构结合，利用多适配器专家和门控机制，进一步提升了微调性能。然而，现有方法主要关注每层适配器专家的分配优化，却忽视了适配器秩这一关键因素。为此，我们提出了HILO，一种专家分配和秩配置的分层方案，动态调整跨层适配器专家的数量和秩，以适应模型层在适配器粒度上的不同表示复杂性。在多个基准任务上的实验表明，HILO在引入更少可训练参数的同时，准确性优于现有方法，为LLMs微调提供了高效实用的解决方案。

> Large language models (LLMs) have demonstrated remarkable success across various tasks, accompanied by a continuous increase in their parameter size. Parameter-efficient fine-tuning (PEFT) methods, such as Low-Rank Adaptation (LoRA), address the challenges of fine-tuning LLMs by significantly reducing the number of trainable parameters. Recent studies have integrated LoRA with Mixture of Experts (MoE) architectures, leveraging multiple adapter experts and gating mechanisms to further improve fine-tuning performance. However, existing approaches primarily focus on adjusting the allocations of adapter experts per layer to optimize the introduced trainable parameter size, while neglecting a critical factor of adapters' rank. To this end, we propose a hierarchical scheme for expert allocation and rank configuration, HILO, which dynamically adjusts the number and rank of adapter experts across layers, matching the varying representational complexity of model layers in adapter-granularity. Extensive experiments on multiple benchmark tasks demonstrate that HILO outperforms existing methods in accuracy while introducing fewer trainable parameters, providing an efficient and practical solution for fine-tuning LLMs.

[Arxiv](https://arxiv.org/abs/2502.03884)