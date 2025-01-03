# 基于结构感知蒸馏的视觉-语言检索再平衡

发布时间：2024年12月14日

`其他

**理由**：这篇论文主要讨论的是视觉-语言检索中的跨模态匹配问题，特别是模态失衡对检索性能的影响。虽然涉及到了语言和视觉的跨模态表示学习，但并没有直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等概念。因此，将其归类为“其他”更为合适。` `计算机视觉` `信息检索`

> Rebalanced Vision-Language Retrieval Considering Structure-Aware Distillation

# 摘要

> # 摘要
视觉-语言检索的目标是基于一种模态的查询，在另一种模态中寻找相似实例。其核心在于在潜在共同空间中学习跨模态匹配表示。跨模态匹配的前提是模态平衡，即每种模态都能充分表达其他模态。然而，噪声干扰和模态不足常导致模态失衡，这在实践中十分常见。失衡对检索性能的影响仍是一个未解之谜。本文首先指出，当模态失衡时，跨模态匹配往往难以达到最优。失衡模态会破坏共同空间中实例的结构，给跨模态相似性测量带来挑战。为此，我们强调了结构保持匹配的重要性，并提出了一种简单有效的方法，通过学习结构保持匹配表示来重新平衡跨模态匹配。具体而言，我们设计了一种多粒度跨模态匹配方法，将结构感知蒸馏与跨模态匹配损失相结合。跨模态匹配损失约束实例级匹配，而结构感知蒸馏则通过关系匹配进一步规范匹配表示与模态内表示之间的几何一致性。大量实验表明，我们的方法在跨模态检索性能上表现优异，同时相比基线模型，单模态检索能力也得到了提升。

> Vision-language retrieval aims to search for similar instances in one modality based on queries from another modality. The primary objective is to learn cross-modal matching representations in a latent common space. Actually, the assumption underlying cross-modal matching is modal balance, where each modality contains sufficient information to represent the others. However, noise interference and modality insufficiency often lead to modal imbalance, making it a common phenomenon in practice. The impact of imbalance on retrieval performance remains an open question. In this paper, we first demonstrate that ultimate cross-modal matching is generally sub-optimal for cross-modal retrieval when imbalanced modalities exist. The structure of instances in the common space is inherently influenced when facing imbalanced modalities, posing a challenge to cross-modal similarity measurement. To address this issue, we emphasize the importance of meaningful structure-preserved matching. Accordingly, we propose a simple yet effective method to rebalance cross-modal matching by learning structure-preserved matching representations. Specifically, we design a novel multi-granularity cross-modal matching that incorporates structure-aware distillation alongside the cross-modal matching loss. While the cross-modal matching loss constraints instance-level matching, the structure-aware distillation further regularizes the geometric consistency between learned matching representations and intra-modal representations through the developed relational matching. Extensive experiments on different datasets affirm the superior cross-modal retrieval performance of our approach, simultaneously enhancing single-modal retrieval capabilities compared to the baseline models.

[Arxiv](https://arxiv.org/abs/2412.10761)