# 情感分析中的针对性蒸馏方法

发布时间：2025年03月05日

`LLM应用` `情感分析` `人工智能`

> Targeted Distillation for Sentiment Analysis

# 摘要

> 本文提出了一种紧凑型模型，通过从先进的大型语言模型（LLMs）中进行有针对性的蒸馏，实现了强大的情感分析能力。我们的方法将蒸馏目标分解为两个关键组件：与情感相关知识和任务对齐。为此，我们提出了一种两阶段蒸馏框架。第一阶段，知识驱动蒸馏（	extsc{KnowDist}），转移与情感相关知识以增强基础情感分析能力。第二阶段，上下文学习蒸馏（	extsc{ICLDist}），转移特定任务的提示遵循能力以优化任务对齐。为了全面评估，我们引入了	extsc{SentiBench}，这是一个全面的情感分析基准，包含12个数据集的3种任务类别。在该基准上的实验表明，我们的模型在模型大小和性能之间实现了有效的平衡，并与现有的小型LLMs相比表现出强大的竞争力。

> This paper presents a compact model that achieves strong sentiment analysis capabilities through targeted distillation from advanced large language models (LLMs). Our methodology decouples the distillation target into two key components: sentiment-related knowledge and task alignment. To transfer these components, we propose a two-stage distillation framework. The first stage, knowledge-driven distillation (\textsc{KnowDist}), transfers sentiment-related knowledge to enhance fundamental sentiment analysis capabilities. The second stage, in-context learning distillation (\textsc{ICLDist}), transfers task-specific prompt-following abilities to optimize task alignment. For evaluation, we introduce \textsc{SentiBench}, a comprehensive sentiment analysis benchmark comprising 3 task categories across 12 datasets. Experiments on this benchmark demonstrate that our model effectively balances model size and performance, showing strong competitiveness compared to existing small-scale LLMs.

[Arxiv](https://arxiv.org/abs/2503.03225)