# # 基于少量样本演示的大型专家混合模型的特定领域高效剪枝策略

发布时间：2025年04月09日

`LLM理论` `人工智能` `机器学习`

> Domain-Specific Pruning of Large Mixture-of-Experts Models with Few-shot Demonstrations

# 摘要

> 专家混合模型（MoE）通过仅激活部分专家，在性能和推理效率之间实现了良好的平衡。然而，存储所有专家带来的内存开销仍然是一个主要限制，尤其是在大规模 MoE 模型（如 DeepSeek-R1（671B））中。本研究探讨了大规模 MoE 模型中的领域专业化和专家冗余问题，并发现了一种一致的行为，我们称之为 few-shot 专家定位：仅需少量演示，模型即可持续激活一组稀疏且稳定的专家子集。基于这一观察，我们提出了一种简单而有效的剪枝框架 EASY-EP，该框架利用少量特定领域的演示来识别并保留最相关的专家。EASY-EP 包含两个关键组件：输出感知的专家重要性评估和专家级令牌贡献估计。前者通过考虑激活专家的门控分数和输出幅度，评估每个专家对当前令牌的重要性；后者则通过路由前后表示相似性，评估令牌的贡献。实验表明，在相同的内存预算下，我们的方法仅使用一半的专家即可实现与完整 DeepSeek-R1 相当的性能，并且吞吐量提高了 2.99 倍。我们的代码可在 https://github.com/RUCAIBox/EASYEP 获取。

> Mixture-of-Experts (MoE) models achieve a favorable trade-off between performance and inference efficiency by activating only a subset of experts. However, the memory overhead of storing all experts remains a major limitation, especially in large-scale MoE models such as DeepSeek-R1 (671B). In this study, we investigate domain specialization and expert redundancy in large-scale MoE models and uncover a consistent behavior we term few-shot expert localization, with only a few demonstrations, the model consistently activates a sparse and stable subset of experts. Building on this observation, we propose a simple yet effective pruning framework, EASY-EP, that leverages a few domain-specific demonstrations to identify and retain only the most relevant experts. EASY-EP comprises two key components: output-aware expert importance assessment and expert-level token contribution estimation. The former evaluates the importance of each expert for the current token by considering the gating scores and magnitudes of the outputs of activated experts, while the latter assesses the contribution of tokens based on representation similarities after and before routed experts. Experiments show that our method can achieve comparable performances and $2.99\times$ throughput under the same memory budget with full DeepSeek-R1 with only half the experts. Our code is available at https://github.com/RUCAIBox/EASYEP.

[Arxiv](https://arxiv.org/abs/2504.06792)