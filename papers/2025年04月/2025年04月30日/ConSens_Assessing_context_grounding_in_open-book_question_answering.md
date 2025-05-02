# ConSens：评估开卷式问答中的上下文定位能力

发布时间：2025年04月30日

`LLM应用

摘要讨论了大型语言模型在开卷问答任务中的应用，提出了评估模型是否依赖提供的上下文的方法，属于应用层面的优化和评估。` `问答系统`

> ConSens: Assessing context grounding in open-book question answering

# 摘要

> 大型语言模型（LLMs）在开卷问答（QA）领域取得了显著成功，该任务要求根据提供的外部上下文生成答案。然而，开卷问答面临一个严峻挑战：如何确保模型的回答基于提供的上下文，而非其内置的知识参数，因为这些参数可能过时、不完整或错误。现有评估方法主要采用“将LLM作为裁判”的思路，但存在偏见、扩展性问题以及对外部系统的高昂依赖等显著限制。为解决这些问题，我们提出了一种创新的评估指标，通过比较两种条件下模型回答的困惑度（perplexity）：一种是提供上下文时，另一种是不提供上下文时。所得分数量化了模型答案对所提供上下文的依赖程度。通过一系列实验，我们验证了该指标的有效性，能够有效识别给定答案是否基于提供的上下文。与现有方法不同，该指标具有计算高效、可解释且适用性强等优势，为评估开卷问答系统中上下文的利用提供了可扩展和实用的解决方案。


> Large Language Models (LLMs) have demonstrated considerable success in open-book question answering (QA), where the task requires generating answers grounded in a provided external context. A critical challenge in open-book QA is to ensure that model responses are based on the provided context rather than its parametric knowledge, which can be outdated, incomplete, or incorrect. Existing evaluation methods, primarily based on the LLM-as-a-judge approach, face significant limitations, including biases, scalability issues, and dependence on costly external systems. To address these challenges, we propose a novel metric that contrasts the perplexity of the model response under two conditions: when the context is provided and when it is not. The resulting score quantifies the extent to which the model's answer relies on the provided context. The validity of this metric is demonstrated through a series of experiments that show its effectiveness in identifying whether a given answer is grounded in the provided context. Unlike existing approaches, this metric is computationally efficient, interpretable, and adaptable to various use cases, offering a scalable and practical solution to assess context utilization in open-book QA systems.

[Arxiv](https://arxiv.org/abs/2505.00065)