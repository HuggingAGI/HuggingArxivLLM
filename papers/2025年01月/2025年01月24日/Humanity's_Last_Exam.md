# 人类的终极考验

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论的是如何通过一个新的基准测试（HLE）来评估大型语言模型（LLM）的能力，特别是针对当前基准测试无法有效评估最先进LLM能力的问题。论文的核心是介绍和推广一个新的基准测试工具，用于评估LLM在多模态和跨学科任务中的表现。这属于LLM在实际应用中的评估和改进，因此归类为“LLM应用”。` `人工智能`

> Humanity's Last Exam

# 摘要

> # 摘要
基准测试是追踪大型语言模型（LLM）能力快速进展的关键工具。然而，基准测试的难度已跟不上LLM的发展：LLMs在MMLU等流行基准测试上的准确率已超过90%，这限制了对最先进LLM能力的有效评估。为此，我们推出了“人类最后的考试”（HLE），这是一个位于人类知识前沿的多模态基准测试，旨在成为同类中最后一个覆盖广泛学科的封闭式学术基准测试。HLE包含3000个问题，涵盖数学、人文和自然科学等数十个学科，由全球学科专家开发，包含适合自动评分的多项选择题和简答题。每个问题都有一个明确且易于验证的已知解决方案，但无法通过互联网检索快速回答。最先进的LLMs在HLE上表现出较低的准确性和校准度，揭示了当前LLM能力与人类专家在封闭式学术问题上的显著差距。为了在清晰理解模型能力的基础上为研究和政策制定提供信息，我们在https://lastexam.ai上公开发布了HLE。

> Benchmarks are important tools for tracking the rapid advancements in large language model (LLM) capabilities. However, benchmarks are not keeping pace in difficulty: LLMs now achieve over 90\% accuracy on popular benchmarks like MMLU, limiting informed measurement of state-of-the-art LLM capabilities. In response, we introduce Humanity's Last Exam (HLE), a multi-modal benchmark at the frontier of human knowledge, designed to be the final closed-ended academic benchmark of its kind with broad subject coverage. HLE consists of 3,000 questions across dozens of subjects, including mathematics, humanities, and the natural sciences. HLE is developed globally by subject-matter experts and consists of multiple-choice and short-answer questions suitable for automated grading. Each question has a known solution that is unambiguous and easily verifiable, but cannot be quickly answered via internet retrieval. State-of-the-art LLMs demonstrate low accuracy and calibration on HLE, highlighting a significant gap between current LLM capabilities and the expert human frontier on closed-ended academic questions. To inform research and policymaking upon a clear understanding of model capabilities, we publicly release HLE at https://lastexam.ai.

[Arxiv](https://arxiv.org/abs/2501.14249)