# DebateBench：专为大型语言模型设计的充满挑战性的长上下文推理基准测试

发布时间：2025年02月10日

`其他` `辩论领域`

> DebateBench: A Challenging Long Context Reasoning Benchmark For Large Language Models

# 摘要

> 我们推出DebateBench，这是一个全新的数据集，包含了一些世界上最负盛名的辩论比赛的大量辩论记录和元数据。该数据集收录了来自著名辩论锦标赛的英国议会制辩论，涵盖多种多样的主题，并附有基于官方裁决数据的详细演讲评分和队伍排名。我们精选了32场辩论中的256篇演讲，每场辩论时长均超过1小时，每篇输入的平均令牌数为32,000。DebateBench特别针对长上下文、大规模推理任务设计，为评估现代大型语言模型（LLMs）在参与论证、商讨以及与人类专家保持一致方面的能力提供了一个基准。要在DebateBench上表现良好，LLMs必须通过上下文学习理解辩论规则和评价标准，然后分析8篇长达7分钟的演讲，并综合所有发言者的论点给出最终结果。我们使用GPT o1、GPT-4o和Claude Haiku进行的初步评估显示，LLMs在DebateBench上的表现不尽如人意，凸显了开发更先进方法以提升其性能的必要性。

> We introduce DebateBench, a novel dataset consisting of an extensive collection of transcripts and metadata from some of the world's most prestigious competitive debates. The dataset consists of British Parliamentary debates from prestigious debating tournaments on diverse topics, annotated with detailed speech-level scores and house rankings sourced from official adjudication data. We curate 256 speeches across 32 debates with each debate being over 1 hour long with each input being an average of 32,000 tokens. Designed to capture long-context, large-scale reasoning tasks, DebateBench provides a benchmark for evaluating modern large language models (LLMs) on their ability to engage in argumentation, deliberation, and alignment with human experts. To do well on DebateBench, the LLMs must perform in-context learning to understand the rules and evaluation criteria of the debates, then analyze 8 seven minute long speeches and reason about the arguments presented by all speakers to give the final results. Our preliminary evaluation using GPT o1, GPT-4o, and Claude Haiku, shows that LLMs struggle to perform well on DebateBench, highlighting the need to develop more sophisticated techniques for improving their performance.

[Arxiv](https://arxiv.org/abs/2502.06279)