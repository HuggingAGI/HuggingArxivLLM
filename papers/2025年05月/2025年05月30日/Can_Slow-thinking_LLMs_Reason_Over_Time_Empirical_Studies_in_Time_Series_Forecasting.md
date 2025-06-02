# # 摘要  
大型语言模型（LLMs）的最新进展推动了从机器人流程自动化（RPA）到智能体流程自动化（AgPAM）的革命性范式转变，这一转变通过基于LLMs自动化工作流编排过程实现。

发布时间：2025年05月30日

`LLM应用` `时间序列预测` `大型语言模型`

> Can Slow-thinking LLMs Reason Over Time? Empirical Studies in Time Series Forecasting

# 摘要

> 时间序列预测（TSF）是一项基础且广泛研究的任务，涵盖了从传统统计方法到现代深度学习和多模态语言建模的方法。尽管这些方法有效，但它们通常遵循快速思考范式，强调模式提取和直接值映射，而忽视了对时间动态和上下文依赖的显式推理。同时，新兴的慢思考大型语言模型（如ChatGPT-o1、DeepSeek-R1）在多个领域展现了令人印象深刻的多步推理能力，这为重新构架TSF为结构化推理任务提供了新机会。

这促使我们提出一个关键问题：慢思考大型语言模型能否有效推理时间模式，支持时间序列预测，甚至在零样本情况下？为探讨这一问题，本文提出TimeReasoner，一项全面的实证研究，将TSF表述为条件推理任务。我们设计了一系列提示策略，以激发预训练慢思考大型语言模型在推理时的推理能力，并在多样化的TSF基准上评估其性能。

我们的研究发现，慢思考大型语言模型表现出非同寻常的零样本预测能力，尤其是在捕捉高层次趋势和上下文转变方面。尽管目前研究尚处于初步阶段，但我们的研究揭示了大型语言模型在时间领域中的推理行为，突显了其潜力与局限性。我们希望这项工作能推动基于推理的预测范式的进一步研究，并为更可解释和通用的时间序列预测框架奠定基础。

> Time series forecasting (TSF) is a fundamental and widely studied task, spanning methods from classical statistical approaches to modern deep learning and multimodal language modeling. Despite their effectiveness, these methods often follow a fast thinking paradigm emphasizing pattern extraction and direct value mapping, while overlooking explicit reasoning over temporal dynamics and contextual dependencies. Meanwhile, emerging slow-thinking LLMs (e.g., ChatGPT-o1, DeepSeek-R1) have demonstrated impressive multi-step reasoning capabilities across diverse domains, suggesting a new opportunity for reframing TSF as a structured reasoning task. This motivates a key question: can slow-thinking LLMs effectively reason over temporal patterns to support time series forecasting, even in zero-shot manner? To investigate this, in this paper, we propose TimeReasoner, an extensive empirical study that formulates TSF as a conditional reasoning task. We design a series of prompting strategies to elicit inference-time reasoning from pretrained slow-thinking LLMs and evaluate their performance across diverse TSF benchmarks. Our findings reveal that slow-thinking LLMs exhibit non-trivial zero-shot forecasting capabilities, especially in capturing high-level trends and contextual shifts. While preliminary, our study surfaces important insights into the reasoning behaviors of LLMs in temporal domains highlighting both their potential and limitations. We hope this work catalyzes further research into reasoning-based forecasting paradigms and paves the way toward more interpretable and generalizable TSF frameworks.

[Arxiv](https://arxiv.org/abs/2505.24511)