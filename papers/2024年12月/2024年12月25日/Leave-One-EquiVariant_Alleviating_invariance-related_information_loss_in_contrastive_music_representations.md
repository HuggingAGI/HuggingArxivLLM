# Leave-One-EquiVariant: 减轻对比音乐表示中不变性导致的信息损失

发布时间：2024年12月25日

`其他

理由：这篇论文主要讨论的是对比学习在音乐表示学习中的应用，特别是针对音乐信息检索（MIR）任务的改进方法。虽然涉及自监督学习和表示学习，但这些内容与Agent、RAG、LLM应用、LLM理论等分类没有直接关联。因此，将其归类为其他更为合适。` `信息检索`

> Leave-One-EquiVariant: Alleviating invariance-related information loss in contrastive music representations

# 摘要

> 对比学习在自监督音乐表示学习中表现出色，尤其在音乐信息检索（MIR）任务中。然而，依赖增强链生成对比视图及其带来的学习不变性，在面对不同下游任务时，尤其是需要对某些音乐属性敏感的任务时，存在挑战。为此，我们提出了Leave One EquiVariant（LOEV）框架，通过选择性保留特定增强信息，使模型能够保持任务相关的等变性，从而提供了一种灵活的任务自适应方法。我们证明，LOEV有效缓解了学习不变性导致的信息丢失，提升了与增强相关任务和检索的性能，同时保持了表示质量。此外，我们还推出了LOEV++，它以自监督方式构建了一个解耦的潜在空间，支持基于增强相关属性的目标检索。

> Contrastive learning has proven effective in self-supervised musical representation learning, particularly for Music Information Retrieval (MIR) tasks. However, reliance on augmentation chains for contrastive view generation and the resulting learnt invariances pose challenges when different downstream tasks require sensitivity to certain musical attributes. To address this, we propose the Leave One EquiVariant (LOEV) framework, which introduces a flexible, task-adaptive approach compared to previous work by selectively preserving information about specific augmentations, allowing the model to maintain task-relevant equivariances. We demonstrate that LOEV alleviates information loss related to learned invariances, improving performance on augmentation related tasks and retrieval without sacrificing general representation quality. Furthermore, we introduce a variant of LOEV, LOEV++, which builds a disentangled latent space by design in a self-supervised manner, and enables targeted retrieval based on augmentation related attributes.

[Arxiv](https://arxiv.org/abs/2412.18955)