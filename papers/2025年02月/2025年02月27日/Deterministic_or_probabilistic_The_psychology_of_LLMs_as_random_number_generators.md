# 确定性还是概率性？大型语言模型作为随机数生成器的心理学探析

大型语言模型（LLMs）作为生成式AI模型，其随机性一直是学界和业界关注的焦点。本文将从心理学视角，深入探讨LLMs在随机数生成方面的独特机制与行为表现。通过实证研究和理论分析，我们试图揭示LLMs在生成随机内容时的内在逻辑与决策模式。这对理解AI模型的创造力、不可预测性以及潜在的应用场景具有重要意义。

发布时间：2025年02月27日

`LLM理论` `计算机科学`

> Deterministic or probabilistic? The psychology of LLMs as random number generators

# 摘要

> 大型语言模型（LLMs）通过其概率上下文感知机制，彻底改变了文本生成的方式，模仿人类自然语言。本文系统性地研究了各种LLMs在生成随机数时的表现，考虑了不同的模型架构、数值范围、温度参数和提示语言等配置。研究发现，尽管这些模型基于随机变换器架构，但它们在生成随机数值输出时往往表现出确定性响应。特别地，改变模型或提示语言会导致显著差异，这一现象归因于训练数据中的偏见。像DeepSeek-R1这样的模型，尽管结果相似，仍能揭示LLMs的内部推理过程。这些偏见诱导出可预测的模式，削弱了随机性，因为LLMs本质上只是在复制人类的认知偏见。

> Large Language Models (LLMs) have transformed text generation through inherently probabilistic context-aware mechanisms, mimicking human natural language. In this paper, we systematically investigate the performance of various LLMs when generating random numbers, considering diverse configurations such as different model architectures, numerical ranges, temperature, and prompt languages. Our results reveal that, despite their stochastic transformers-based architecture, these models often exhibit deterministic responses when prompted for random numerical outputs. In particular, we find significant differences when changing the model, as well as the prompt language, attributing this phenomenon to biases deeply embedded within the training data. Models such as DeepSeek-R1 can shed some light on the internal reasoning process of LLMs, despite arriving to similar results. These biases induce predictable patterns that undermine genuine randomness, as LLMs are nothing but reproducing our own human cognitive biases.

[Arxiv](https://arxiv.org/abs/2502.19965)