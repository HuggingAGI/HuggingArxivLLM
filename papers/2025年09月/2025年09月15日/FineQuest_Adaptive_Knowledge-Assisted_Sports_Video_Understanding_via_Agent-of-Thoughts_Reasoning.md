# FineQuest：借助思维智能体推理的自适应知识辅助体育视频理解

发布时间：2025年09月15日

`LLM应用` `媒体与娱乐`

> FineQuest: Adaptive Knowledge-Assisted Sports Video Understanding via Agent-of-Thoughts Reasoning

# 摘要

> 基于大型语言模型（LLMs）的视频问答（VideoQA）虽在通用视频理解领域展现潜力，但在复杂的体育视频场景中仍面临严峻挑战。为此，我们提出首个无需训练的框架FineQuest，其核心是受认知科学启发的双模式推理机制：对简单体育查询采用反应式推理，对复杂查询则启用审慎式推理。为弥合通用模型与体育专业理解的知识鸿沟，FineQuest融入了SSGraph——一个覆盖九类运动的多模态体育知识场景图，通过编码视觉实例与领域专属术语提升推理精度。此外，我们还基于FineGym和FineDiving数据集构建了两个全新体育视频问答基准Gym-QA与Diving-QA，支持多样化、全方位的性能评估。实验表明，FineQuest不仅在这两个新基准及现有SPORTU数据集上均刷新性能纪录，还保留了强大的通用视频问答能力。

> Video Question Answering (VideoQA) based on Large Language Models (LLMs) has shown potential in general video understanding but faces significant challenges when applied to the inherently complex domain of sports videos. In this work, we propose FineQuest, the first training-free framework that leverages dual-mode reasoning inspired by cognitive science: i) Reactive Reasoning for straightforward sports queries and ii) Deliberative Reasoning for more complex ones. To bridge the knowledge gap between general-purpose models and domain-specific sports understanding, FineQuest incorporates SSGraph, a multimodal sports knowledge scene graph spanning nine sports, which encodes both visual instances and domain-specific terminology to enhance reasoning accuracy. Furthermore, we introduce two new sports VideoQA benchmarks, Gym-QA and Diving-QA, derived from the FineGym and FineDiving datasets, enabling diverse and comprehensive evaluation. FineQuest achieves state-of-the-art performance on these benchmarks as well as the existing SPORTU dataset, while maintains strong general VideoQA capabilities.

[Arxiv](https://arxiv.org/abs/2509.11796)