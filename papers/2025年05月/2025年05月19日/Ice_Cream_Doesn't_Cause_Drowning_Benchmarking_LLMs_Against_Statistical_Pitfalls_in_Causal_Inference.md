# 冰淇淋不会导致溺水：评估大型语言模型在因果推理中的统计误区

发布时间：2025年05月19日

`LLM应用

摘要中讨论了大型语言模型在因果推断中的应用，提出了评估其能力的基准测试，并探讨了其在实际任务中的表现和局限性。这属于LLM的应用研究。` `因果推断` `统计方法`

> Ice Cream Doesn't Cause Drowning: Benchmarking LLMs Against Statistical Pitfalls in Causal Inference

# 摘要

> 因果推断在医学、经济学和公共政策等高风险领域至关重要，但大型语言模型（LLMs）能否胜任严谨的统计因果推断仍存疑问。现有基准测试多基于简化任务，例如仅要求模型识别因果关系或直接分析原始数据，这可能导致模型忽视辛普森悖论或选择偏差等关键统计陷阱，限制了其实际应用。为解决这一问题，我们提出了 CausalPitfalls 基准测试，旨在全面评估 LLMs 克服因果推断陷阱的能力。通过多难度级别的结构化挑战和配套评分标准，我们能够定量衡量模型的因果推理能力和回应可靠性。评估采用直接提示和代码辅助提示两种方式：前者评估模型的固有因果推理能力，后者要求模型生成用于显式统计分析的可执行代码。我们还通过与人类专家评估的对比，验证了评估方法的有效性。结果显示，当前 LLMs 在统计因果推断方面存在明显局限。CausalPitfalls 为开发可信因果推理系统提供了关键指导和量化指标。

> Reliable causal inference is essential for making decisions in high-stakes areas like medicine, economics, and public policy. However, it remains unclear whether large language models (LLMs) can handle rigorous and trustworthy statistical causal inference. Current benchmarks usually involve simplified tasks. For example, these tasks might only ask LLMs to identify semantic causal relationships or draw conclusions directly from raw data. As a result, models may overlook important statistical pitfalls, such as Simpson's paradox or selection bias. This oversight limits the applicability of LLMs in the real world. To address these limitations, we propose CausalPitfalls, a comprehensive benchmark designed to rigorously evaluate the capability of LLMs in overcoming common causal inference pitfalls. Our benchmark features structured challenges across multiple difficulty levels, each paired with grading rubrics. This approach allows us to quantitatively measure both causal reasoning capabilities and the reliability of LLMs' responses. We evaluate models using two protocols: (1) direct prompting, which assesses intrinsic causal reasoning, and (2) code-assisted prompting, where models generate executable code for explicit statistical analysis. Additionally, we validate the effectiveness of this judge by comparing its scoring with assessments from human experts. Our results reveal significant limitations in current LLMs when performing statistical causal inference. The CausalPitfalls benchmark provides essential guidance and quantitative metrics to advance the development of trustworthy causal reasoning systems.

[Arxiv](https://arxiv.org/abs/2505.13770)