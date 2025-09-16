# Dr.V：基于细粒度时空锚定的分层感知-时序-认知框架——视频幻觉诊断方法

发布时间：2025年09月15日

`Agent` `媒体与娱乐`

> Dr.V: A Hierarchical Perception-Temporal-Cognition Framework to Diagnose Video Hallucination by Fine-grained Spatial-Temporal Grounding

# 摘要

> 大型视频模型（LVMs）的最新进展极大地提升了视频理解水平。但这些模型仍受幻觉问题困扰，会生成与输入视频不符的内容。为此，我们提出Dr.V——一个涵盖感知、时间与认知层面的分层框架，旨在通过细粒度时空定位诊断视频幻觉。Dr.V包含两个核心组件：基准数据集Dr.V-Bench与卫星视频智能体Dr.V-Agent。Dr.V-Bench包含1万个实例，源自4974个覆盖多任务的视频，每个实例均附有详细的时空标注。Dr.V-Agent则通过在感知与时间层面系统应用细粒度时空定位，继而进行认知层面推理，以检测LVMs中的幻觉。这一逐步流程模拟了人类的视频理解方式，可有效识别幻觉。大量实验证实，Dr.V-Agent不仅能有效诊断幻觉，还提升了模型的可解释性与可靠性，为现实场景下的稳健视频理解提供了实用方案。相关数据与代码均已开源，地址为https://github.com/Eurekaleo/Dr.V。

> Recent advancements in large video models (LVMs) have significantly enhance video understanding. However, these models continue to suffer from hallucinations, producing content that conflicts with input videos. To address this issue, we propose Dr.V, a hierarchical framework covering perceptive, temporal, and cognitive levels to diagnose video hallucination by fine-grained spatial-temporal grounding. Dr.V comprises of two key components: a benchmark dataset Dr.V-Bench and a satellite video agent Dr.V-Agent. Dr.V-Bench includes 10k instances drawn from 4,974 videos spanning diverse tasks, each enriched with detailed spatial-temporal annotation. Dr.V-Agent detects hallucinations in LVMs by systematically applying fine-grained spatial-temporal grounding at the perceptive and temporal levels, followed by cognitive level reasoning. This step-by-step pipeline mirrors human-like video comprehension and effectively identifies hallucinations. Extensive experiments demonstrate that Dr.V-Agent is effective in diagnosing hallucination while enhancing interpretability and reliability, offering a practical blueprint for robust video understanding in real-world scenarios. All our data and code are available at https://github.com/Eurekaleo/Dr.V.

[Arxiv](https://arxiv.org/abs/2509.11866)