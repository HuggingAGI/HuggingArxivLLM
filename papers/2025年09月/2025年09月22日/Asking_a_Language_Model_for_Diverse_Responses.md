# 让语言模型生成多样化响应

发布时间：2025年09月22日

`LLM应用` `基础理论`

> Asking a Language Model for Diverse Responses

# 摘要

> 大型语言模型如今愈发依赖显式推理链，且能针对特定上下文生成多个合理响应。我们研究了生成合理响应集的候选采样器，对比了传统的祖先（并行）采样与两种替代方法：枚举法（要求模型单次生成【数学公式】个候选）和迭代采样（基于当前已生成的响应集依次提出候选）。在预算相同的条件下，我们从质量、词汇与计算流多样性及效率三个维度对这些采样器进行了比较。实证结果显示，枚举法和迭代策略在保证质量相当的同时，能显著提升多样性。研究结果凸显了简单非独立采样策略的潜力——在不牺牲生成质量的前提下提升响应多样性。

> Large language models increasingly rely on explicit reasoning chains and can produce multiple plausible responses for a given context. We study the candidate sampler that produces the set of plausible responses contrasting the ancestral (parallel) sampling against two alternatives: enumeration, which asks the model to produce $n$ candidates in one pass, and iterative sampling, which proposes candidates sequentially while conditioning on the currently generated response set. Under matched budgets, we compare these samplers on quality, lexical and computation flow diversity, and efficiency. Our empirical results demonstrate that enumeration and iterative strategies result in higher diversity at comparable quality. Our findings highlight the potential of simple non-independent sampling strategies to improve response diversity without sacrificing generation quality.

[Arxiv](https://arxiv.org/abs/2509.17570)