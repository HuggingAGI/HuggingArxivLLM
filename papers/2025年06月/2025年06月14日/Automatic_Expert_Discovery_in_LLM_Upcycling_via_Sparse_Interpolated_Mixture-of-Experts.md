# 通过稀疏插值专家混合模型实现LLM的自动专家发现与升级利用

发布时间：2025年06月14日

`LLM应用

摘要中提到的SIMoE方法是一种指令微调技术，用于优化大型语言模型在多领域的应用性能，属于LLM的应用层面改进。` `人工智能`

> Automatic Expert Discovery in LLM Upcycling via Sparse Interpolated Mixture-of-Experts

# 摘要

> 我们提出了稀疏插值专家混合模型（Sparse Interpolated Mixture-of-Experts，SIMoE）指令微调方法，这是一种端到端算法，旨在将密集预训练的大型语言模型（LLM）微调为具备多领域专业能力的专家混合模型（MoE）风格。在指令微调过程中，SIMoE能在给定稀疏性约束下自动识别多个专业领域专家，每个专家代表种子LLM参数中对应特定领域知识的结构稀疏子集。同时，SIMoE通过路由网络学习一种输入依赖的专家融合策略，充分利用跨专家知识，实现超越现有基线的下游泛化性能。实证结果显示，SIMoE在常见指令微调基准测试中始终达到当前最优水平，同时相较于所有基线方法，实现了性能与计算资源的最优平衡。

> We present Sparse Interpolated Mixture-of-Experts (SIMoE) instruction-tuning, an end-to-end algorithm designed to fine-tune a dense pre-trained Large Language Model (LLM) into a MoE-style model that possesses capabilities in multiple specialized domains. During instruction-tuning, SIMoE automatically identifies multiple specialized experts under a specified sparsity constraint, with each expert representing a structurally sparse subset of the seed LLM's parameters that correspond to domain-specific knowledge within the data. SIMoE simultaneously learns an input-dependent expert merging strategy via a router network, leveraging rich cross-expert knowledge for superior downstream generalization that surpasses existing baselines. Empirically, SIMoE consistently achieves state-of-the-art performance on common instruction-tuning benchmarks while maintaining an optimal performance-compute trade-off compared to all baselines.

[Arxiv](https://arxiv.org/abs/2506.12597)