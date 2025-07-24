# 能否借助外部验证工具提升LLM作为裁判的标注质量？

发布时间：2025年07月22日

`LLM应用

理由：这篇论文探讨了如何通过工具增强的系统来提升大型语言模型在特定任务中的反馈质量，属于大型语言模型的应用研究。` `人工智能`

> Can External Validation Tools Improve Annotation Quality for LLM-as-a-Judge?

# 摘要

> 模型响应的配对偏好被广泛用于评估和优化大型语言模型 (LLMs)。通过让人类或 AI 标注者从同一输入的两个替代响应中选择更优者，我们能够为难以量化评估的领域（如聊天质量）提供反馈支持。然而，某些领域中高质量的配对比较往往难以获得——无论是来自 AI 还是人类。例如，面对包含大量事实陈述的响应时，标注者可能过分关注写作质量而忽视事实本身。针对这一挑战，我们提出了一种工具增强的智能系统，旨在提升长篇事实性、数学和代码任务等三个具有挑战性领域的反馈质量。该系统通过网络搜索和代码执行实现外部验证，从而摆脱对 LLM 内部知识和偏见的依赖。我们通过 RewardBench（含 AlpacaEval 和 LLMBar）、RewardMath，以及三个全新的数据集，对我们的方法进行了全面评估，覆盖了目标领域和通用标注任务。实验结果表明，外部工具确实在许多情况下（但非全部）能够提升性能。更重要的是，我们的研究揭示了系统性能对简单参数（如提示）的高度敏感性，并凸显了建立更完善的标注基准的重要性。我们的代码已开源，详情请访问 https://github.com/apple/ml-agent-evaluator。


> Pairwise preferences over model responses are widely collected to evaluate and provide feedback to large language models (LLMs). Given two alternative model responses to the same input, a human or AI annotator selects the "better" response. This approach can provide feedback for domains where other hard-coded metrics are difficult to obtain (e.g., chat response quality), thereby helping model evaluation or training. However, for some domains high-quality pairwise comparisons can be tricky to obtain - from AI and humans. For example, for responses with many factual statements, annotators may disproportionately weigh writing quality rather than underlying facts. In this work, we explore augmenting standard AI annotator systems with additional tools to improve performance on three challenging response domains: long-form factual, math and code tasks. We propose a tool-using agentic system to provide higher quality feedback on these domains. Our system uses web-search and code execution to ground itself based on external validation, independent of the LLM's internal knowledge and biases. We provide extensive experimental results evaluating our method across the three targeted response domains as well as general annotation tasks, using RewardBench (incl. AlpacaEval and LLMBar), RewardMath, as well as three new datasets for domains with saturated pre-existing datasets. Our results indicate that external tools can indeed improve performance in many, but not all, cases. More generally, our experiments highlight the sensitivity of performance to simple parameters (e.g., prompt) and the need for improved (non-saturated) annotator benchmarks. We share our code at https://github.com/apple/ml-agent-evaluator.

[Arxiv](https://arxiv.org/abs/2507.17015)