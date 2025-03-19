# # 时间一致性在大语言模型推理过程错误识别中的应用
时间一致性在大语言模型 (LLM) 推理过程中的错误识别具有重要意义。通过分析推理过程中的时间一致性，我们可以更好地理解模型在推理过程中可能出现的错误，并采取相应的改进措施。

发布时间：2025年03月18日

`LLM应用`

> Temporal Consistency for LLM Reasoning Process Error Identification

# 摘要

> 验证是有效数学推理的关键。我们提出了一种基于时间一致性的新方法，验证者通过迭代反思逐步优化判断。与单轮验证或多模型辩论不同，我们通过序列中的一致性提升准确性。在 Mathcheck、ProcessBench 和 PRM800K 等基准测试中，我们的方法显著优于传统方案。应用于 DeepSeek R1 蒸馏模型时，7B/8B 模型超越了 70B/72B 模型和 GPT-4o，而 14B 模型的表现更是与 Deepseek-R1 比肩。代码已开源：https://github.com/jcguo123/Temporal-Consistency

> Verification is crucial for effective mathematical reasoning. We present a new temporal consistency method where verifiers iteratively refine their judgments based on the previous assessment. Unlike one-round verification or multi-model debate approaches, our method leverages consistency in a sequence of self-reflection actions to improve verification accuracy. Empirical evaluations across diverse mathematical process error identification benchmarks (Mathcheck, ProcessBench, and PRM800K) show consistent performance improvements over baseline methods. When applied to the recent DeepSeek R1 distilled models, our method demonstrates strong performance, enabling 7B/8B distilled models to outperform all 70B/72B models and GPT-4o on ProcessBench. Notably, the distilled 14B model with our method achieves performance comparable to Deepseek-R1. Our codes are available at https://github.com/jcguo123/Temporal-Consistency

[Arxiv](https://arxiv.org/abs/2503.14495)