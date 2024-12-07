# Medchain：借由交互式顺序基准测试来填补 LLM 代理与临床实践之间的鸿沟

发布时间：2024年12月02日

`Agent` `临床决策`

> Medchain: Bridging the Gap Between LLM Agents and Clinical Practice through Interactive Sequential Benchmarking

# 摘要

> 临床决策制定（CDM）是一个复杂且动态的过程，对医疗保健服务意义重大，然而对于人工智能系统而言，这仍是一项艰巨挑战。尽管基于大型语言模型（LLM）的代理已通过许可考试和知识问答任务对一般医学知识进行了测试，但由于缺少能反映实际医疗实践的综合测试数据集，它们在现实场景中的CDM表现欠佳。为弥补这一差距，我们推出了MedChain，这是一个涵盖临床工作流程五个关键阶段、包含12,163个临床病例的数据集。MedChain区别于现有基准，具有现实临床实践的三个关键特性：个性化、交互性和顺序性。此外，为应对现实中的CDM挑战，我们还提出了MedChain-Agent，这是一个集成了反馈机制和MCase-RAG模块的人工智能系统，能够从过往案例中学习并调整响应。MedChain-Agent在动态收集信息和处理顺序临床任务方面展现出显著的适应性，大幅超越现有方法。相关数据集和代码将在本文被接收后发布。

> Clinical decision making (CDM) is a complex, dynamic process crucial to healthcare delivery, yet it remains a significant challenge for artificial intelligence systems. While Large Language Model (LLM)-based agents have been tested on general medical knowledge using licensing exams and knowledge question-answering tasks, their performance in the CDM in real-world scenarios is limited due to the lack of comprehensive testing datasets that mirror actual medical practice. To address this gap, we present MedChain, a dataset of 12,163 clinical cases that covers five key stages of clinical workflow. MedChain distinguishes itself from existing benchmarks with three key features of real-world clinical practice: personalization, interactivity, and sequentiality. Further, to tackle real-world CDM challenges, we also propose MedChain-Agent, an AI system that integrates a feedback mechanism and a MCase-RAG module to learn from previous cases and adapt its responses. MedChain-Agent demonstrates remarkable adaptability in gathering information dynamically and handling sequential clinical tasks, significantly outperforming existing approaches. The relevant dataset and code will be released upon acceptance of this paper.

[Arxiv](https://arxiv.org/abs/2412.01605)