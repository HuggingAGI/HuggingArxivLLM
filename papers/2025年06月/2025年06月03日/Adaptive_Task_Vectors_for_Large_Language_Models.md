# 面向大型语言模型的自适应任务向量

发布时间：2025年06月03日

`LLM理论`

> Adaptive Task Vectors for Large Language Models

# 摘要

> 上下文学习（ICL）让大型语言模型（LLMs）无需参数更新，仅通过在提示中加入少量演示样例即可完成任务。尽管ICL表现出色，但它也存在一些局限，如对演示顺序敏感、上下文长度限制以及计算效率不高。为了解决这些问题，基于任务向量的方法将任务信息压缩为单一向量。然而，这些方法通常基于固定的一组演示样例构建任务向量，并在所有输入查询中重复使用，而未针对具体输入进行调整。这种局限可能导致模型难以有效适应输入查询与演示不匹配的情况，进而影响其在未见任务上的泛化性能。为克服这一限制，我们提出了自适应任务向量（ATV），这是一种简单而有效的框架，能够根据每个输入查询动态生成任务向量。ATV采用小型语言模型生成任务向量，随后将其转换以匹配目标LLM的架构，并指导其输出生成。与ICL和传统基于向量的方法不同，ATV能够动态生成针对每个具体输入查询和任务的定制化任务向量。因此，ATV在性能和泛化能力上表现优异，即使对于未见任务也是如此。此外，我们还提供了一种理论分析，表明在相等的秩预算下，ATV在表达能力上与LoRA等效，且比Prefix-Tuning更具表达性，从而为其实现优势提供了形式化支持。

> In-Context Learning (ICL) enables Large Language Models (LLMs) to perform tasks without parameter updates by conditioning on a few demonstrations provided in the prompt. Despite its success, ICL suffers from several limitations, including sensitivity to demonstration order, context length constraints, and computational inefficiency. To address these challenges, task vector-based approaches compress task information into a single vector. However, these methods typically construct task vectors from fixed sets of demonstrations and reuse them across input queries, without conditioning on the specific input. This limitation can lead models to struggle with effective adaptation when the input query is not well aligned with the underlying demonstrations, consequently degrading their generalization performance on unseen tasks. To overcome this limitation, we propose Adaptive Task Vectors (ATV), a simple and effective framework that dynamically generates task vectors conditioned on each input query. ATV employs a small language model to generate task vectors, which are then transformed to match the target LLM's architecture and applied to guide its output generation. In contrast to ICL and previous vector-based approaches, which rely on fixed demonstration sets and their corresponding vectors, ATV dynamically generates task vectors tailored to each specific input query and task. Consequently, ATV demonstrates strong performance and generalization capabilities, even for unseen tasks. Furthermore, we provide a theoretical analysis indicating that ATV is expressively equivalent to LoRA under equal rank budgets and more expressive than Prefix-Tuning, thereby offering formal support for its representational advantage.

[Arxiv](https://arxiv.org/abs/2506.03426)