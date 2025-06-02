# 超越指数衰减：重新审视大型语言模型中的错误积累

发布时间：2025年05月29日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）在长序列输出中的可靠性问题，并提出了一种新的理论框架来解释其性能。论文挑战了主流的关于LLM可靠性的假设，并提出了新的理论解释，属于对LLM理论的深入研究。` `人工智能`

> Beyond Exponential Decay: Rethinking Error Accumulation in Large Language Models

# 摘要

> 目前关于大型语言模型（LLM）可靠性随着序列长度呈指数级衰减的主流假设，认为长自回归输出存在根本性限制。我们的研究根本性地挑战了这一观点，通过整合新兴证据表明，LLM错误并非均匀分布，而是集中在稀疏的“关键标记”（占总标记的5-10%）上，这些标记代表了关键的决策节点。通过区分这些高影响标记与日益可预测的大多数标记，我们提出了一种新的可靠性公式，解释了现代LLM在数千个标记上保持连贯性的原因。汇聚的研究表明，长上下文性能主要取决于准确导航少数关键语义决策点，而非均匀的标记级准确性，从而支持了比暴力方法更有效的针对性策略。因此，我们提出了一种以选择性保留语义重要标记、在不确定决策边界动态分配计算资源、在模糊性时进行多路径探索以及与自然语义领域对齐的架构为核心的新一代系统框架。这标志着从简单扩展到战略推理的根本转变，有望在不按比例扩大计算规模的情况下实现突破性性能，提供了超越指数衰减假设的更细致理解，从而为构建更强大、更高效的语言系统开辟了新的道路。

> The prevailing assumption of an exponential decay in large language model (LLM) reliability with sequence length, predicated on independent per-token error probabilities, posits an inherent limitation for long autoregressive outputs. Our research fundamentally challenges this view by synthesizing emerging evidence that LLM errors are not uniformly distributed but are concentrated at sparse "key tokens" ($5-10\%$ of total tokens) representing critical decision junctions. By distinguishing these high-impact tokens from the increasingly predictable majority, we introduce a new reliability formula explaining the sustained coherence of modern LLMs over thousands of tokens. Converging research streams reveal that long-context performance primarily depends on accurately navigating a few crucial semantic decision points rather than on uniform token-level accuracy, enabling targeted strategies that significantly outperform brute-force approaches. We thus propose a framework for next-generation systems centered on selective preservation of semantically vital tokens, dynamic computational allocation at uncertain decision boundaries, multi-path exploration at ambiguities, and architectures aligned with natural semantic domains. This marks a fundamental shift from raw scaling to strategic reasoning, promising breakthrough performance without proportionate computational scaling and offering a more nuanced understanding that supersedes the exponential decay hypothesis, thereby opening pathways toward substantially more powerful and efficient language systems.

[Arxiv](https://arxiv.org/abs/2505.24187)