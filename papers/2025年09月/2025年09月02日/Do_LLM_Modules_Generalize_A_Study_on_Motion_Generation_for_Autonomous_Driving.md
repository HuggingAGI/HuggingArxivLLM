# # 大型语言模型模块能否泛化？——自动驾驶运动生成研究

发布时间：2025年09月02日

`LLM应用` `交通运输`

> Do LLM Modules Generalize? A Study on Motion Generation for Autonomous Driving

# 摘要

> 大型语言模型（LLMs）的最新突破不仅推动了自然语言处理的进步，还启发其在结构相似问题领域的应用——其中最引人注目的便是自动驾驶运动生成。这两个领域均涉及自回归序列建模、基于token的表示及上下文感知决策，因此LLM组件的迁移成为一种自然且日益常见的做法。然而，尽管早期尝试已显潜力，我们对哪些LLM模块真正具备可迁移性的系统性认知仍显不足。为此，本文在自动驾驶运动生成场景下，对五个关键LLM模块展开了全面评估：tokenizer设计、位置嵌入、预训练范式、后训练策略及测试时计算。通过在Waymo Sim Agents基准上的大量实验，我们发现，经过适当调整，这些模块可显著提升自动驾驶运动生成的性能。此外，我们还明确了哪些技术可实现有效迁移，分析了其他技术迁移失败的潜在原因，并探讨了自动驾驶场景所需的特定适配方案。我们在Sim Agents任务上对所提方法进行了评估，结果达到了行业领先水平。

> Recent breakthroughs in large language models (LLMs) have not only advanced natural language processing but also inspired their application in domains with structurally similar problems--most notably, autonomous driving motion generation. Both domains involve autoregressive sequence modeling, token-based representations, and context-aware decision making, making the transfer of LLM components a natural and increasingly common practice. However, despite promising early attempts, a systematic understanding of which LLM modules are truly transferable remains lacking. In this paper, we present a comprehensive evaluation of five key LLM modules--tokenizer design, positional embedding, pre-training paradigms, post-training strategies, and test-time computation--within the context of motion generation for autonomous driving. Through extensive experiments on the Waymo Sim Agents benchmark, we demonstrate that, when appropriately adapted, these modules can significantly improve performance for autonomous driving motion generation. In addition, we identify which techniques can be effectively transferred, analyze the potential reasons for the failure of others, and discuss the specific adaptations needed for autonomous driving scenarios. We evaluate our method on the Sim Agents task and achieve competitive results.

[Arxiv](https://arxiv.org/abs/2509.02754)