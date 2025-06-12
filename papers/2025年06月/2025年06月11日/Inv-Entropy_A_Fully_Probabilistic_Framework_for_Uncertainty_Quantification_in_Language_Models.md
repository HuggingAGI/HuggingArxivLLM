# 逆熵：语言模型不确定性量化完整概率框架

发布时间：2025年06月11日

`LLM理论`

> Inv-Entropy: A Fully Probabilistic Framework for Uncertainty Quantification in Language Models

# 摘要

> 大型语言模型 (LLMs) 已经彻底改变了自然语言处理领域，但它们的可靠应用需要有效的不确定性量化 (UQ)。现有的 UQ 方法多基于启发式，缺乏坚实的概率论基础。本文首先从理论上阐述了扰动在 LLMs 不确定性量化中的关键作用。接着，我们创新性地提出了双随机游走视角，将输入-输出对建模为两个马尔可夫链，其转移概率由语义相似性决定。在此基础上，我们开发了一种基于逆模型的全新概率框架，通过系统性扰动评估给定输出条件下输入空间的多样性来量化不确定性。在此框架下，我们引入了新的不确定性度量 Inv-Entropy。该框架的一大优势是其高度的灵活性：它兼容多种不确定性度量的定义、嵌入方式、扰动策略和相似性度量。此外，我们提出了 GAAP，一种基于遗传算法的扰动算法，能够显著提升采样输入的多样性。我们还创新性地引入了温度敏感性不确定性 (TSU) 评估指标，它可以直接评估不确定性，而无需依赖正确性作为替代。通过大量实验验证，Inv-Entropy 在现有的语义 UQ 方法中表现最为出色。相关代码可在 https://github.com/UMDataScienceLab/Uncertainty-Quantification-for-LLMs 获取。

> Large language models (LLMs) have transformed natural language processing, but their reliable deployment requires effective uncertainty quantification (UQ). Existing UQ methods are often heuristic and lack a probabilistic foundation. This paper begins by providing a theoretical justification for the role of perturbations in UQ for LLMs. We then introduce a dual random walk perspective, modeling input-output pairs as two Markov chains with transition probabilities defined by semantic similarity. Building on this, we propose a fully probabilistic framework based on an inverse model, which quantifies uncertainty by evaluating the diversity of the input space conditioned on a given output through systematic perturbations. Within this framework, we define a new uncertainty measure, Inv-Entropy. A key strength of our framework is its flexibility: it supports various definitions of uncertainty measures, embeddings, perturbation strategies, and similarity metrics. We also propose GAAP, a perturbation algorithm based on genetic algorithms, which enhances the diversity of sampled inputs. In addition, we introduce a new evaluation metric, Temperature Sensitivity of Uncertainty (TSU), which directly assesses uncertainty without relying on correctness as a proxy. Extensive experiments demonstrate that Inv-Entropy outperforms existing semantic UQ methods. The code to reproduce the results can be found at https://github.com/UMDataScienceLab/Uncertainty-Quantification-for-LLMs.

[Arxiv](https://arxiv.org/abs/2506.09684)