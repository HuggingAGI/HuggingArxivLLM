# 专家混合语言模型升级的扩展法则

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要讨论了预训练大型语言模型（LLMs）的计算效率问题，特别是通过升级回收和专家混合模型（MoE）来优化模型训练。论文的核心在于探索LLMs的扩展行为和性能优化策略，属于对LLMs的理论研究和优化方法的探讨，因此归类为“LLM理论”。` `人工智能` `机器学习`

> Scaling Laws for Upcycling Mixture-of-Experts Language Models

# 摘要

> 预训练大型语言模型（LLMs）资源消耗巨大，即使使用高端GPU集群，也常需数月时间。为缓解这一计算压力，有两种策略：一是重用小模型训练大模型（升级回收），二是训练计算高效的模型，如专家混合模型（MoE）。本文聚焦于将LLMs升级回收为MoE模型，其扩展行为尚待深入探索。通过大量实验，我们揭示了性能与数据集大小及模型配置之间的经验扩展规律。特别地，我们发现，尽管扩展这些因素能提升性能，但密集与升级回收数据集间存在一种新的交互项，限制了大计算预算下升级回收的效率。基于此，我们提出了扩展升级回收的指导原则，并确立了在预算限制内升级回收优于从头训练的条件。

> Pretraining large language models (LLMs) is resource-intensive, often requiring months of training time even with high-end GPU clusters. There are two approaches of mitigating such computational demands: reusing smaller models to train larger ones (upcycling), and training computationally efficient models like mixture-of-experts (MoE). In this paper, we study the upcycling of LLMs to MoE models, of which the scaling behavior remains underexplored. Through extensive experiments, we identify empirical scaling laws that describe how performance depends on dataset size and model configuration. Particularly, we show that, while scaling these factors improves performance, there is a novel interaction term between the dense and upcycled training dataset that limits the efficiency of upcycling at large computational budgets. Based on these findings, we provide guidance to scale upcycling, and establish conditions under which upcycling outperforms from-scratch trainings within budget constraints.

[Arxiv](https://arxiv.org/abs/2502.03009)