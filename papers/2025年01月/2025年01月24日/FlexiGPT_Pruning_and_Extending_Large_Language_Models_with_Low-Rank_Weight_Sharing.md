# FlexiGPT: 利用低秩权重共享实现大型语言模型的修剪与扩展

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了在内存受限设备上高效部署大型语言模型（LLMs）的技术需求，并提出了一种基于重要性评分选择性修剪模型块并用低参数策略替换的方法。这属于LLM在实际应用中的优化和部署问题，因此归类为LLM应用。` `模型压缩`

> FlexiGPT: Pruning and Extending Large Language Models with Low-Rank Weight Sharing

# 摘要

> 在NLP领域，LLMs的快速普及催生了在内存受限设备上高效部署而不牺牲性能的技术需求。我们提出了一种基于重要性评分选择性修剪模型块并用低参数策略替换的方法。具体而言，我们采用权重共享机制，利用未修剪的模型部分和低秩适配器替换每个修剪块。此外，通过输出特征归一化和基于低秩SVD重建的适配器初始化方案，我们促进了替换块的学习。实证评估显示，我们的方法在30%压缩率下在5/6基准测试中显著优于现有方法，在40%压缩率下在6/6基准测试中达到最优。我们还展示了该方法可扩展较小模型，仅用约0.3%的扩展训练标记，在6/6基准测试中提升性能，且额外参数成本极低。

> The rapid proliferation of large language models (LLMs) in natural language processing (NLP) has created a critical need for techniques that enable efficient deployment on memory-constrained devices without compromising performance. We present a method to prune LLMs that selectively prunes model blocks based on an importance score and replaces them with a low-parameter replacement strategy. Specifically, we propose a principled metric to replace each pruned block using a weight-sharing mechanism that leverages unpruned counterparts from the model and block-specific low-rank adapters. Furthermore, we facilitate the learning of these replacement blocks with output feature normalization and an adapter initialization scheme built on low-rank SVD reconstructions. Empirical evaluations demonstrate substantial performance gains over existing methods, achieving state-of-the-art performance on 5/6 benchmarks for a compression rate of 30% and 6/6 benchmarks for a compression rate of 40%. We also demonstrate that our approach can extend smaller models, boosting performance on 6/6 benchmarks using only ~0.3% tokens of extended training with minimal additional parameter costs.

[Arxiv](https://arxiv.org/abs/2501.14713)