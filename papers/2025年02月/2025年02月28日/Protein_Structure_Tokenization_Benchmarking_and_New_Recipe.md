# 蛋白质结构分词：基准测试及新方案

发布时间：2025年02月28日

`其他` `生物信息学` `蛋白质结构分析`

> Protein Structure Tokenization: Benchmarking and New Recipe

# 摘要

> 近年来，蛋白质结构分块方法蓬勃发展，将蛋白质的3D结构分解为离散或连续的表示形式。这一创新使蛋白质结构语言建模及大型多模态模型整合结构与蛋白质序列和功能性文本成为可能。然而，现有方法的能力与局限性因缺乏统一评估框架而尚未被充分理解。为此，我们推出StructTokenBench，一个专注于评估结构分块器质量与效率的框架，着重于精细的局部子结构而非传统整体结构。评估结果显示，现有模型在不同基准视角下各有千秋，无一绝对领先。针对代码本利用率低下的问题，我们开发了AminoAseed，一种简单而有效的策略，通过优化代码本梯度更新，在代码本大小与维度间实现最佳平衡，从而显著提升分块器的利用率与质量。与领先模型ESM3相比，我们在24个监督任务中实现了平均6.31%的性能提升，灵敏度与利用率分别显著提高12.83%和124.03%。

> Recent years have witnessed a surge in the development of protein structural tokenization methods, which chunk protein 3D structures into discrete or continuous representations. Structure tokenization enables the direct application of powerful techniques like language modeling for protein structures, and large multimodal models to integrate structures with protein sequences and functional texts. Despite the progress, the capabilities and limitations of these methods remain poorly understood due to the lack of a unified evaluation framework. We first introduce StructTokenBench, a framework that comprehensively evaluates the quality and efficiency of structure tokenizers, focusing on fine-grained local substructures rather than global structures, as typical in existing benchmarks. Our evaluations reveal that no single model dominates all benchmarking perspectives. Observations of codebook under-utilization led us to develop AminoAseed, a simple yet effective strategy that enhances codebook gradient updates and optimally balances codebook size and dimension for improved tokenizer utilization and quality. Compared to the leading model ESM3, our method achieves an average of 6.31% performance improvement across 24 supervised tasks, with sensitivity and utilization rates increased by 12.83% and 124.03%, respectively.

[Arxiv](https://arxiv.org/abs/2503.00089)