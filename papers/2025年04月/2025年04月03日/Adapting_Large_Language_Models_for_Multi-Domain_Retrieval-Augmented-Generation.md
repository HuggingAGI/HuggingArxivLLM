# # 将大型语言模型应用于跨领域检索增强生成

发布时间：2025年04月03日

`RAG` `跨领域`

> Adapting Large Language Models for Multi-Domain Retrieval-Augmented-Generation

# 摘要

> 检索增强生成（RAG）虽然提升了大型语言模型的事实准确性，但在多领域应用中仍面临两大挑战：缺乏多样化的基准测试和跨领域泛化能力不足。本研究的两大贡献分别是：首先，我们引入了一个涵盖13个领域、整合了8个来源的多样化基准测试集；其次，我们系统性地评估了典型RAG微调策略的跨领域泛化性能。研究发现，标准微调方法难以实现有效泛化，而采用教师生成标签的序列级蒸馏方法，通过提供更连贯的监督信号，显著提升了跨领域性能。这些发现为提升多领域RAG的鲁棒性提供了关键策略。

> Retrieval-Augmented Generation (RAG) enhances LLM factuality, but multi-domain applications face challenges like lack of diverse benchmarks and poor out-of-domain generalization. The first contribution of this work is to introduce a diverse benchmark comprising a variety of question-answering tasks from 8 sources and covering 13 domains. Our second contribution consists in systematically testing out-of-domain generalization for typical RAG tuning strategies. While our findings reveal that standard fine-tuning fails to generalize effectively, we show that sequence-level distillation with teacher-generated labels improves out-of-domain performance by providing more coherent supervision. Our findings highlight key strategies for improving multi-domain RAG robustness.

[Arxiv](https://arxiv.org/abs/2504.02411)