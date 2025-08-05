# LOST：大型语言模型的低秩稀疏预训练方法

发布时间：2025年08月04日

`LLM理论` `计算机科学`

> LOST: Low-rank and Sparse Pre-training for Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在各类任务中表现优异，但其庞大的规模使得从头预训练的计算和内存成本高昂到难以承受。近期研究探讨了通过低秩参数化来减少模型规模和训练成本的可能性。在此背景下，稀疏性常被作为互补技术，通过捕获残差空间中的显著特征来恢复低秩压缩中丢失的重要信息。然而，现有方法通常以简单或随意的方式结合低秩和稀疏组件，与全秩训练相比，往往导致性能下降。本文提出了一种针对LLMs的全新方法，即	extbf{LO}w-rank and 	extbf{S}parse pre-	extbf{T}raining（	extbf{LOST}），该方法巧妙地将低秩和稀疏结构相结合，能够在严格的效率约束下实现有效的LLMs从头训练。LOST通过对权重矩阵进行奇异值分解，保留主要的低秩组件，同时将剩余的奇异值分配到构建通道级稀疏组件中，以补充低秩训练的表达能力。我们在从60M到7B参数规模的LLM预训练中评估了LOST。实验表明，与全秩模型相比，LOST不仅实现了具有竞争力甚至更优的性能，同时显著降低了内存和计算开销。此外，代码可在\href{https://github.com/JiaxiLi1/LOST-Low-rank-and-Sparse-Training-for-Large-Language-Models}{LOST Repo}获取。

> While large language models (LLMs) have achieved remarkable performance across a wide range of tasks, their massive scale incurs prohibitive computational and memory costs for pre-training from scratch. Recent studies have investigated the use of low-rank parameterization as a means of reducing model size and training cost. In this context, sparsity is often employed as a complementary technique to recover important information lost in low-rank compression by capturing salient features in the residual space. However, existing approaches typically combine low-rank and sparse components in a simplistic or ad hoc manner, often resulting in undesirable performance degradation compared to full-rank training. In this paper, we propose \textbf{LO}w-rank and \textbf{S}parse pre-\textbf{T}raining (\textbf{LOST}) for LLMs, a novel method that ingeniously integrates low-rank and sparse structures to enable effective training of LLMs from scratch under strict efficiency constraints. LOST applies singular value decomposition to weight matrices, preserving the dominant low-rank components, while allocating the remaining singular values to construct channel-wise sparse components to complement the expressiveness of low-rank training. We evaluate LOST on LLM pretraining ranging from 60M to 7B parameters. Our experiments show that LOST achieves competitive or superior performance compared to full-rank models, while significantly reducing both memory and compute overhead. Moreover, Code is available at \href{https://github.com/JiaxiLi1/LOST-Low-rank-and-Sparse-Training-for-Large-Language-Models}{LOST Repo}

[Arxiv](https://arxiv.org/abs/2508.02668)