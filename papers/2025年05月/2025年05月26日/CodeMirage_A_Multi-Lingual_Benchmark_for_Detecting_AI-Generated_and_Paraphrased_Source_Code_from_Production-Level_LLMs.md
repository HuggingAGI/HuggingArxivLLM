# CodeMirage：一个多语言基准，用于检测生产级LLM生成和改写后的源代码。

发布时间：2025年05月26日

`LLM应用` `软件开发` `代码检测`

> CodeMirage: A Multi-Lingual Benchmark for Detecting AI-Generated and Paraphrased Source Code from Production-Level LLMs

# 摘要

> 大型语言模型（LLMs）在现代软件开发中扮演了重要角色，生成了大量AI代码。虽然这些模型提高了编程效率，但滥用它们会引发严重风险，如代码抄袭、许可证违规和传播不安全程序。因此，检测AI生成代码变得至关重要。为了支持检测器的开发，我们需要一个反映现实条件的综合性基准测试。然而，现有的基准测试存在局限——大多仅支持有限的编程语言，并依赖能力较弱的生成模型。本文介绍的CodeMirage基准测试通过三大创新解决了这些问题：(1) 支持十种主流编程语言，(2) 包含原始和改写代码样本，(3) 集成了十种顶尖生产级LLMs的输出，涵盖六家供应商的推理型和非推理型模型。通过CodeMirage，我们在四种现实评估环境下，对四种方法论范式下的十种检测器进行了全面评估，采用三种互补指标呈现结果。我们的研究发现了九个关键点，揭示了现有检测器的优缺点，并为未来研究指明了方向。我们相信，CodeMirage将为开发更 robust 和通用的AI代码检测器提供一个严谨实用的测试平台。

> Large language models (LLMs) have become integral to modern software development, producing vast amounts of AI-generated source code. While these models boost programming productivity, their misuse introduces critical risks, including code plagiarism, license violations, and the propagation of insecure programs. As a result, robust detection of AI-generated code is essential. To support the development of such detectors, a comprehensive benchmark that reflects real-world conditions is crucial. However, existing benchmarks fall short -- most cover only a limited set of programming languages and rely on less capable generative models. In this paper, we present CodeMirage, a comprehensive benchmark that addresses these limitations through three major advancements: (1) it spans ten widely used programming languages, (2) includes both original and paraphrased code samples, and (3) incorporates outputs from ten state-of-the-art production-level LLMs, including both reasoning and non-reasoning models from six major providers. Using CodeMirage, we evaluate ten representative detectors across four methodological paradigms under four realistic evaluation configurations, reporting results using three complementary metrics. Our analysis reveals nine key findings that uncover the strengths and weaknesses of current detectors, and identify critical challenges for future work. We believe CodeMirage offers a rigorous and practical testbed to advance the development of robust and generalizable AI-generated code detectors.

[Arxiv](https://arxiv.org/abs/2506.11059)