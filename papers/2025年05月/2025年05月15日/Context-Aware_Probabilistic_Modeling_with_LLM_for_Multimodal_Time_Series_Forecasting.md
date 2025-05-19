# 基于 LLM 的上下文感知概率建模应用于多模态时间序列预测

发布时间：2025年05月15日

`LLM应用`

> Context-Aware Probabilistic Modeling with LLM for Multimodal Time Series Forecasting

# 摘要

> 时间序列预测在能源市场、气候分析和交通管理等领域具有重要意义。然而，现有方法难以有效整合外部文本，并与大型语言模型（LLMs）的概率特性相匹配。当前方法要么采用基于基本提示的浅层文本-时间序列融合，要么依赖与LLMs生成范式冲突的确定性数值解码，这限制了上下文感知和分布建模能力。为了解决这些问题，我们提出CAPTime，这是一种基于上下文感知的概率多模态时间序列预测方法，结合了文本驱动的抽象和自回归LLM解码。我们的方法首先利用预训练的时间序列编码器编码时间模式，然后通过可学习的交互模块与文本上下文对齐，生成联合多模态表示。通过将分布专家混合与冻结的LLMs相结合，我们实现了上下文感知的概率预测，同时保留了LLMs固有的分布建模能力。在多样化的时间序列预测任务上的实验表明，CAPTime在准确性和通用性方面表现优异，尤其是在多模态场景中。额外的分析还突显了其在数据稀缺场景中通过混合概率解码的鲁棒性。

> Time series forecasting is important for applications spanning energy markets, climate analysis, and traffic management. However, existing methods struggle to effectively integrate exogenous texts and align them with the probabilistic nature of large language models (LLMs). Current approaches either employ shallow text-time series fusion via basic prompts or rely on deterministic numerical decoding that conflict with LLMs' token-generation paradigm, which limits contextual awareness and distribution modeling. To address these limitations, we propose CAPTime, a context-aware probabilistic multimodal time series forecasting method that leverages text-informed abstraction and autoregressive LLM decoding. Our method first encodes temporal patterns using a pretrained time series encoder, then aligns them with textual contexts via learnable interactions to produce joint multimodal representations. By combining a mixture of distribution experts with frozen LLMs, we enable context-aware probabilistic forecasting while preserving LLMs' inherent distribution modeling capabilities. Experiments on diverse time series forecasting tasks demonstrate the superior accuracy and generalization of CAPTime, particularly in multimodal scenarios. Additional analysis highlights its robustness in data-scarce scenarios through hybrid probabilistic decoding.

[Arxiv](https://arxiv.org/abs/2505.10774)