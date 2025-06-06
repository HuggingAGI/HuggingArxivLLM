# 聚类与中位数聚合优化差异隐私推理

发布时间：2025年06月04日

`LLM应用

理由：这篇论文探讨了如何在大型语言模型（LLM）中应用差分隐私技术，以生成私有合成文本。虽然它涉及隐私保护，但主要关注的是LLM的应用和优化，而非其理论基础或内部机制。因此，归类为LLM应用。` `数据隐私保护`

> Clustering and Median Aggregation Improve Differentially Private Inference

# 摘要

> 差分隐私（DP）语言模型推理是一种生成私有合成文本的方法。通过使用敏感输入示例提示现成的大型语言模型（LLM），可以生成类似的示例。多个示例的聚合可以正式满足差分隐私的保证。

    之前的工作通过从敏感输入中均匀随机采样来创建推理批次。然而，我们发现均匀采样会显著降低私有生成文本的质量，尤其是在处理异质主题的敏感示例时。

    为了解决这一问题，我们在选择推理批次之前对输入数据进行聚类。进一步观察发现，聚类会导致推理之间更相似的下一个词预测。基于这一发现，我们引入了一种新算法，该算法通过私下计算中位数而不是平均值来聚合下一个词的统计信息。这种方法利用了中位数在相似预测下较低的局部敏感性，从而允许我们对这个算法的隐私特性做出数据依赖的和事后的DP保证。

    最后，我们在代表性指标（如MAUVE）和下游任务性能方面展示了显著改进。实验结果表明，与之前最先进的方法相比，我们的方法在生成高质量合成数据的同时，显著降低了隐私成本。
    

> Differentially private (DP) language model inference is an approach for generating private synthetic text. A sensitive input example is used to prompt an off-the-shelf large language model (LLM) to produce a similar example. Multiple examples can be aggregated together to formally satisfy the DP guarantee.
  Prior work creates inference batches by sampling sensitive inputs uniformly at random. We show that uniform sampling degrades the quality of privately generated text, especially when the sensitive examples concern heterogeneous topics.
  We remedy this problem by clustering the input data before selecting inference batches. Next, we observe that clustering also leads to more similar next-token predictions across inferences. We use this insight to introduce a new algorithm that aggregates next token statistics by privately computing medians instead of averages. This approach leverages the fact that the median has decreased local sensitivity when next token predictions are similar, allowing us to state a data-dependent and ex-post DP guarantee about the privacy properties of this algorithm. Finally, we demonstrate improvements in terms of representativeness metrics (e.g., MAUVE) as well as downstream task performance. We show that our method produces high-quality synthetic data at significantly lower privacy cost than a previous state-of-the-art method.

[Arxiv](https://arxiv.org/abs/2506.04566)