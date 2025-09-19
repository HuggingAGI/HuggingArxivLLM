# SMARTER：基于自增强大型语言模型的高效数据框架——用于改进毒性检测并提供解释

发布时间：2025年09月18日

`LLM应用` `媒体与娱乐`

> SMARTER: A Data-efficient Framework to Improve Toxicity Detection with Explanation via Self-augmenting Large Language Models

# 摘要

> 警告：本文包含冒犯性材料示例。有毒内容在社交媒体平台上已十分泛滥。为此，我们提出SMARTER——一个数据高效的两阶段可解释内容审核框架，专门基于大型语言模型（LLMs）构建。第一阶段，我们利用LLMs自身输出生成正确与错误标签的合成解释，通过偏好优化实现对齐，仅需极少人工监督。第二阶段，通过跨模型训练提升解释质量，让较弱模型在风格和语义上与较强模型保持一致。在HateXplain、Latent Hate和Implicit Hate三个基准任务上的实验显示，SMARTER能让LLMs在仅用少量训练数据时，相比标准少样本基线，宏F1值提升高达13.5%。该框架借助LLMs在分类与解释上的自我改进能力，为低资源场景提供了可扩展的解决方案。

> WARNING: This paper contains examples of offensive materials. Toxic content has become pervasive on social media platforms. We introduce SMARTER, a data-efficient two-stage framework for explainable content moderation using Large Language Models (LLMs). In Stage 1, we leverage LLMs' own outputs to generate synthetic explanations for both correct and incorrect labels, enabling alignment via preference optimization with minimal human supervision. In Stage 2, we refine explanation quality through cross-model training, allowing weaker models to align stylistically and semantically with stronger ones. Experiments on three benchmark tasks -- HateXplain, Latent Hate, and Implicit Hate -- demonstrate that SMARTER enables LLMs to achieve up to a 13.5% macro-F1 improvement over standard few-shot baselines while using only a fraction of the full training data. Our framework offers a scalable strategy for low-resource settings by harnessing LLMs' self-improving capabilities for both classification and explanation.

[Arxiv](https://arxiv.org/abs/2509.15174)