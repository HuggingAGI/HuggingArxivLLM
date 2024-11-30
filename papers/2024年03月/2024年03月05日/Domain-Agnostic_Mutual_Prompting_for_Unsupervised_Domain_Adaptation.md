# 为解决无监督领域适应问题，我们提出“领域无关的相互提示”方法，该方法能够在不同领域间进行有效知识迁移，无需任何领域标注数据。

发布时间：2024年03月05日

`Agent`

> Domain-Agnostic Mutual Prompting for Unsupervised Domain Adaptation

# 摘要

> 传统UDA致力于缩小不同领域的分布差距，却忽视了充分挖掘数据的丰富语义，并在面对复杂领域转换时力不从心。为此，我们创新性地借助大规模预训练的视觉-语言模型，实现更精准的引导式适应。然而，现有方法多是分开为源域和目标域学习文本提示，并在各自领域内完成分类，这限制了跨域知识的有效传递。另外，仅对语言分支进行提示调整也难以灵活应对双模态动态适应的需求。针对此挑战，我们提出了“领域无关双向提示”（DAMP）技术，它通过对视觉和文本嵌入进行互相对齐，巧妙发掘并利用领域不变的语义特征。具体而言，DAMP以领域无关、实例相关的策略运用图像上下文信息去驱动语言分支，同时根据领域无关的文本提示构建视觉提示，从而提炼出领域不变的视觉嵌入。这两种提示分支通过交叉注意力机制相互学习，并通过语义一致性损失及实例辨别对比损失加以约束。在三个UDA基准数据集上的实验证明，DAMP方法在性能上超越了当前最先进的同类技术。

> Conventional Unsupervised Domain Adaptation (UDA) strives to minimize distribution discrepancy between domains, which neglects to harness rich semantics from data and struggles to handle complex domain shifts. A promising technique is to leverage the knowledge of large-scale pre-trained vision-language models for more guided adaptation. Despite some endeavors, current methods often learn textual prompts to embed domain semantics for source and target domains separately and perform classification within each domain, limiting cross-domain knowledge transfer. Moreover, prompting only the language branch lacks flexibility to adapt both modalities dynamically. To bridge this gap, we propose Domain-Agnostic Mutual Prompting (DAMP) to exploit domain-invariant semantics by mutually aligning visual and textual embeddings. Specifically, the image contextual information is utilized to prompt the language branch in a domain-agnostic and instance-conditioned way. Meanwhile, visual prompts are imposed based on the domain-agnostic textual prompt to elicit domain-invariant visual embeddings. These two branches of prompts are learned mutually with a cross-attention module and regularized with a semantic-consistency loss and an instance-discrimination contrastive loss. Experiments on three UDA benchmarks demonstrate the superiority of DAMP over state-of-the-art approaches.

[Arxiv](https://arxiv.org/abs/2403.02899)