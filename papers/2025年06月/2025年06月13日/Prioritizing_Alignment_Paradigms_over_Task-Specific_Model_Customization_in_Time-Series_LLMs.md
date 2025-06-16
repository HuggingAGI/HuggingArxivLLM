# 在时间序列大语言模型中，对齐范式的优先级高于任务特定的模型定制。

发布时间：2025年06月13日

`LLM应用` `时间序列`

> Prioritizing Alignment Paradigms over Task-Specific Model Customization in Time-Series LLMs

# 摘要

> 近年来，大型语言模型（LLMs）的突破性进展为医疗、金融和时空等领域带来了前所未有的时间序列推理能力。然而，现有方法多聚焦于任务特定的模型定制，如预测和异常检测，却忽视了时间序列数据本身——这些基元对于深入推理至关重要。本文主张在使用LLMs进行时间序列推理时采取根本性转变：优先考虑基于时间序列数据内在基元的对齐范式，而非任务特定的模型定制。这种调整通过在任务工程前系统地考虑数据的内在结构，解决了当前方法成本高昂、缺乏灵活性且效率低下的问题。为此，我们提出了三种对齐范式：单射对齐、桥接对齐和内部对齐，分别对应时间序列基元的领域、特性和表示，以激活LLMs的时间序列推理能力，实现经济、灵活和高效的推理。我们建议从业者采用以对齐为导向的方法选择合适的范式，并将相关文献分类到这些范式中，同时概述了有前景的研究方向。

> Recent advances in Large Language Models (LLMs) have enabled unprecedented capabilities for time-series reasoning in diverse real-world applications, including medical, financial, and spatio-temporal domains. However, existing approaches typically focus on task-specific model customization, such as forecasting and anomaly detection, while overlooking the data itself, referred to as time-series primitives, which are essential for in-depth reasoning. This position paper advocates a fundamental shift in approaching time-series reasoning with LLMs: prioritizing alignment paradigms grounded in the intrinsic primitives of time series data over task-specific model customization. This realignment addresses the core limitations of current time-series reasoning approaches, which are often costly, inflexible, and inefficient, by systematically accounting for intrinsic structure of data before task engineering. To this end, we propose three alignment paradigms: Injective Alignment, Bridging Alignment, and Internal Alignment, which are emphasized by prioritizing different aspects of time-series primitives: domain, characteristic, and representation, respectively, to activate time-series reasoning capabilities of LLMs to enable economical, flexible, and efficient reasoning. We further recommend that practitioners adopt an alignment-oriented method to avail this instruction to select an appropriate alignment paradigm. Additionally, we categorize relevant literature into these alignment paradigms and outline promising research directions.

[Arxiv](https://arxiv.org/abs/2506.11512)