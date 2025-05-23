# TRIM：基于行的迭代度量驱动剪枝方法实现极端稀疏性

发布时间：2025年05月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的剪枝技术，提出了一种创新的方法TRIM，用于优化模型的稀疏度分配，以提高模型的效率和性能。这属于模型训练和优化的理论层面，因此归类为LLM理论。`

> TRIM: Achieving Extreme Sparsity with Targeted Row-wise Iterative Metric-driven Pruning

# 摘要

> 大型语言模型（LLMs）因其规模庞大，在计算和内存方面带来了巨大挑战，因此剪枝技术对于实现高效部署至关重要。现有的一次性剪枝方法往往在各层间或层内采用统一的稀疏度约束，这在高稀疏度比时会导致性能下降。本研究提出了一种名为TRIM（基于目标的逐行迭代度量驱动剪枝）的创新方法，该方法对每一层内的各个输出维度（行）应用差异化的稀疏度比率。TRIM通过质量指标引导的迭代调整过程，优化维度级别的稀疏度分配，重点关注减少输出间质量保留的方差，从而保留关键信息。TRIM能够无缝集成到现有的逐层剪枝策略中。我们在困惑度和零样本任务上，针对不同LLM家族（Qwen2.5, LLaMA-2, 和 OPT）和稀疏度水平进行的评估表明，TRIM实现了新的最先进结果并提升了稳定性。例如，在80%稀疏度下，与基线方法相比，TRIM使Qwen2.5-14B的困惑度降低了48%，OPT-13B的困惑度降低了90%以上。我们得出结论，精细的维度级别稀疏度自适应对于突破极端LLM压缩的极限至关重要。代码可在：https://github.com/flobk/TRIM 获取

> Large Language Models (LLMs) present significant computational and memory challenges due to their extensive size, making pruning essential for their efficient deployment. Existing one-shot pruning methods often apply uniform sparsity constraints across layers or within each layer, resulting in suboptimal performance, especially at high sparsity ratios. This work introduces TRIM (Targeted Row-wise Iterative Metric-driven pruning), a novel approach that applies varying sparsity ratios to individual output dimensions (rows) within each layer. TRIM employs an iterative adjustment process guided by quality metrics to optimize dimension-wise sparsity allocation, focusing on reducing variance in quality retention across outputs to preserve critical information. TRIM can be seamlessly integrated with existing layer-wise pruning strategies. Our evaluations on perplexity and zero-shot tasks across diverse LLM families (Qwen2.5, LLaMA-2, and OPT) and sparsity levels demonstrate that TRIM achieves new state-of-the-art results and enhances stability. For instance, at 80% sparsity, TRIM reduces perplexity by 48% for Qwen2.5-14B and over 90% for OPT-13B compared to baseline methods. We conclude that fine-grained, dimension-wise sparsity adaptation is crucial for pushing the limits of extreme LLM compression. Code available at: https://github.com/flobk/TRIM

[Arxiv](https://arxiv.org/abs/2505.16743)