# DynaCode：动态复杂度感知的代码基准测试，用于评估大型语言模型在代码生成任务中的表现。

发布时间：2025年03月13日

`LLM应用` `软件开发` `基准测试`

> DynaCode: A Dynamic Complexity-Aware Code Benchmark for Evaluating Large Language Models in Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成任务中的性能突飞猛进，但现有代码基准测试的静态特性却带来了严重问题。这些固定数据集和预设问题的组合，使模型在训练时更倾向于记忆特定测试案例，而非真正掌握泛化能力，最终导致数据污染和评估结果不可靠。为突破这一瓶颈，我们推出了DynaCode——一个动态且感知复杂性的新基准测试。DynaCode通过结合代码复杂度和调用图结构的综合评估指标，为LLMs提供全面的能力检验。它覆盖了从简单到复杂的四个代码级别和16种调用图类型，生成了多达1.89亿个独特的嵌套代码问题。在12个最新LLMs的测试中，DynaCode的评估结果显示，与传统静态基准MBPP+相比，模型性能平均下降16.8%至45.7%，且复杂性越高，性能越明显下滑。这一结果充分证明了DynaCode在区分模型真实能力方面的有效性。此外，通过对调用图的深入分析，我们还揭示了LLMs在处理嵌套代码时的独特偏好，特别是在子函数交互方面的行为特征。

> The rapid advancement of large language models (LLMs) has significantly improved their performance in code generation tasks. However, existing code benchmarks remain static, consisting of fixed datasets with predefined problems. This makes them vulnerable to memorization during training, where LLMs recall specific test cases instead of generalizing to new problems, leading to data contamination and unreliable evaluation results. To address these issues, we introduce DynaCode, a dynamic, complexity-aware benchmark that overcomes the limitations of static datasets. DynaCode evaluates LLMs systematically using a complexity-aware metric, incorporating both code complexity and call-graph structures. DynaCode achieves large-scale diversity, generating up to 189 million unique nested code problems across four distinct levels of code complexity, referred to as units, and 16 types of call graphs. Results on 12 latest LLMs show an average performance drop of 16.8% to 45.7% compared to MBPP+, a static code generation benchmark, with performance progressively decreasing as complexity increases. This demonstrates DynaCode's ability to effectively differentiate LLMs. Additionally, by leveraging call graphs, we gain insights into LLM behavior, particularly their preference for handling subfunction interactions within nested code.

[Arxiv](https://arxiv.org/abs/2503.10452)