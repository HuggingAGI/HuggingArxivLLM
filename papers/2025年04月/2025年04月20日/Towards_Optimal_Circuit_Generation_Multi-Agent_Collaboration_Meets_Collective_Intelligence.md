# 探索最优电路生成：多智能体协作与集体智能的融合

发布时间：2025年04月20日

`LLM应用` `硬件设计` `电路设计`

> Towards Optimal Circuit Generation: Multi-Agent Collaboration Meets Collective Intelligence

# 摘要

> 大型语言模型（LLMs）彻底改变了代码生成领域，但在硬件设计应用中，其表现仍有提升空间——生成的门电路数量比人工设计高出38\%--1075\%。我们推出CircuitMind——一个多智能体框架，通过三大创新实现与人类相当的设计效率：语法锁定（限制生成为基本逻辑门）、检索增强生成（支持知识驱动设计）以及双奖励优化（平衡正确性与效率）。为了全面评估CircuitMind，我们创建了TC-Bench——首个基于TuringComplete生态系统的门级基准，该平台汇聚了来自数万名设计师的集体智慧。实验结果令人振奋：CircuitMind使55.6\%的模型实现能够在综合效率指标上匹敌或超越顶尖人类专家。更令人惊叹的是，我们的框架成功将14B Phi-4模型提升至超越GPT-4o mini和Gemini 2.0 Flash，其效率可媲美人类专家中的前25\%，而无需专门训练。这些创新为硬件优化开辟了新范式，协作式AI系统可借助集体人类智慧实现最优电路设计。我们的模型、数据和代码已在GitHub开放，地址为https://github.com/BUAA-CLab/CircuitMind。


> Large language models (LLMs) have transformed code generation, yet their application in hardware design produces gate counts 38\%--1075\% higher than human designs. We present CircuitMind, a multi-agent framework that achieves human-competitive efficiency through three key innovations: syntax locking (constraining generation to basic logic gates), retrieval-augmented generation (enabling knowledge-driven design), and dual-reward optimization (balancing correctness with efficiency). To evaluate our approach, we introduce TC-Bench, the first gate-level benchmark harnessing collective intelligence from the TuringComplete ecosystem -- a competitive circuit design platform with hundreds of thousands of players. Experiments show CircuitMind enables 55.6\% of model implementations to match or exceed top-tier human experts in composite efficiency metrics. Most remarkably, our framework elevates the 14B Phi-4 model to outperform both GPT-4o mini and Gemini 2.0 Flash, achieving efficiency comparable to the top 25\% of human experts without requiring specialized training. These innovations establish a new paradigm for hardware optimization where collaborative AI systems leverage collective human expertise to achieve optimal circuit designs. Our model, data, and code are open-source at https://github.com/BUAA-CLab/CircuitMind.

[Arxiv](https://arxiv.org/abs/2504.14625)