# 深入理解并缓解以英语为中心的大型语言模型中的语言混淆问题

发布时间：2025年05月22日

`LLM理论` `人工智能`

> Mechanistic Understanding and Mitigation of Language Confusion in English-Centric Large Language Models

# 摘要

> 语言混淆——即大型语言模型（LLMs）违背用户需求生成非预期语言的现象——仍是关键挑战，尤其在以英语为中心的模型中。我们首次开展机制可解释性（MI）研究，结合行为基准测试与神经元级别分析。通过语言混淆基准测试（LCB），我们发现语言切换发生的特定位置——混淆点（CPs）——是这一现象的核心。借助TunedLens分层分析和目标神经元归因，我们揭示最终层的转换失败是混淆的主要诱因。通过编辑一组关键神经元（经与多语言微调模型比较分析识别），我们显著降低了混淆，同时保持模型的一般能力和流利度。我们的方法在混淆减少方面与多语言对齐相当，适用于大多数语言，并生成更优质输出。这些发现为理解LLMs内部动态提供了新视角，突显了神经元级别干预在实现稳健、可解释多语言建模中的潜力。


> Language confusion -- where large language models (LLMs) generate unintended languages against the user's need -- remains a critical challenge, especially for English-centric models. We present the first mechanistic interpretability (MI) study of language confusion, combining behavioral benchmarking with neuron-level analysis. Using the Language Confusion Benchmark (LCB), we show that confusion points (CPs) -- specific positions where language switches occur -- are central to this phenomenon. Through layer-wise analysis with TunedLens and targeted neuron attribution, we reveal that transition failures in the final layers drive confusion. We further demonstrate that editing a small set of critical neurons, identified via comparative analysis with multilingual-tuned models, substantially mitigates confusion without harming general competence or fluency. Our approach matches multilingual alignment in confusion reduction for most languages and yields cleaner, higher-quality outputs. These findings provide new insights into the internal dynamics of LLMs and highlight neuron-level interventions as a promising direction for robust, interpretable multilingual language modeling.

[Arxiv](https://arxiv.org/abs/2505.16538)