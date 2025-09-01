# 超越质量：通过大型语言模型释放广告标题生成的多样性

发布时间：2025年08月26日

`LLM应用` `零售与电商`

> Beyond Quality: Unlocking Diversity in Ad Headline Generation with Large Language Models

# 摘要

> 广告标题生成在现代广告中至关重要，质量与多样性是吸引各类受众的核心要素。当前方法多聚焦于优化语言模型的标题质量或点击率（CTR），却常忽视多样性需求，导致输出同质化。为此，我们提出DIVER——一个基于大型语言模型（LLMs）的新型框架，可同时优化多样性与质量。我们首先设计语义与风格感知的数据生成管道，能自动生成包含广告内容与多个多样标题的高质量训练对。为实现在单次前向传播中生成高质量、多样化广告标题的目标，我们提出结合监督微调（SFT）与强化学习（RL）的多阶段多目标优化框架。在真实工业数据集上的实验表明，DIVER能有效平衡质量与多样性。该框架已部署于服务数亿用户的大规模内容分享平台，广告主价值（ADVV）与点击率（CTR）分别提升4.0%和1.4%。

> The generation of ad headlines plays a vital role in modern advertising, where both quality and diversity are essential to engage a broad range of audience segments. Current approaches primarily optimize language models for headline quality or click-through rates (CTR), often overlooking the need for diversity and resulting in homogeneous outputs. To address this limitation, we propose DIVER, a novel framework based on large language models (LLMs) that are jointly optimized for both diversity and quality. We first design a semantic- and stylistic-aware data generation pipeline that automatically produces high-quality training pairs with ad content and multiple diverse headlines. To achieve the goal of generating high-quality and diversified ad headlines within a single forward pass, we propose a multi-stage multi-objective optimization framework with supervised fine-tuning (SFT) and reinforcement learning (RL). Experiments on real-world industrial datasets demonstrate that DIVER effectively balances quality and diversity. Deployed on a large-scale content-sharing platform serving hundreds of millions of users, our framework improves advertiser value (ADVV) and CTR by 4.0% and 1.4%.

[Arxiv](https://arxiv.org/abs/2508.18739)