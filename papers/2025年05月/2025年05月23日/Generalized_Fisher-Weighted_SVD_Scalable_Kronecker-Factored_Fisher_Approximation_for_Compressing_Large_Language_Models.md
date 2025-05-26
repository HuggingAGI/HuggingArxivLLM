# 广义Fisher加权奇异值分解：实现大型语言模型压缩的可扩展Kronecker因子化Fisher近似

发布时间：2025年05月23日

`LLM理论` `机器学习`

> Generalized Fisher-Weighted SVD: Scalable Kronecker-Factored Fisher Approximation for Compressing Large Language Models

# 摘要

> 费舍尔信息是表征神经网络参数敏感性的核心概念。然而，对于大型模型，完整观测费舍尔信息的计算成本过高，因此大多数方法采用简单的对角线近似。尽管这种方法高效，但忽略了参数间的相关性，导致下游任务性能受限。为此，我们提出了广义费舍尔加权奇异值分解（GFWSVD），一种在训练后压缩大型语言模型（LLM）的技术，它同时考虑费舍尔信息矩阵的对角线和非对角线元素，更准确地反映参数重要性。为使方法可行，我们引入了观测费舍尔信息的可扩展克罗内克因子化近似算法。实验表明，我们的方法在LLM压缩上优于现有基线。例如，在MMLU基准上的20倍压缩率下，我们的方法比基于费舍尔信息对角近似的FWSVD高出5个百分点，比SVD-LLM高出3个百分点，比ASVD高出6个百分点的压缩率。

> The Fisher information is a fundamental concept for characterizing the sensitivity of parameters in neural networks. However, leveraging the full observed Fisher information is too expensive for large models, so most methods rely on simple diagonal approximations. While efficient, this approach ignores parameter correlations, often resulting in reduced performance on downstream tasks. In this work, we mitigate these limitations and propose Generalized Fisher-Weighted SVD (GFWSVD), a post-training LLM compression technique that accounts for both diagonal and off-diagonal elements of the Fisher information matrix, providing a more accurate reflection of parameter importance. To make the method tractable, we introduce a scalable adaptation of the Kronecker-factored approximation algorithm for the observed Fisher information. We demonstrate the effectiveness of our method on LLM compression, showing improvements over existing compression baselines. For example, at a 20 compression rate on the MMLU benchmark, our method outperforms FWSVD, which is based on a diagonal approximation of the Fisher information, by 5 percent, SVD-LLM by 3 percent, and ASVD by 6 percent compression rate.

[Arxiv](https://arxiv.org/abs/2505.17974)