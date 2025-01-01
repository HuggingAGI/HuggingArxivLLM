# Audiopedia：知识型音频问答

发布时间：2024年12月29日

`LLM应用` `问答系统`

> Audiopedia: Audio QA with Knowledge

# 摘要

> 在本文中，我们引入了 Audiopedia 这一全新任务——具有知识的音频问答，它要求同时具备音频理解和外部知识推理能力。传统的音频问答（AQA）基准侧重于仅依靠音频就能回答的简单查询，而 Audiopedia 则针对知识密集型问题。我们设定了三个子任务：（i）单音频问答（s-AQA），即基于单个音频样本回答问题；（ii）多音频问答（m-AQA），需要对多个音频样本进行推理；（iii）检索增强音频问答（r-AQA），涉及检索相关音频来回答问题。我们对大型音频语言模型（LALMs）在这些子任务上进行了基准测试，发现性能欠佳。为此，我们提出了一个通用框架，能够适配任何 LALM，使其具备知识推理能力。我们的框架包含两个部分：（i）音频实体链接（AEL）和（ii）知识增强音频大型多模态模型（KA2LM），二者共同提升了知识密集型 AQA 任务的性能。据我们了解，这是首次通过像 Audiopedia 这样的知识密集型任务来处理高级音频理解的工作。

> In this paper, we introduce Audiopedia, a novel task called Audio Question Answering with Knowledge, which requires both audio comprehension and external knowledge reasoning. Unlike traditional Audio Question Answering (AQA) benchmarks that focus on simple queries answerable from audio alone, Audiopedia targets knowledge-intensive questions. We define three sub-tasks: (i) Single Audio Question Answering (s-AQA), where questions are answered based on a single audio sample, (ii) Multi-Audio Question Answering (m-AQA), which requires reasoning over multiple audio samples, and (iii) Retrieval-Augmented Audio Question Answering (r-AQA), which involves retrieving relevant audio to answer the question. We benchmark large audio language models (LALMs) on these sub-tasks and observe suboptimal performance. To address this, we propose a generic framework that can be adapted to any LALM, equipping them with knowledge reasoning capabilities. Our framework has two components: (i) Audio Entity Linking (AEL) and (ii) Knowledge-Augmented Audio Large Multimodal Model (KA2LM), which together improve performance on knowledge-intensive AQA tasks. To our knowledge, this is the first work to address advanced audio understanding via knowledge-intensive tasks like Audiopedia.

[Arxiv](https://arxiv.org/abs/2412.20619)