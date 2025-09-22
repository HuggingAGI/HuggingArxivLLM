# EigenTrack：谱激活特征追踪——大型语言模型与视觉语言模型的幻觉及分布外检测

发布时间：2025年09月19日

`LLM应用` `基础理论`

> EigenTrack: Spectral Activation Feature Tracking for Hallucination and Out-of-Distribution Detection in LLMs and VLMs

# 摘要

> 大型语言模型（LLMs）用途广泛，但仍易产生幻觉和分布外（OOD）错误。我们提出EigenTrack——一种可解释的实时检测器，它利用隐藏激活的谱几何特性，这是模型动态的一种紧凑全局特征。EigenTrack通过将协方差谱统计数据（如熵、特征值间隙以及与随机基线的KL散度）流式输入轻量级循环分类器，能够追踪表示结构的时间变化——这些变化会在表面错误显现前发出幻觉和OOD漂移的信号。与黑盒和灰盒方法不同，EigenTrack仅需单次前向传播，无需重采样；而与现有白盒检测器相比，它保留时间上下文，聚合全局信号，并提供可解释的准确性-延迟权衡。

> Large language models (LLMs) offer broad utility but remain prone to hallucination and out-of-distribution (OOD) errors. We propose EigenTrack, an interpretable real-time detector that uses the spectral geometry of hidden activations, a compact global signature of model dynamics. By streaming covariance-spectrum statistics such as entropy, eigenvalue gaps, and KL divergence from random baselines into a lightweight recurrent classifier, EigenTrack tracks temporal shifts in representation structure that signal hallucination and OOD drift before surface errors appear. Unlike black- and grey-box methods, it needs only a single forward pass without resampling. Unlike existing white-box detectors, it preserves temporal context, aggregates global signals, and offers interpretable accuracy-latency trade-offs.

[Arxiv](https://arxiv.org/abs/2509.15735)