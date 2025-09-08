# HoPE：大型语言模型中稳定长程依赖建模的双曲旋转位置编码

发布时间：2025年09月05日

`LLM理论` `基础理论`

> HoPE: Hyperbolic Rotary Positional Encoding for Stable Long-Range Dependency Modeling in Large Language Models

# 摘要

> 位置编码机制让Transformer得以捕捉文本的序列结构与长程依赖关系。然而，绝对位置编码因位置表示固定而难以外推至更长序列；Alibi等相对位置编码在超长上下文下性能衰减；广泛应用的旋转位置编码（RoPE）则会产生振荡注意力模式，影响长距离依赖关系的稳定建模。为此，我们从几何角度重构位置编码机制，受双曲几何中洛伦兹变换的启发，提出双曲旋转位置编码（HoPE）——该方法利用双曲函数对token表示实施洛伦兹旋转。理论分析证实，RoPE实为我们广义公式的特例。HoPE通过使注意力权重随token距离增加而单调衰减，从根本上解决了RoPE的振荡问题。大量实验（包括多个扩展序列基准上的困惑度评估）表明，HoPE性能持续超越现有位置编码方法，凸显其在长程依赖表示与泛化能力上的显著优势。相关数据与代码将公开发布。

> Positional encoding mechanisms enable Transformers to model sequential structure and long-range dependencies in text. While absolute positional encodings struggle with extrapolation to longer sequences due to fixed positional representations, and relative approaches like Alibi exhibit performance degradation on extremely long contexts, the widely-used Rotary Positional Encoding (RoPE) introduces oscillatory attention patterns that hinder stable long-distance dependency modelling. We address these limitations through a geometric reformulation of positional encoding. Drawing inspiration from Lorentz transformations in hyperbolic geometry, we propose Hyperbolic Rotary Positional Encoding (HoPE), which leverages hyperbolic functions to implement Lorentz rotations on token representations. Theoretical analysis demonstrates that RoPE is a special case of our generalized formulation. HoPE fundamentally resolves RoPE's slation issues by enforcing monotonic decay of attention weights with increasing token distances. Extensive experimental results, including perplexity evaluations under several extended sequence benchmarks, show that HoPE consistently exceeds existing positional encoding methods. These findings underscore HoPE's enhanced capacity for representing and generalizing long-range dependencies. Data and code will be available.

[Arxiv](https://arxiv.org/abs/2509.05218)