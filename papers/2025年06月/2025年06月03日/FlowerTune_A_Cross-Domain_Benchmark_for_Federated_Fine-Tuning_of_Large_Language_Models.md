# <翻译失败>

发布时间：2025年06月03日

`LLM应用`

> FlowerTune: A Cross-Domain Benchmark for Federated Fine-Tuning of Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多领域已达到顶尖水准，但其发展仍高度依赖大量公开数据，这引发了数据稀缺及难以获取领域特定敏感信息的担忧。联邦学习（FL）提供了一个极具吸引力的框架，通过在预训练的LLMs上进行去中心化微调，无需共享原始数据，从而应对这些挑战。然而，预训练LLMs在FL环境下的兼容性和性能仍鲜有研究。我们推出FlowerTune LLM Leaderboard——首个跨领域联邦微调基准测试套件，涵盖通用NLP、金融、医疗和编程四大领域。每个领域均包含联邦指令微调数据集及专属评估指标。通过协作、开源和社区驱动的方式，我们对26个不同聚合与微调策略下的预训练LLMs进行了首次全面对比，为模型性能、资源限制及领域适应提供了实用见解。这项工作为开发隐私保护、领域专用的LLMs奠定了基础，助力其在现实世界中的应用。

> Large Language Models (LLMs) have achieved state-of-the-art results across diverse domains, yet their development remains reliant on vast amounts of publicly available data, raising concerns about data scarcity and the lack of access to domain-specific, sensitive information. Federated Learning (FL) presents a compelling framework to address these challenges by enabling decentralized fine-tuning on pre-trained LLMs without sharing raw data. However, the compatibility and performance of pre-trained LLMs in FL settings remain largely under explored. We introduce the FlowerTune LLM Leaderboard, a first-of-its-kind benchmarking suite designed to evaluate federated fine-tuning of LLMs across four diverse domains: general NLP, finance, medical, and coding. Each domain includes federated instruction-tuning datasets and domain-specific evaluation metrics. Our results, obtained through a collaborative, open-source and community-driven approach, provide the first comprehensive comparison across 26 pre-trained LLMs with different aggregation and fine-tuning strategies under federated settings, offering actionable insights into model performance, resource constraints, and domain adaptation. This work lays the foundation for developing privacy-preserving, domain-specialized LLMs for real-world applications.

[Arxiv](https://arxiv.org/abs/2506.02961)