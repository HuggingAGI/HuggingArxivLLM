# 快速而简单：二维单纯形注意力在Triton中的应用

发布时间：2025年07月03日

`LLM理论` `人工智能` `模型优化`

> Fast and Simplex: 2-Simplicial Attention in Triton

# 摘要

> 最近研究表明，训练损失与模型大小和token数量之间遵循幂律关系，而实现计算效率最优的模型需要同时增大模型规模和token数量。然而，这些缩放定律假设了无限的数据供应，并主要适用于计算资源充足的场景。随着现代大型语言模型越来越依赖海量的互联网规模数据集，认为它们处于计算资源充足的假设正逐渐失效，这一变化凸显了对注重token效率的架构的需求。

本研究中，我们探讨了2-单纯形Transformer架构的应用。该架构通过高效的Triton内核实现，将标准的点积注意力机制推广到三线性函数。实验表明，2-单纯形Transformer在token效率上优于标准Transformer：在固定token预算下，规模相近的模型在数学、编码、推理和逻辑等任务上优于点积注意力机制的对应模型。我们通过实验证明，与点积注意力相比，2-单纯形注意力改变了知识和推理任务的缩放定律中的指数，从而量化了这些改进。


> Recent work has shown that training loss scales as a power law with both model size and the number of tokens, and that achieving compute-optimal models requires scaling model size and token count together. However, these scaling laws assume an infinite supply of data and apply primarily in compute-bound settings. As modern large language models increasingly rely on massive internet-scale datasets, the assumption that they are compute-bound is becoming less valid. This shift highlights the need for architectures that prioritize token efficiency.
  In this work, we investigate the use of the 2-simplicial Transformer, an architecture that generalizes standard dot-product attention to trilinear functions through an efficient Triton kernel implementation. We demonstrate that the 2-simplicial Transformer achieves better token efficiency than standard Transformers: for a fixed token budget, similarly sized models outperform their dot-product counterparts on tasks involving mathematics, coding, reasoning, and logic. We quantify these gains by demonstrating that $2$-simplicial attention changes the exponent in the scaling laws for knowledge and reasoning tasks compared to dot product attention.

[Arxiv](https://arxiv.org/abs/2507.02754)