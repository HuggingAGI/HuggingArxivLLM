# 层次平衡打包：面向长上下文型LLM的监督微调高效方法

发布时间：2025年03月10日

`LLM理论

理由：这篇论文讨论了训练长上下文大型语言模型 (LLMs) 的挑战，并提出了一种新的方法 HBP 来优化训练过程。它专注于训练效率和模型优化，属于 LLM 的理论研究。` `人工智能`

> Hierarchical Balance Packing: Towards Efficient Supervised Fine-tuning for Long-Context LLM

# 摘要

> 训练长上下文大型语言模型 (LLMs) 具有挑战性，因为同时使用长上下文和短上下文数据的混合训练常常导致负载不平衡。现有研究主要通过数据打包来缓解这一问题，但未能考虑到注意力计算的不平衡和通信开销的浪费。本文提出了分层平衡打包 (HBP)，设计了一种新型的批次构建方法和训练配方，以解决这些低效问题。具体来说，HBP 构建了多级数据打包组，每组都采用不同的打包长度进行优化。它将训练样本分配到最适合的组中，并为每组配置最有效的设置，包括顺序并行度和梯度检查点配置。为了充分利用多级数据组，我们为 HBP 设计了一条专门的动态训练流水线，包括课程学习、自适应顺序并行和稳定损失。我们的大量实验表明，与现有方法相比，我们的方法在多个数据集和开源模型上显著减少了训练时间，同时保持了强大的性能。对于最大的 DeepSeek-V2 (236B) 分布式专家模型，我们的方法将训练速度提升了 2.4 倍，同时保持了具有竞争力的性能。

> Training Long-Context Large Language Models (LLMs) is challenging, as hybrid training with long-context and short-context data often leads to workload imbalances. Existing works mainly use data packing to alleviate this issue but fail to consider imbalanced attention computation and wasted communication overhead. This paper proposes Hierarchical Balance Packing (HBP), which designs a novel batch-construction method and training recipe to address those inefficiencies. In particular, the HBP constructs multi-level data packing groups, each optimized with a distinct packing length. It assigns training samples to their optimal groups and configures each group with the most effective settings, including sequential parallelism degree and gradient checkpointing configuration. To effectively utilize multi-level groups of data, we design a dynamic training pipeline specifically tailored to HBP, including curriculum learning, adaptive sequential parallelism, and stable loss. Our extensive experiments demonstrate that our method significantly reduces training time over multiple datasets and open-source models while maintaining strong performance. For the largest DeepSeek-V2 (236B) MOE model, our method speeds up the training by 2.4$\times$ with competitive performance.

[Arxiv](https://arxiv.org/abs/2503.07680)