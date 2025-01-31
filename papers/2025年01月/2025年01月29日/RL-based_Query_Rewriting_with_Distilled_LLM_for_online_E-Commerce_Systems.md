# 基于强化学习的查询重写与蒸馏LLM在电商系统中的应用

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了在电商搜索环境中使用大型语言模型（LLMs）进行查询重写的应用。论文提出了一种混合管道方法，结合了离线知识蒸馏和在线强化学习，以提升查询重写的效率和效果。虽然涉及了强化学习（RL）和知识蒸馏等技术，但核心仍然是LLM在特定领域（电商搜索）中的应用，因此归类为“LLM应用”更为合适。` `搜索优化`

> RL-based Query Rewriting with Distilled LLM for online E-Commerce Systems

# 摘要

> # 摘要
查询重写（QR）是电商搜索中的关键技术，用于弥合用户查询与产品描述之间的词汇鸿沟，从而提升搜索效果。现有QR方法主要分为两类：判别模型和基于大型语言模型（LLMs）的生成方法。判别模型在自然语言理解上表现欠佳，重写灵活性有限；而生成式LLMs虽能生成高质量重写，但在线场景中面临高延迟和高成本的瓶颈，通常只能离线部署，易受信息过时和语义漂移的影响。为此，我们提出了一种新颖的混合管道方法，兼顾效率与效果。该方法通过离线知识蒸馏构建轻量高效的学生模型，并结合在线强化学习（RL）利用实时反馈动态优化重写。关键创新在于使用LLMs模拟人类反馈，实现可扩展的奖励信号和低成本评估，无需人工标注。在Amazon ESCI数据集上的实验表明，该方法显著提升了查询相关性、多样性和适应性，并获得了LLM模拟的积极反馈。这项研究推动了LLM在特定领域的应用能力，为复杂动态的电商搜索环境提供了高效解决方案。

> Query rewriting (QR) is a critical technique in e-commerce search, addressing the lexical gap between user queries and product descriptions to enhance search performance. Existing QR approaches typically fall into two categories: discriminative models and generative methods leveraging large language models (LLMs). Discriminative models often struggle with natural language understanding and offer limited flexibility in rewriting, while generative LLMs, despite producing high-quality rewrites, face high inference latency and cost in online settings. These limitations force offline deployment, making them vulnerable to issues like information staleness and semantic drift. To overcome these challenges, we propose a novel hybrid pipeline for QR that balances efficiency and effectiveness. Our approach combines offline knowledge distillation to create a lightweight but efficient student model with online reinforcement learning (RL) to refine query rewriting dynamically using real-time feedback. A key innovation is the use of LLMs as simulated human feedback, enabling scalable reward signals and cost-effective evaluation without manual annotations. Experimental results on Amazon ESCI dataset demonstrate significant improvements in query relevance, diversity, and adaptability, as well as positive feedback from the LLM simulation. This work contributes to advancing LLM capabilities for domain-specific applications, offering a robust solution for dynamic and complex e-commerce search environments.

[Arxiv](https://arxiv.org/abs/2501.18056)