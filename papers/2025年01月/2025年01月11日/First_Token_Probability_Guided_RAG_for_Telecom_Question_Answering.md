# 基于首个令牌概率引导的RAG在电信问答中的应用

发布时间：2025年01月11日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在电信领域多项选择题回答（MCQA）中的应用，并提出了一种基于首个令牌概率引导的RAG框架。论文的核心内容围绕如何通过RAG框架优化检索质量和减少幻觉，属于RAG领域的研究。` `问答系统`

> First Token Probability Guided RAG for Telecom Question Answering

# 摘要

> 大型语言模型（LLMs）因其强大的通用能力备受瞩目。在需要复杂领域知识的应用中，检索增强生成（RAG）在整合领域特定信息方面表现出显著优势。然而，现有RAG研究尚未完全解决电信领域中的多项选择题回答（MCQA）挑战，尤其是在检索质量和减少幻觉方面。为此，我们提出了一种基于首个令牌概率引导的RAG框架。该框架利用置信度分数优化关键超参数（如块数和块窗口大小），并动态调整上下文。我们的方法首先检索最相关的块，生成一个令牌作为潜在答案，随后将所有选项的概率归一化为置信度分数，用于指导上下文的动态调整。通过基于这些分数迭代优化超参数，我们能够持续提升RAG性能。实验验证了该框架的有效性，展示了其在提升领域特定MCQA任务准确性方面的潜力。

> Large Language Models (LLMs) have garnered significant attention for their impressive general-purpose capabilities. For applications requiring intricate domain knowledge, Retrieval-Augmented Generation (RAG) has shown a distinct advantage in incorporating domain-specific information into LLMs. However, existing RAG research has not fully addressed the challenges of Multiple Choice Question Answering (MCQA) in telecommunications, particularly in terms of retrieval quality and mitigating hallucinations. To tackle these challenges, we propose a novel first token probability guided RAG framework. This framework leverages confidence scores to optimize key hyperparameters, such as chunk number and chunk window size, while dynamically adjusting the context. Our method starts by retrieving the most relevant chunks and generates a single token as the potential answer. The probabilities of all options are then normalized to serve as confidence scores, which guide the dynamic adjustment of the context. By iteratively optimizing the hyperparameters based on these confidence scores, we can continuously improve RAG performance. We conducted experiments to validate the effectiveness of our framework, demonstrating its potential to enhance accuracy in domain-specific MCQA tasks.

[Arxiv](https://arxiv.org/abs/2501.06468)