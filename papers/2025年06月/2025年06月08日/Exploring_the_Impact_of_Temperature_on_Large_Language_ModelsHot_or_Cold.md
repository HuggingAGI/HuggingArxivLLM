# # 温度对大型语言模型的影响：是该冷静还是热烈？
温度参数对大型语言模型的性能有着重要影响，尤其是在生成任务中，它决定了模型输出的随机性和创造性。然而，关于温度如何影响模型性能的深入理解仍然有限，特别是在不同任务和数据集上，最佳温度设置尚未达成共识。

发布时间：2025年06月08日

`LLM理论` `人工智能`

> Exploring the Impact of Temperature on Large Language Models:Hot or Cold?

# 摘要

> 采样温度是大型语言模型（LLMs）中的关键超参数，通过调整softmax层前的logits值来重塑输出标记的分布。近期研究表明，LLMs不仅能够记忆数据，还能理解语义，而由采样温度调节的随机性在模型推理中起着重要作用，从而挑战了“随机鹦鹉”类比。本研究系统评估了0到2范围内采样温度的影响，针对六种不同能力设计的数据集进行了统计分析，测试了三个规模的开源模型：小型（1B至4B）、中型（6B至13B）和大型（40B至80B）。研究发现，采样温度对模型性能的影响因具体能力而异，凸显了实际应用中选择最优温度的复杂性。为解决这一挑战，我们提出了一种基于BERT的温度选择器，利用观察到的影响效应来识别给定提示的最佳温度。实验表明，这种方法显著提升了小型和中型模型在SuperGLUE数据集上的性能。此外，研究还扩展到FP16精度推理，发现温度效应与4位量化模型中观察到的效果一致。通过在三个量化模型中评估温度效应直至4.0，我们发现突变温度——性能发生显著变化的点——随着模型规模的增加而增加。

> The sampling temperature, a critical hyperparameter in large language models (LLMs), modifies the logits before the softmax layer, thereby reshaping the distribution of output tokens. Recent studies have challenged the Stochastic Parrots analogy by demonstrating that LLMs are capable of understanding semantics rather than merely memorizing data and that randomness, modulated by sampling temperature, plays a crucial role in model inference. In this study, we systematically evaluated the impact of temperature in the range of 0 to 2 on data sets designed to assess six different capabilities, conducting statistical analyses on open source models of three different sizes: small (1B--4B), medium (6B--13B), and large (40B--80B). Our findings reveal distinct skill-specific effects of temperature on model performance, highlighting the complexity of optimal temperature selection in practical applications. To address this challenge, we propose a BERT-based temperature selector that takes advantage of these observed effects to identify the optimal temperature for a given prompt. We demonstrate that this approach can significantly improve the performance of small and medium models in the SuperGLUE datasets. Furthermore, our study extends to FP16 precision inference, revealing that temperature effects are consistent with those observed in 4-bit quantized models. By evaluating temperature effects up to 4.0 in three quantized models, we find that the Mutation Temperature -- the point at which significant performance changes occur -- increases with model size.

[Arxiv](https://arxiv.org/abs/2506.07295)