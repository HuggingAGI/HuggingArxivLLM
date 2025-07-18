# UniSLU：基于异质跨任务数据集的统一语音语言理解

发布时间：2025年07月17日

`LLM应用` `语音处理`

> UniSLU: Unified Spoken Language Understanding from Heterogeneous Cross-Task Datasets

# 摘要

> 语音语言理解（SLU）在以语音为中心的多媒体应用中至关重要，它让机器能够理解会议、采访和客服互动等场景中的口语。SLU 包括自动语音识别（ASR）、口语命名实体识别（NER）和口语情感分析（SA）等多个任务。然而，现有方法通常为每个任务（如口语 NER 和 SA）使用不同的模型架构，这不仅显著增加系统复杂性，还限制了跨任务的交互，并未能充分利用跨任务的异构数据集。为了解决这些问题，我们提出了 UniSLU，这是一个在单个架构内联合建模多个 SLU 任务的统一框架。具体来说，我们为多样化的 SLU 任务设计了统一的表示方法，从而能够充分利用跨任务的异构数据集。在此基础上，我们提出了一种统一的生成方法，联合建模 ASR、口语 NER 和 SA 任务，增强了任务之间的交互，并实现了与大型语言模型的无缝集成，充分挖掘其强大的生成能力。在公共 SLU 数据集上的大量实验表明，我们的方法显著优于多种基准方法，展现出卓越的性能，特别适合应用于基于语音的现实世界多媒体场景。我们将在 github 上开源所有代码和模型，以支持未来的研究工作。

> Spoken Language Understanding (SLU) plays a crucial role in speech-centric multimedia applications, enabling machines to comprehend spoken language in scenarios such as meetings, interviews, and customer service interactions. SLU encompasses multiple tasks, including Automatic Speech Recognition (ASR), spoken Named Entity Recognition (NER), and spoken Sentiment Analysis (SA). However, existing methods often rely on separate model architectures for individual tasks such as spoken NER and SA, which increases system complexity, limits cross-task interaction, and fails to fully exploit heterogeneous datasets available across tasks. To address these limitations, we propose UniSLU, a unified framework that jointly models multiple SLU tasks within a single architecture. Specifically, we propose a unified representation for diverse SLU tasks, enabling full utilization of heterogeneous datasets across multiple tasks. Built upon this representation, we propose a unified generative method that jointly models ASR, spoken NER, and SA tasks, enhancing task interactions and enabling seamless integration with large language models to harness their powerful generative capabilities. Extensive experiments on public SLU datasets demonstrate the effectiveness of our approach, achieving superior SLU performance compared to several benchmark methods, making it well-suited for real-world speech-based multimedia scenarios. We will release all code and models at github to facilitate future research.

[Arxiv](https://arxiv.org/abs/2507.12951)