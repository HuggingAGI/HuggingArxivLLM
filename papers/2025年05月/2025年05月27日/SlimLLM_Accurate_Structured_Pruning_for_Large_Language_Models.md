# SlimLLM：大型语言模型的精准结构化剪枝

发布时间：2025年05月27日

`LLM应用` `人工智能` `计算机科学`

> SlimLLM: Accurate Structured Pruning for Large Language Models

# 摘要

> 大型语言模型（LLMs）凭借其卓越性能在众多领域引发了广泛关注。然而，由于其高昂的计算成本，LLMs的实际应用往往受到限制。为解决这一问题，我们提出了一种名为SlimLLM的有效快速结构化剪枝方法，旨在压缩模型参数。在剪枝过程中，我们不仅关注单个元素的重要性，更基于整个通道或注意力头进行评估，从而更全面地考虑子模块内部的相互依赖关系。此外，我们设计了一种简单的线性回归策略来快速恢复模型性能，并提出了一种基于层的重要性比率方法来优化剪枝比例。实验结果表明， SlimLLM在LLaMA基准测试中表现优异，达到了当前最优水平。

> Large language models(LLMs) have garnered significant attention and demonstrated impressive capabilities in a wide range of applications. However, due to their enormous computational costs, the deployment and application of LLMs are often severely limited. To address this issue, structured pruning is an effective solution to compress the parameters of LLMs. Determining the importance of each sub-module in LLMs and minimizing performance loss are critical issues that need to be carefully addressed in structured pruning. In this paper, we propose an effective and fast structured pruning method named SlimLLM for large language models. For channel and attention head pruning, we evaluate the importance based on the entire channel or head, rather than merely aggregating the importance of individual elements within a sub-module. This approach enables a more holistic consideration of the interdependence among elements within the sub-module. In addition, we design a simple linear regression strategy for the output matrix to quickly recover performance. We also propose layer-based importance ratio to determine the pruning ratio for each layer. Based on the LLaMA benchmark results, our SlimLLM outperforms other methods and achieves state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2505.22689)