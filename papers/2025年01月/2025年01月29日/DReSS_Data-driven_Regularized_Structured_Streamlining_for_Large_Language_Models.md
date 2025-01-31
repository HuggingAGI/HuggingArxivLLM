# DReSS: 数据驱动的正则化结构化精简，助力大型语言模型

发布时间：2025年01月29日

`LLM理论` `模型压缩`

> DReSS: Data-driven Regularized Structured Streamlining for Large Language Models

# 摘要

> 大型语言模型（LLMs）在多个领域取得了显著进展，但其规模的扩大带来了高昂的计算和内存成本。最新研究发现，LLMs具有稀疏性，这为通过剪枝技术压缩模型提供了可能。然而，现有剪枝方法通常采用“先剪枝再微调”的模式。由于被剪枝的组件仍包含重要信息，直接移除它们往往会导致性能不可逆的下降，从而在微调过程中需要大量计算资源来恢复性能。本文提出了一种新范式：先正则化，再剪枝，最后微调。基于这一范式，我们提出了DReSS，一种简单高效的数据驱动正则化结构化精简方法。DReSS通过少量数据对剪枝组件进行正则化，提前将重要信息显式转移到模型的剩余部分。与直接剪枝相比，这种方法减少了参数移除带来的信息损失，从而提升了语言建模能力。实验表明，即使在极端剪枝比例下，DReSS也显著优于现有剪枝方法，大幅降低了延迟并提高了吞吐量。

> Large language models (LLMs) have achieved significant progress across various domains, but their increasing scale results in high computational and memory costs. Recent studies have revealed that LLMs exhibit sparsity, providing the potential to reduce model size through pruning techniques. However, existing pruning methods typically follow a prune-then-finetune paradigm. Since the pruned components still contain valuable information, their direct removal often leads to irreversible performance degradation, imposing a substantial computational burden to recover performance during finetuning. In this paper, we propose a novel paradigm that first applies regularization, then prunes, and finally finetunes. Based on this paradigm, we introduce DReSS, a simple and effective Data-driven Regularized Structured Streamlining method for LLMs. By leveraging a small amount of data to regularize the components to be pruned, DReSS explicitly transfers the important information to the remaining parts of the model in advance. Compared to direct pruning, this can reduce the information loss caused by parameter removal, thereby enhancing its language modeling capabilities. Experimental results demonstrate that DReSS significantly outperforms existing pruning methods even under extreme pruning ratios, significantly reducing latency and increasing throughput.

[Arxiv](https://arxiv.org/abs/2501.17905)