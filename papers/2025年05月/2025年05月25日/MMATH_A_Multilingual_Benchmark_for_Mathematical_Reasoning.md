# MMATH：一个多语言数学推理基准测试

发布时间：2025年05月25日

`LLM应用`

> MMATH: A Multilingual Benchmark for Mathematical Reasoning

# 摘要

> 大型推理模型（如 OpenAI o1 和 DeepSeek R1）的出现，推动了复杂推理任务的发展。然而，这些模型在多语言复杂推理方面的能力仍待深入探索，现有研究主要集中在像 MGSM 这样的简单任务上。为填补这一空白，我们推出了 MMATH 基准测试，涵盖 10 种类型多样化的语言中 374 个高质量数学问题。通过 MMATH，我们发现即便是 DeepSeek R1 这样的先进模型，其跨语言表现也存在显著差异，并且存在一个严重的问题：生成了目标语言以外的回应。为解决这一问题，我们探索了包括提示和训练在内的多种策略，发现用英语进行推理并用目标语言作答，可以在提升性能的同时保持目标语言的一致性。我们的研究为提升大型语言模型的多语言推理能力提供了新见解和实用策略。我们的代码和数据可在 https://github.com/RUCAIBox/MMATH 获取。

> The advent of large reasoning models, such as OpenAI o1 and DeepSeek R1, has significantly advanced complex reasoning tasks. However, their capabilities in multilingual complex reasoning remain underexplored, with existing efforts largely focused on simpler tasks like MGSM. To address this gap, we introduce MMATH, a benchmark for multilingual complex reasoning spanning 374 high-quality math problems across 10 typologically diverse languages. Using MMATH, we observe that even advanced models like DeepSeek R1 exhibit substantial performance disparities across languages and suffer from a critical off-target issue-generating responses in unintended languages. To address this, we explore strategies including prompting and training, demonstrating that reasoning in English and answering in target languages can simultaneously enhance performance and preserve target-language consistency. Our findings offer new insights and practical strategies for advancing the multilingual reasoning capabilities of large language models. Our code and data could be found at https://github.com/RUCAIBox/MMATH.

[Arxiv](https://arxiv.org/abs/2505.19126)