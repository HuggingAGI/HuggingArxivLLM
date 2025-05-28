# 基于语音大语言模型的二语口语能力评估

发布时间：2025年05月27日

`LLM应用` `教育技术`

> Assessment of L2 Oral Proficiency using Speech Large Language Models

# 摘要

> 随着第二语言英语学习者人数的增加，开发用于口语评估的自动评分系统变得尤为重要。传统上，统计模型、文本编码器和自监督语音模型曾被用于这一领域。然而，级联系统存在信息丢失的问题，而端到端评分器也有其局限性。随着近期多模态大型语言模型（LLMs）的进步，我们旨在探索其作为第二语言口语能力评分器的潜力，并克服现有问题。在这项研究中，我们比较了使用回归和分类目标的各种训练策略。我们的结果显示，语音LLMs在两个数据集上超越了所有先前有竞争力的基线，展现出显著优势。此外，经过训练的评分器在跨部分或跨任务评估中也表现出强大的泛化能力，这得益于LLM预训练过程中所获取的音频理解知识。

> The growing population of L2 English speakers has increased the demand for developing automatic graders for spoken language assessment (SLA). Historically, statistical models, text encoders, and self-supervised speech models have been utilised for this task. However, cascaded systems suffer from the loss of information, while E2E graders also have limitations. With the recent advancements of multi-modal large language models (LLMs), we aim to explore their potential as L2 oral proficiency graders and overcome these issues. In this work, we compare various training strategies using regression and classification targets. Our results show that speech LLMs outperform all previous competitive baselines, achieving superior performance on two datasets. Furthermore, the trained grader demonstrates strong generalisation capabilities in the cross-part or cross-task evaluation, facilitated by the audio understanding knowledge acquired during LLM pre-training.

[Arxiv](https://arxiv.org/abs/2505.21148)