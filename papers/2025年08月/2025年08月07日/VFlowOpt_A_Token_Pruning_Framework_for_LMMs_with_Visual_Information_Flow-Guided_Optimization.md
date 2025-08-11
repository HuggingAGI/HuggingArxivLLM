# VFlowOpt: 基于视觉信息流优化的LMMs Token剪枝框架

发布时间：2025年08月07日

`LLM应用

理由：该论文探讨了大型多模态模型（LMMs）在视觉语言任务中的优化，提出了一种创新的令牌剪枝框架VFlowOpt。虽然涉及模型优化，但其核心在于应用层面的改进，而非理论探讨或代理、RAG相关内容。因此，归类为LLM应用。` `视觉语言` `计算机视觉`

> VFlowOpt: A Token Pruning Framework for LMMs with Visual Information Flow-Guided Optimization

# 摘要

> # 摘要
大型多模态模型（LMMs）在视觉语言任务中表现出色，通过大量视觉令牌获取精细视觉信息。然而，令牌冗余导致了高昂的计算成本。以往研究主要通过仅视觉或视觉语言令牌间的注意力分数导出重要性图谱，在一个或多个阶段剪枝令牌。尽管有所进展，现有剪枝框架和策略仍显简单，研究不足，常导致性能大幅下降。

本文提出VFlowOpt，一种创新的令牌剪枝框架。VFlowOpt引入重要性图谱导出过程，并配备带有回收机制的渐进式剪枝模块。其剪枝策略的超参数通过视觉信息流引导的方法进一步优化。具体而言，我们基于图像令牌的注意力导出上下文相关性和补丁级别信息熵，计算重要性图谱。随后决定保留或剪除令牌，并将剪除的令牌聚合为回收令牌，避免信息丢失。最后，我们采用视觉信息流引导的方法，将LMM中的最后一个令牌视为文本视觉交互的最具代表性的信号。该方法最小化了LMM中存在和不存在剪枝的令牌表示之间的差异，从而实现了针对不同LMM的更优剪枝策略。

实验结果表明，VFlowOpt可以在保持性能的同时剪除90%的视觉令牌，将KV-Cache内存减少89%，并将推理速度提升3.8倍。

> Large Multimodal Models (LMMs) excel in visual-language tasks by leveraging numerous visual tokens for fine-grained visual information, but this token redundancy results in significant computational costs. Previous research aimed at reducing visual tokens during inference typically leverages importance maps derived from attention scores among vision-only tokens or vision-language tokens to prune tokens across one or multiple pruning stages. Despite this progress, pruning frameworks and strategies remain simplistic and insufficiently explored, often resulting in substantial performance degradation. In this paper, we propose VFlowOpt, a token pruning framework that introduces an importance map derivation process and a progressive pruning module with a recycling mechanism. The hyperparameters of its pruning strategy are further optimized by a visual information flow-guided method. Specifically, we compute an importance map for image tokens based on their attention-derived context relevance and patch-level information entropy. We then decide which tokens to retain or prune and aggregate the pruned ones as recycled tokens to avoid potential information loss. Finally, we apply a visual information flow-guided method that regards the last token in the LMM as the most representative signal of text-visual interactions. This method minimizes the discrepancy between token representations in LMMs with and without pruning, thereby enabling superior pruning strategies tailored to different LMMs. Experiments demonstrate that VFlowOpt can prune 90% of visual tokens while maintaining comparable performance, leading to an 89% reduction in KV-Cache memory and 3.8 times faster inference.

[Arxiv](https://arxiv.org/abs/2508.05211)