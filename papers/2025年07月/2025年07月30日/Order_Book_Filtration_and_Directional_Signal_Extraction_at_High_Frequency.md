# 高频订单簿过滤与方向信号提取

发布时间：2025年07月30日

`其他` `金融市场` `算法交易`

> Order Book Filtration and Directional Signal Extraction at High Frequency

# 摘要

> 电子资本市场的兴起和算法交易代理的普及，使得逐笔市场数据中的事件数量激增。其中很大一部分订单具有瞬时特性，这些瞬时订单的特性削弱了基于限价订单簿 (LOB) 状态所获取的方向性超额收益 (alpha) 的信息价值。我们研究了通过结构化过滤高频 LOB 数据来改善订单簿失衡 (OBI) 等方向性信号的可能性。我们提出了三种实时可观察的过滤方案：基于订单寿命、更新次数和更新间隔。利用这些方案对结构化过滤后的事件流重新计算 OBI。为了评估过滤效果，我们实施了一个三层诊断框架：与回报的同期相关性、离散化状态计数的解释能力，以及通过 Hawkes 激发范数的因果一致性。实证结果表明，结构化过滤在相关性和状态基指标上提高了方向性信号的清晰度，但在因果激发强度上的提升有限。相比之下，基于成交事件计算的 OBI 与未来价格走势的因果一致性更强。这些发现强调了在设计高频方向性信号时区分关联性和因果性诊断的重要性。

> With the advent of electronic capital markets and algorithmic trading agents, the number of events in tick-by-tick market data has exploded. A large fraction of these orders is transient. Their ephemeral character degrades the informativeness of directional alphas derived from the limit order book (LOB) state. We investigate whether directional signals such as order book imbalance (OBI) can be improved by structurally filtering high-frequency LOB data. Three real-time, observable filtration schemes: based on order lifetime, update count, and inter-update delay. These are used to recompute OBI on structurally filtered event streams. To assess the effect of filtration, we implement a three-layer diagnostic framework: contemporaneous correlation with returns, explanatory power under discretized regime counts, and causal coherence via Hawkes excitation norms. Empirical results show that structural filtration improves directional signal clarity in correlation and regime-based metrics, but leads to only limited gains in causal excitation strength. In contrast, OBI computed using trade events exhibits stronger causal alignment with future price movements. These findings highlight the importance of differentiating between associative and causal diagnostics when designing high-frequency directional signals.

[Arxiv](https://arxiv.org/abs/2507.22712)