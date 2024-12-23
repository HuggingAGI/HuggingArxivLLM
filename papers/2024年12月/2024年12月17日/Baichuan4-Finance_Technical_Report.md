# 百川 4 - 金融技术报告

发布时间：2024年12月17日

`LLM应用` `语言模型`

> Baichuan4-Finance Technical Report

# 摘要

> 大型语言模型（LLMs）在语言理解、生成及推理方面能力出众，然而鉴于金融知识的复杂与专业，其在金融领域的潜力尚未充分发掘。在本研究中，我们介绍了百川 4 - 金融系列的研发成果，涵盖全面的基础模型百川 4 - 金融 - 基础以及与之对齐的语言模型百川 4 - 金融，它们均基于百川 4 - 涡轮基础模型构建，并专为金融领域定制。首先，我们大力构建了用于提升数据质量的详细流程。再者，在持续预训练阶段，我们提出了新颖的领域自约束训练策略，使百川 4 - 金融 - 基础既能获取金融知识，又不丧失通用能力。历经监督微调以及来自人类反馈和 AI 反馈的强化学习后，聊天模型百川 4 - 金融能够应对各类金融认证问题及现实场景应用。我们在众多广泛使用的通用数据集和两个整体金融基准上对百川 4 - 金融予以评估。评估结果显示，百川 4 - 金融 - 基础在金融任务上大幅领先几乎所有竞争基线，且在一般 LLM 基准测试中性能不减。同时，百川 4 - 金融在金融应用场景中表现更为出色，展现出其在金融 LLM 领域推动社区创新的潜力。

> Large language models (LLMs) have demonstrated strong capabilities in language understanding, generation, and reasoning, yet their potential in finance remains underexplored due to the complexity and specialization of financial knowledge. In this work, we report the development of the Baichuan4-Finance series, including a comprehensive suite of foundational Baichuan4-Finance-Base and an aligned language model Baichuan4-Finance, which are built upon Baichuan4-Turbo base model and tailored for finance domain. Firstly, we have dedicated significant effort to building a detailed pipeline for improving data quality. Moreover, in the continual pre-training phase, we propose a novel domain self-constraint training strategy, which enables Baichuan4-Finance-Base to acquire financial knowledge without losing general capabilities. After Supervised Fine-tuning and Reinforcement Learning from Human Feedback and AI Feedback, the chat model Baichuan4-Finance is able to tackle various financial certification questions and real-world scenario applications. We evaluate Baichuan4-Finance on many widely used general datasets and two holistic financial benchmarks. The evaluation results show that Baichuan4-Finance-Base surpasses almost all competitive baselines on financial tasks by significant margins without sacrificing performance on general LLM benchmarks. At the same time, Baichuan4-Finance demonstrates even more impressive performance on financial application scenarios, showcasing its potential to foster community innovation in the financial LLM field.

[Arxiv](https://arxiv.org/abs/2412.15270)