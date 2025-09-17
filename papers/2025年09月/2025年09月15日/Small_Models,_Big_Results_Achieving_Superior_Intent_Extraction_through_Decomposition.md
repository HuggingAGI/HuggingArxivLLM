# 小模型，大成效：借助分解实现优异的意图提取

发布时间：2025年09月15日

`Agent` `基础理论`

> Small Models, Big Results: Achieving Superior Intent Extraction through Decomposition

# 摘要

> 从用户界面（UI）交互轨迹中解读用户意图，是智能体开发中一个极具挑战却又至关重要的前沿课题。尽管大型数据中心级多模态大语言模型（MLLMs）具备更强的能力应对这类序列的复杂性，但能在设备端运行、提供隐私保护、低成本且低延迟用户体验的小型模型，却难以准确推断用户意图。为此，我们提出一种新颖的分解式方法：首先，对交互过程进行结构化总结，提取每个用户操作的关键信息；其次，基于聚合后的总结，利用微调模型进行意图提取。该方法不仅提升了资源受限模型的意图理解能力，甚至超越了大型MLLMs的基础性能。

> Understanding user intents from UI interaction trajectories remains a challenging, yet crucial, frontier in intelligent agent development. While massive, datacenter-based, multi-modal large language models (MLLMs) possess greater capacity to handle the complexities of such sequences, smaller models which can run on-device to provide a privacy-preserving, low-cost, and low-latency user experience, struggle with accurate intent inference. We address these limitations by introducing a novel decomposed approach: first, we perform structured interaction summarization, capturing key information from each user action. Second, we perform intent extraction using a fine-tuned model operating on the aggregated summaries. This method improves intent understanding in resource-constrained models, even surpassing the base performance of large MLLMs.

[Arxiv](https://arxiv.org/abs/2509.12423)