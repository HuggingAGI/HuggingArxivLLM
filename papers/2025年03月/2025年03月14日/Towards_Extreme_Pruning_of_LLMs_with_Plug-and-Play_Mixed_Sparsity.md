# 探索LLMs的极端剪枝：即插即用混合稀疏性

发布时间：2025年03月14日

`LLM应用

<example>
论文摘要：N:M结构化剪枝对大型语言模型（LLMs）至关重要，因为它能移除不重要的网络权重，从而降低内存和计算需求。现有剪枝方法主要集中在设计指标以衡量网络组件的重要性，从而指导剪枝过程。除了这些指标的影响外，我们发现不同层对网络性能的敏感度存在差异。因此，我们提出了一种基于费舍尔信息矩阵（FIM）迹的高效方法，用于定量测量和验证各层之间的不同敏感度。基于此，我们提出了混合稀疏剪枝（MSP），它使用一种面向剪枝的进化算法（EA）来确定不同层的最优稀疏度。为了保证快速收敛并实现良好的性能，我们利用高效的FIM启发式分层敏感度来初始化EA种群。此外，我们的MSP可以作为一个即插即用模块，随时集成到现有的剪枝方法中。在LLaMA和LLaMA-2模型上进行的语言建模和零样本任务的大量实验表明，我们的方法表现优异。特别地，在极端剪枝比例（例如75%）下，我们的方法在困惑度（PPL）方面显著优于现有方法，差距达到多个数量级（如图1所示）。
LLM应用
</example>` `机器学习`

> Towards Extreme Pruning of LLMs with Plug-and-Play Mixed Sparsity

# 摘要

> N:M结构化剪枝对大型语言模型（LLMs）至关重要，因为它能移除不重要的网络权重，从而降低内存和计算需求。现有剪枝方法主要集中在设计指标以衡量网络组件的重要性，从而指导剪枝过程。除了这些指标的影响外，我们发现不同层对网络性能的敏感度存在差异。因此，我们提出了一种基于费舍尔信息矩阵（FIM）迹的高效方法，用于定量测量和验证各层之间的不同敏感度。基于此，我们提出了混合稀疏剪枝（MSP），它使用一种面向剪枝的进化算法（EA）来确定不同层的最优稀疏度。为了保证快速收敛并实现良好的性能，我们利用高效的FIM启发式分层敏感度来初始化EA种群。此外，我们的MSP可以作为一个即插即用模块，随时集成到现有的剪枝方法中。在LLaMA和LLaMA-2模型上进行的语言建模和零样本任务的大量实验表明，我们的方法表现优异。特别地，在极端剪枝比例（例如75%）下，我们的方法在困惑度（PPL）方面显著优于现有方法，差距达到多个数量级（如图1所示）。

> N:M structured pruning is essential for large language models (LLMs) because it can remove less important network weights and reduce the memory and computation requirements. Existing pruning methods mainly focus on designing metrics to measure the importance of network components to guide pruning. Apart from the impact of these metrics, we observe that different layers have different sensitivities over the network performance. Thus, we propose an efficient method based on the trace of Fisher Information Matrix (FIM) to quantitatively measure and verify the different sensitivities across layers. Based on this, we propose Mixed Sparsity Pruning (MSP) which uses a pruning-oriented evolutionary algorithm (EA) to determine the optimal sparsity levels for different layers. To guarantee fast convergence and achieve promising performance, we utilize efficient FIM-inspired layer-wise sensitivity to initialize the population of EA. In addition, our MSP can work as a plug-and-play module, ready to be integrated into existing pruning methods. Extensive experiments on LLaMA and LLaMA-2 on language modeling and zero-shot tasks demonstrate our superior performance. In particular, in extreme pruning ratio (e.g. 75%), our method significantly outperforms existing methods in terms of perplexity (PPL) by orders of magnitude (Figure 1).

[Arxiv](https://arxiv.org/abs/2503.11164)