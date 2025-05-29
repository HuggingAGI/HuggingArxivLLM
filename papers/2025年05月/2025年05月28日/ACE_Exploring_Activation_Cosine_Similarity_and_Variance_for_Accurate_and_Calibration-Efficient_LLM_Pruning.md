# ACE：通过激活余弦相似度与方差分析，打造准确且校准高效的LLM剪枝方案

发布时间：2025年05月28日

`LLM理论

论文摘要讨论了大型语言模型的剪枝方法，提出了一种新的高效剪枝策略，引入了两个关键指标以提高剪枝的准确性和效率。这属于对模型本身的优化和改进，因此归类为LLM理论。` `人工智能`

> ACE: Exploring Activation Cosine Similarity and Variance for Accurate and Calibration-Efficient LLM Pruning

# 摘要

> 大型语言模型（LLMs）的快速发展带来了对内存和计算资源的显著需求增长。近期关于LLM剪枝的研究致力于减小模型规模和降低计算成本，然而现有方法往往在剪枝性能或时间效率上表现欠佳。我们提出了一种高效且有效的剪枝方法，实现了高剪枝性能与快速剪枝速度的双重突破，并提升了校准效率。我们的方法创新性地引入了两个关键指标：(1) 基于激活余弦相似度损失的剪枝指标，衡量稠密模型与剪枝后模型输出激活的角度偏差；(2) 基于激活方差的剪枝指标，帮助保留输出激活中的语义差异，支持使用短输入序列实现有效剪枝。这两个指标可轻松结合，全面提升LLM剪枝的准确性和效率。实验结果表明，我们的方法在LLaMA、LLaMA-2和OPT等主流LLM上，实现了困惑度降低18%、剪枝时间减少高达63%的显著效果。

> With the rapid expansion of large language models (LLMs), the demand for memory and computational resources has grown significantly. Recent advances in LLM pruning aim to reduce the size and computational cost of these models. However, existing methods often suffer from either suboptimal pruning performance or low time efficiency during the pruning process. In this work, we propose an efficient and effective pruning method that simultaneously achieves high pruning performance and fast pruning speed with improved calibration efficiency. Our approach introduces two key innovations: (1) An activation cosine similarity loss-guided pruning metric, which considers the angular deviation of the output activation between the dense and pruned models. (2) An activation variance-guided pruning metric, which helps preserve semantic distinctions in output activations after pruning, enabling effective pruning with shorter input sequences. These two components can be readily combined to enhance LLM pruning in both accuracy and efficiency. Experimental results show that our method achieves up to an 18% reduction in perplexity and up to 63% decrease in pruning time on prevalent LLMs such as LLaMA, LLaMA-2, and OPT.

[Arxiv](https://arxiv.org/abs/2505.21987)