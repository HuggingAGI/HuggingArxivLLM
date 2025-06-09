# 大型语言模型自身就是演示的预选器

发布时间：2025年06月06日

`LLM应用

摘要中提到的上下文学习（ICL）和演示样本选择方法FEEDER是关于如何更有效地应用大型语言模型（LLMs）的技术，属于LLM的应用层面。FEEDER框架旨在优化LLMs的训练效率和性能，这直接关联到LLM的应用场景和优化策略。因此，这篇论文应归类为LLM应用。` `大型语言模型`

> Large Language Models are Demonstration Pre-Selectors for Themselves

# 摘要

> 基于大型语言模型 (LLMs) 的上下文学习 (ICL) 能够通过选择少量样本演示实现强大的少量样本学习性能。然而，现有 ICL 方法依赖相似性或多样性分数选择演示样本，由于需要从大规模数据集中重复检索，导致计算成本高昂。为此，我们提出了 FEEDER（FEw yet Essential Demonstration prE-selectoR），这是一种为特定 LLMs 量身定制的新型预选框架，旨在识别包含训练数据中最具代表性的样例的演示子集。为了构建这个子集，我们在预选阶段引入了“充分性”和“必要性”指标，并设计了一种树基算法来高效识别具有代表性的样例。预选完成后，这个子集可有效替代完整训练数据，在保持 ICL 性能的同时提升效率。此外，我们的预选子集对微调 LLMs 也有益处，我们引入了一种双层优化方法，在不牺牲性能的情况下提升训练效率。实验结果表明，对于参数规模从 300M 到 8B 的 LLMs，FEEDER 可在保持性能的同时将训练数据规模减少 20% 以上，并无缝集成到 ICL 的各种下游演示选择策略中。

> In-context learning (ICL) with large language models (LLMs) delivers strong few-shot performance by choosing few-shot demonstrations from the entire training data. However, existing ICL methods, which rely on similarity or diversity scores to choose demonstrations, incur high computational costs due to repeatedly retrieval from large-scale datasets for each query. To this end, we propose FEEDER (FEw yet Essential Demonstration prE-selectoR), a novel pre-selection framework that identifies a representative subset of demonstrations containing the most representative examples in the training data, tailored to specific LLMs. To construct this subset, we introduce the "sufficiency" and "necessity" metrics in the pre-selection stage and design a tree-based algorithm to identify representative examples efficiently. Once pre-selected, this representative subset can effectively replace the full training data, improving efficiency while maintaining comparable performance in ICL. Additionally, our pre-selected subset also benefits fine-tuning LLMs, where we introduce a bi-level optimization method that enhances training efficiency without sacrificing performance. Experiments with LLMs ranging from 300M to 8B parameters show that FEEDER can reduce training data size by over 20% while maintaining performance and seamlessly integrating with various downstream demonstration selection strategies in ICL.

[Arxiv](https://arxiv.org/abs/2506.06033)