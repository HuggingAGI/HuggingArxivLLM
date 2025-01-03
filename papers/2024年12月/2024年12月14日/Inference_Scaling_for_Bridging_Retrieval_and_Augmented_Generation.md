# 推理扩展：连接检索与增强生成

发布时间：2024年12月14日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）方法中的偏差问题，并提出了一种新的干预混合（MOI）方法来缓解这种偏差。论文的核心内容围绕如何通过推理扩展和多次前向传递来优化RAG的效果，并展示了在多个RAG任务中的性能提升。因此，这篇论文应归类为RAG。` `信息检索`

> Inference Scaling for Bridging Retrieval and Augmented Generation

# 摘要

> 检索增强生成（RAG）通过引入检索上下文作为输入，成为引导大型语言模型（LLM）输出的热门方法。然而，现有研究发现生成器存在偏差，即提升检索效果可能反而影响最终结果。本文提出，通过推理扩展——即对检索上下文的排列顺序进行推理调用聚合——可以有效缓解这种偏差。我们提出的干预混合（MOI）方法，通过多次前向传递显式建模每个段落的去偏差效用，从而构建新的排名。此外，MOI还能利用检索器的先验知识，通过减少排列数量和降低每次LLM调用的成本来降低计算开销。实验表明，MOI在多种RAG任务中表现优异，将MS MARCO的ROUGE-L和HotpotQA的EM指标提升了约7个点。

> Retrieval-augmented generation (RAG) has emerged as a popular approach to steering the output of a large language model (LLM) by incorporating retrieved contexts as inputs. However, existing work observed the generator bias, such that improving the retrieval results may negatively affect the outcome. In this work, we show such bias can be mitigated, from inference scaling, aggregating inference calls from the permuted order of retrieved contexts. The proposed Mixture-of-Intervention (MOI) explicitly models the debiased utility of each passage with multiple forward passes to construct a new ranking. We also show that MOI can leverage the retriever's prior knowledge to reduce the computational cost by minimizing the number of permutations considered and lowering the cost per LLM call. We showcase the effectiveness of MOI on diverse RAG tasks, improving ROUGE-L on MS MARCO and EM on HotpotQA benchmarks by ~7 points.

[Arxiv](https://arxiv.org/abs/2412.10684)