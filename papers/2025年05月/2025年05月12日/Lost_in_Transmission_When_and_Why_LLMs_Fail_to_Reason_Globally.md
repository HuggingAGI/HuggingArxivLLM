# 迷失在传输：大型语言模型为何无法全局推理？

发布时间：2025年05月12日

`LLM理论` `人工智能`

> Lost in Transmission: When and Why LLMs Fail to Reason Globally

# 摘要

> 尽管基于Transformer的大型语言模型（LLMs）在许多任务中表现出色，但在需要处理输入大部分内容的复杂推理任务上仍存在瓶颈。我们认为，这些挑战源于LLMs内部信息流动的容量限制。为此，我们提出了有界注意力前缀 oracle（BAPO）模型，这是一个新的计算框架，用于建模LLMs内部通信机制——注意力头的带宽约束。我们发现，像图可达性等重要的推理问题需要BAPO具备高通信带宽才能解决；我们将这类问题称为BAPO难题。实验结果验证了我们的理论预测：GPT-4、Claude 和 Gemini 在 BAPO 容易的任务上表现优异，但在相对较小的 BAPO难题上却难以应对。此外，BAPO 还揭示了链式思维（CoT）的另一大优势：我们证明，通过 CoT 分解任务，可以将任何 BAPO难题转化为 BAPO 容易的问题。我们的研究不仅为理解 LLM 的失败提供了理论依据，还为缓解带宽限制的架构和推理方法设计提供了方向。

> Despite their many successes, transformer-based large language models (LLMs) continue to struggle with tasks that require complex reasoning over large parts of their input. We argue that these failures arise due to capacity limits on the accurate flow of information within LLMs. To formalize this issue, we introduce the bounded attention prefix oracle (BAPO) model, a new computational framework that models bandwidth constraints on attention heads, the mechanism for internal communication in LLMs. We show that several important reasoning problems like graph reachability require high communication bandwidth for BAPOs to solve; we call these problems BAPO-hard. Our experiments corroborate our theoretical predictions: GPT-4, Claude, and Gemini succeed on BAPO-easy tasks and fail even on relatively small BAPO-hard tasks. BAPOs also reveal another benefit of chain of thought (CoT): we prove that breaking down a task using CoT can turn any BAPO-hard problem into a BAPO-easy one. Our results offer principled explanations for key LLM failures and suggest directions for architectures and inference methods that mitigate bandwidth limits.

[Arxiv](https://arxiv.org/abs/2505.08140)