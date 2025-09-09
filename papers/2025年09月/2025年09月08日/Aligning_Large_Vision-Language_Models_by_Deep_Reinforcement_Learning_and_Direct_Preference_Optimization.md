# 基于深度强化学习与直接偏好优化对齐大型视觉语言模型

发布时间：2025年09月08日

`强化学习` `基础理论`

> Aligning Large Vision-Language Models by Deep Reinforcement Learning and Direct Preference Optimization

# 摘要

> 大型视觉语言模型（LVLMs），即多模态大型语言模型，是人工智能领域的一项重大突破，让系统能够跨视觉和文本模态理解与生成内容。尽管大规模预训练已带来显著进展，但微调这些模型以使其与人类价值观对齐、适应特定任务或行为仍是一大关键难题。深度强化学习（DRL）和直接偏好优化（DPO）为这一对齐过程提供了极具潜力的框架。其中，DRL让模型能够利用奖励信号优化行为，而非单纯依赖监督偏好数据；DPO则直接使策略与偏好对齐，无需构建显式奖励模型。本综述探讨了LVLMs的微调范式，重点阐述了DRL和DPO技术如何助力模型与人类偏好及价值观对齐、提升任务性能，并实现自适应多模态交互。我们对关键方法进行了分类，考察了偏好数据的来源与奖励信号，并探讨了可扩展性、样本效率、持续学习、泛化能力及安全性等开放性挑战，旨在清晰阐释DRL和DPO如何推动稳健且与人类对齐的LVLMs的发展。

> Large Vision-Language Models (LVLMs) or multimodal large language models represent a significant advancement in artificial intelligence, enabling systems to understand and generate content across both visual and textual modalities. While large-scale pretraining has driven substantial progress, fine-tuning these models for aligning with human values or engaging in specific tasks or behaviors remains a critical challenge. Deep Reinforcement Learning (DRL) and Direct Preference Optimization (DPO) offer promising frameworks for this aligning process. While DRL enables models to optimize actions using reward signals instead of relying solely on supervised preference data, DPO directly aligns the policy with preferences, eliminating the need for an explicit reward model. This overview explores paradigms for fine-tuning LVLMs, highlighting how DRL and DPO techniques can be used to align models with human preferences and values, improve task performance, and enable adaptive multimodal interaction. We categorize key approaches, examine sources of preference data, reward signals, and discuss open challenges such as scalability, sample efficiency, continual learning, generalization, and safety. The goal is to provide a clear understanding of how DRL and DPO contribute to the evolution of robust and human-aligned LVLMs.

[Arxiv](https://arxiv.org/abs/2509.06759)