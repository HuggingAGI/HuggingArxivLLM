# # 用有效状态大小量化内存利用率

发布时间：2025年04月28日

`LLM理论` `计算机科学` `人工智能`

> Quantifying Memory Utilization with Effective State-Size

# 摘要

> 随着序列模型设计空间的不断扩大，开发一个通用的架构分析框架变得日益重要。为此，我们从经典信号处理和控制理论中汲取灵感，提出了一种衡量	extit{内存利用率}的定量指标：模型存储过去信息以生成未来输出的内部机制。我们称这一指标为	extbf{	extit{有效状态大小}}（ESS），它专为具有	extit{输入不变}和	extit{输入变化线性算子}的基本系统类别设计，涵盖了许多计算单元，如注意力机制、卷积和循环神经网络等变体。与之前关于内存利用率的工作不同，这些工作要么依赖于原始算子可视化（例如注意力图），要么仅仅关注模型的总	extit{内存容量}（即缓存大小），我们的指标提供了高度可解释和可操作的测量方法。具体而言，我们展示了如何利用ESS来改进初始化策略、启发新型正则化方法以及通过模型蒸馏推进性能与效率的前沿。此外，我们还证明了上下文分隔符（如结束语音标记）对ESS的影响突显了大型语言模型在利用其可用内存召回信息时的跨架构差异。总体而言，我们发现ESS为内存利用率的动态机制提供了宝贵的见解，从而能够设计出更高效和有效的序列模型。


> The need to develop a general framework for architecture analysis is becoming increasingly important, given the expanding design space of sequence models. To this end, we draw insights from classical signal processing and control theory, to develop a quantitative measure of \textit{memory utilization}: the internal mechanisms through which a model stores past information to produce future outputs. This metric, which we call \textbf{\textit{effective state-size}} (ESS), is tailored to the fundamental class of systems with \textit{input-invariant} and \textit{input-varying linear operators}, encompassing a variety of computational units such as variants of attention, convolutions, and recurrences. Unlike prior work on memory utilization, which either relies on raw operator visualizations (e.g. attention maps), or simply the total \textit{memory capacity} (i.e. cache size) of a model, our metrics provide highly interpretable and actionable measurements. In particular, we show how ESS can be leveraged to improve initialization strategies, inform novel regularizers and advance the performance-efficiency frontier through model distillation. Furthermore, we demonstrate that the effect of context delimiters (such as end-of-speech tokens) on ESS highlights cross-architectural differences in how large language models utilize their available memory to recall information. Overall, we find that ESS provides valuable insights into the dynamics that dictate memory utilization, enabling the design of more efficient and effective sequence models.

[Arxiv](https://arxiv.org/abs/2504.19561)