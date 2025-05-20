# 结构引导跨模态对齐增强 LLM 的时间序列预测能力。

发布时间：2025年05月19日

`LLM应用` `时间序列预测`

> Enhancing LLMs for Time Series Forecasting via Structure-Guided Cross-Modal Alignment

# 摘要

> 利用预训练大型语言模型（LLMs）进行时间序列预测的新范式主要通过基于令牌级或层级特征映射的语言-时间模态对齐策略实现。然而，这些方法从根本上忽视了一个关键见解：LLMs的核心能力不仅在于处理局部令牌特征，更在于其本质上能够建模整体序列结构。本文提出，有效的跨模态对齐需要在序列级别保持结构一致性。我们提出了基于结构引导的跨模态对齐框架（SGCMA），该框架充分利用并对齐时间序列和语言数据作为序列模态所共享的状态转换图结构，从而赋予时间序列类似语言的特性，并在模态对齐后实现更强的泛化能力。SGCMA包括两个关键组件，即结构对齐和语义对齐。在结构对齐中，通过隐马尔可夫模型（HMM）从文本数据中学习状态转移矩阵，浅层变压器的极大熵马尔可夫模型（MEMM）接收预热转移矩阵，并将每个时间补丁标注为状态概率，确保时间表示序列继承类似语言的序列动态。在语义对齐中，在时间补丁与每个状态的前k个词之间应用交叉注意力机制，最终的时间嵌入通过基于状态概率的加权平均计算得到。在多个基准上的实验表明，SGCMA实现了最先进的性能，为时间序列预测中的跨模态对齐提供了一种新颖的方法。


> The emerging paradigm of leveraging pretrained large language models (LLMs) for time series forecasting has predominantly employed linguistic-temporal modality alignment strategies through token-level or layer-wise feature mapping. However, these approaches fundamentally neglect a critical insight: the core competency of LLMs resides not merely in processing localized token features but in their inherent capacity to model holistic sequence structures. This paper posits that effective cross-modal alignment necessitates structural consistency at the sequence level. We propose the Structure-Guided Cross-Modal Alignment (SGCMA), a framework that fully exploits and aligns the state-transition graph structures shared by time-series and linguistic data as sequential modalities, thereby endowing time series with language-like properties and delivering stronger generalization after modality alignment. SGCMA consists of two key components, namely Structure Alignment and Semantic Alignment. In Structure Alignment, a state transition matrix is learned from text data through Hidden Markov Models (HMMs), and a shallow transformer-based Maximum Entropy Markov Model (MEMM) receives the hot-start transition matrix and annotates each temporal patch into state probability, ensuring that the temporal representation sequence inherits language-like sequential dynamics. In Semantic Alignment, cross-attention is applied between temporal patches and the top-k tokens within each state, and the ultimate temporal embeddings are derived by the expected value of these embeddings using a weighted average based on state probabilities. Experiments on multiple benchmarks demonstrate that SGCMA achieves state-of-the-art performance, offering a novel approach to cross-modal alignment in time series forecasting.

[Arxiv](https://arxiv.org/abs/2505.13175)