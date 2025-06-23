# 从教师到学生：通过模型蒸馏追踪记忆过程

发布时间：2025年06月19日

`LLM理论` `人工智能` `机器学习`

> From Teacher to Student: Tracking Memorization Through Model Distillation

# 摘要

> 大型语言模型（LLMs）因能记忆部分训练数据而备受关注，同时也引发了隐私和安全方面的担忧。虽然先前研究主要聚焦于预训练模型的记忆机制，但知识蒸馏（KD）对记忆的影响尚不明确。本研究旨在探究不同KD方法如何影响大型教师模型蒸馏为小型学生模型时的微调任务数据记忆。研究表明，将大型教师模型蒸馏为小型学生模型，不仅降低了计算成本和模型规模，还显著降低了与标准微调方法相比的记忆风险。

> Large language models (LLMs) are known to memorize parts of their training data, raising important concerns around privacy and security. While previous research has focused on studying memorization in pre-trained models, much less is known about how knowledge distillation (KD) affects memorization.In this study, we explore how different KD methods influence the memorization of fine-tuned task data when a large teacher model is distilled into smaller student variants.This study demonstrates that distilling a larger teacher model, fine-tuned on a dataset, into a smaller variant not only lowers computational costs and model size but also significantly reduces the memorization risks compared to standard fine-tuning approaches.

[Arxiv](https://arxiv.org/abs/2506.16170)