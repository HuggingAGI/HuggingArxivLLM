# # CVBench：针对复杂多模态理解与推理的跨视频协同作用评估

发布时间：2025年08月28日

`LLM应用` `媒体与娱乐`

> CVBench: Evaluating Cross-Video Synergies for Complex Multimodal Understanding and Reasoning

# 摘要

> 尽管多模态大型语言模型（MLLMs）在单视频任务（如视频问答）中表现出色，但它们在跨视频场景下的能力却严重未被挖掘。然而，这种能力在现实应用中至关重要，例如多摄像头监控和跨视频流程学习。为填补这一空白，我们提出了CVBench——首个旨在严格评估跨视频关系推理能力的综合基准。CVBench包含1000个问答对，分为三个层级：跨视频对象关联（识别共享实体）、跨视频事件关联（链接时间或因果事件链）以及跨视频复杂推理（整合常识与领域知识）。该基准基于五个不同领域的视频集群（如体育、生活记录）构建，要求模型整合动态视觉上下文中的信息。我们在零样本或思维链提示范式下，对10余款主流MLLMs（包括GPT-4o、Gemini-2.0-flash、Qwen2.5-VL）进行了全面评估。核心发现揭示了显著的性能差距：即便是GPT-4o等顶级模型，在因果推理任务上的准确率也仅为60%，而人类表现则达到91%。关键的是，我们的分析指出了当前MLLM架构的固有瓶颈：跨视频上下文保留能力不足，以及对重叠实体的消歧能力较弱。CVBench为诊断和提升多视频推理能力奠定了严格框架，并为下一代MLLMs提供了架构设计思路。相关数据与评估代码可访问https://github.com/Hokhim2/CVBench。

> While multimodal large language models (MLLMs) exhibit strong performance on single-video tasks (e.g., video question answering), their ability across multiple videos remains critically underexplored. However, this capability is essential for real-world applications, including multi-camera surveillance and cross-video procedural learning. To bridge this gap, we present CVBench, the first comprehensive benchmark designed to assess cross-video relational reasoning rigorously. CVBench comprises 1,000 question-answer pairs spanning three hierarchical tiers: cross-video object association (identifying shared entities), cross-video event association (linking temporal or causal event chains), and cross-video complex reasoning (integrating commonsense and domain knowledge). Built from five domain-diverse video clusters (e.g., sports, life records), the benchmark challenges models to synthesise information across dynamic visual contexts. Extensive evaluation of 10+ leading MLLMs (including GPT-4o, Gemini-2.0-flash, Qwen2.5-VL) under zero-shot or chain-of-thought prompting paradigms. Key findings reveal stark performance gaps: even top models, such as GPT-4o, achieve only 60% accuracy on causal reasoning tasks, compared to the 91% accuracy of human performance. Crucially, our analysis reveals fundamental bottlenecks inherent in current MLLM architectures, notably deficient inter-video context retention and poor disambiguation of overlapping entities. CVBench establishes a rigorous framework for diagnosing and advancing multi-video reasoning, offering architectural insights for next-generation MLLMs. The data and evaluation code are available at https://github.com/Hokhim2/CVBench.

[Arxiv](https://arxiv.org/abs/2508.19542)