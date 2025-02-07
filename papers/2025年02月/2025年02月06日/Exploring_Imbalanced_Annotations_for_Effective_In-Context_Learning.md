# 探索不平衡标注对上下文学习效果的提升

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在上下文学习（ICL）中的表现，特别是标注数据集类别分布不平衡对ICL性能的影响。论文提出了一种新的方法来处理这种不平衡问题，并通过实验验证了其有效性。这些内容主要涉及LLM的理论研究和改进方法，因此归类为“LLM理论”。` `机器学习` `数据挖掘`

> Exploring Imbalanced Annotations for Effective In-Context Learning

# 摘要

> 大型语言模型（LLMs）通过上下文学习（ICL）在下游任务中表现出色，但这一表现高度依赖于从标注数据集中挑选的示例。现有选择方法往往受限于标注数据集的分布，而现实场景中这种分布通常是长尾的。本文研究表明，标注数据集中类别分布的不平衡会显著降低ICL在各种任务和选择方法中的性能，且传统再平衡方法对此问题束手无策。我们提出了一种新方法，将标注数据集与测试数据集之间的分布差异分解为两个权重：类别权重和条件偏差。该方法的核心思想是通过最小化平衡验证数据集上的经验误差来估计条件偏差，并在选择过程中利用这两个权重调整原始评分函数。我们的方法既能避免从单一类别中选取过多示例，又能保持原始选择方法的有效性。大量实验表明，该方法在不平衡数据集的常见基准上，平均准确率最高提升了5.46。

> Large language models (LLMs) have shown impressive performance on downstream tasks through in-context learning (ICL), which heavily relies on the demonstrations selected from annotated datasets. Existing selection methods may hinge on the distribution of annotated datasets, which can often be long-tailed in real-world scenarios. In this work, we show that imbalanced class distributions in annotated datasets significantly degrade the performance of ICL across various tasks and selection methods. Moreover, traditional rebalance methods fail to ameliorate the issue of class imbalance in ICL. Our method is motivated by decomposing the distributional differences between annotated and test datasets into two-component weights: class-wise weights and conditional bias. The key idea behind our method is to estimate the conditional bias by minimizing the empirical error on a balanced validation dataset and to employ the two-component weights to modify the original scoring functions during selection. Our approach can prevent selecting too many demonstrations from a single class while preserving the effectiveness of the original selection methods. Extensive experiments demonstrate the effectiveness of our method, improving the average accuracy by up to 5.46 on common benchmarks with imbalanced datasets.

[Arxiv](https://arxiv.org/abs/2502.04037)