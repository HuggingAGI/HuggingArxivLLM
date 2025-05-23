# 基于知识导向的简单问答评估大型语言模型

发布时间：2025年05月22日

`LLM应用` `语言学` `跨文化交流`

> Evaluating Large Language Model with Knowledge Oriented Language Specific Simple Question Answering

# 摘要

> 我们推出 KoLasSimpleQA，首个专为评估大型语言模型 (LLMs) 多语言事实能力设计的基准测试。受现有研究启发，我们精心打造了涵盖单一知识点、具备绝对客观性、拥有唯一答案且保持时间稳定性的题库。这些问题使我们能够借助 LLM 作为评委的范式高效评估，既考验 LLM 的事实记忆，又检验其自我认知能力（“知道自己不知道什么”）。KoLasSimpleQA 在两个关键维度上实现了突破：(1) 广度（多语言覆盖）：支持 9 种语言，为全球适用性评估提供可能。 (2) 深度（双域设计）：同时覆盖通用领域（全球事实）和语言特定领域（如历史、文化及地区传统），全面评估多语言能力。我们对主流 LLM 进行了测试，包括传统 LLM 和新兴大规模推理模型。结果显示，不同领域在性能指标、排名、校准和鲁棒性方面存在显著差异。这一发现凸显了在多语言环境中进行针对性评估和优化的重要性。我们期待 KoLasSimpleQA 能够助力研究界更清晰地识别 LLM 在多语言环境中的能力边界，并为模型优化提供方向。KoLasSimpleQA 已在 https://github.com/opendatalab/KoLasSimpleQA 发布。

> We introduce KoLasSimpleQA, the first benchmark evaluating the multilingual factual ability of Large Language Models (LLMs). Inspired by existing research, we created the question set with features such as single knowledge point coverage, absolute objectivity, unique answers, and temporal stability. These questions enable efficient evaluation using the LLM-as-judge paradigm, testing both the LLMs' factual memory and self-awareness ("know what they don't know"). KoLasSimpleQA expands existing research in two key dimensions: (1) Breadth (Multilingual Coverage): It includes 9 languages, supporting global applicability evaluation. (2) Depth (Dual Domain Design): It covers both the general domain (global facts) and the language-specific domain (such as history, culture, and regional traditions) for a comprehensive assessment of multilingual capabilities. We evaluated mainstream LLMs, including traditional LLM and emerging Large Reasoning Models. Results show significant performance differences between the two domains, particularly in performance metrics, ranking, calibration, and robustness. This highlights the need for targeted evaluation and optimization in multilingual contexts. We hope KoLasSimpleQA will help the research community better identify LLM capability boundaries in multilingual contexts and provide guidance for model optimization. We will release KoLasSimpleQA at https://github.com/opendatalab/KoLasSimpleQA .

[Arxiv](https://arxiv.org/abs/2505.16591)