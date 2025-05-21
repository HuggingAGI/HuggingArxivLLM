# 冰淇淋不会导致溺水：评估 LLMs 在因果推断中的统计误区

发布时间：2025年05月19日

`LLM应用` `公共政策`

> Ice Cream Doesn't Cause Drowning: Benchmarking LLMs Against Statistical Pitfalls in Causal Inference

# 摘要

> 因果推理在医学、经济学和公共政策等高风险领域至关重要，但大型语言模型（LLMs）能否胜任严格可信的统计因果推理仍存疑。现有基准测试多基于简化任务，仅要求模型识别语义因果关系或直接从数据中得出结论，忽视了辛普森悖论等关键统计陷阱，限制了 LLMs 的实际应用。为此，我们提出 CausalPitfalls，一个全面基准测试，旨在严格评估 LLMs 在克服因果推理陷阱方面的潜力。该基准测试涵盖多难度级别的结构化挑战，每项挑战均配有评分标准，可定量衡量模型的因果推理能力和响应可靠性。我们采用两种评估协议：直接提示评估固有因果推理能力，代码辅助提示则要求生成用于显式统计分析的可执行代码。通过与人类专家评估对比，我们验证了该评估方法的有效性。研究结果表明，当前 LLMs 在统计因果推理方面存在重大局限性。CausalPitfalls 基准测试为开发值得信赖的因果推理系统提供了关键指导和定量指标。

> Reliable causal inference is essential for making decisions in high-stakes areas like medicine, economics, and public policy. However, it remains unclear whether large language models (LLMs) can handle rigorous and trustworthy statistical causal inference. Current benchmarks usually involve simplified tasks. For example, these tasks might only ask LLMs to identify semantic causal relationships or draw conclusions directly from raw data. As a result, models may overlook important statistical pitfalls, such as Simpson's paradox or selection bias. This oversight limits the applicability of LLMs in the real world. To address these limitations, we propose CausalPitfalls, a comprehensive benchmark designed to rigorously evaluate the capability of LLMs in overcoming common causal inference pitfalls. Our benchmark features structured challenges across multiple difficulty levels, each paired with grading rubrics. This approach allows us to quantitatively measure both causal reasoning capabilities and the reliability of LLMs' responses. We evaluate models using two protocols: (1) direct prompting, which assesses intrinsic causal reasoning, and (2) code-assisted prompting, where models generate executable code for explicit statistical analysis. Additionally, we validate the effectiveness of this judge by comparing its scoring with assessments from human experts. Our results reveal significant limitations in current LLMs when performing statistical causal inference. The CausalPitfalls benchmark provides essential guidance and quantitative metrics to advance the development of trustworthy causal reasoning systems.

[Arxiv](https://arxiv.org/abs/2505.13770)