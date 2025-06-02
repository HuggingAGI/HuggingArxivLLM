# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月30日

`LLM理论` `模型蒸馏` `数学推理`

> Harnessing Negative Signals: Reinforcement Distillation from Teacher Data for LLM Reasoning

# 摘要

> # 摘要
近期模型蒸馏领域的最新进展表明，来自先进推理模型（如DeepSeek-R1、OpenAI的o1）的数据能够有效将复杂的推理能力转移给更小、更高效的“学生”模型。然而，传统的做法是使用拒绝采样，丢弃错误的推理示例——这些数据虽然宝贵，但却经常被忽视。本文探讨了一个关键问题：如何充分利用正负蒸馏推理轨迹，在线下环境中最大限度地提升LLM的推理性能？

为此，我们提出了强化蒸馏（REDI），这是一个两阶段的框架。第一阶段通过监督微调（SFT）从正面轨迹中学习。第二阶段则利用我们提出的REDI目标，进一步结合正负轨迹对模型进行优化。这一创新目标是一个简单且无需参考的损失函数，在蒸馏背景下，其表现优于DPO和SimPO等 established methods。

我们的实证评估表明，相比于基线的拒绝采样SFT或SFT结合DPO/SimPO，REDI在数学推理任务中表现更优。值得注意的是，仅在开放的Open-R1数据集上的131k正负示例上进行后训练的Qwen-REDI-1.5B模型，在MATH-500（pass@1）上达到了83.1%的得分。其性能在多个数学推理基准上与DeepSeek-R1-Distill-Qwen-1.5B（一个在800k专有数据上进行后训练的模型）相匹配或超越，从而为使用公开可用数据进行线下后训练的1.5B规模模型树立了新的state-of-the-art。


> Recent advances in model distillation demonstrate that data from advanced reasoning models (e.g., DeepSeek-R1, OpenAI's o1) can effectively transfer complex reasoning abilities to smaller, efficient student models. However, standard practices employ rejection sampling, discarding incorrect reasoning examples -- valuable, yet often underutilized data. This paper addresses the critical question: How can both positive and negative distilled reasoning traces be effectively leveraged to maximize LLM reasoning performance in an offline setting? To this end, We propose Reinforcement Distillation (REDI), a two-stage framework. Stage 1 learns from positive traces via Supervised Fine-Tuning (SFT). Stage 2 further refines the model using both positive and negative traces through our proposed REDI objective. This novel objective is a simple, reference-free loss function that outperforms established methods like DPO and SimPO in this distillation context. Our empirical evaluations demonstrate REDI's superiority over baseline Rejection Sampling SFT or SFT combined with DPO/SimPO on mathematical reasoning tasks. Notably, the Qwen-REDI-1.5B model, post-trained on just 131k positive and negative examples from the open Open-R1 dataset, achieves an 83.1% score on MATH-500 (pass@1). Its performance matches or surpasses that of DeepSeek-R1-Distill-Qwen-1.5B (a model post-trained on 800k proprietary data) across various mathematical reasoning benchmarks, establishing a new state-of-the-art for 1.5B models post-trained offline with openly available data.

[Arxiv](https://arxiv.org/abs/2505.24850)