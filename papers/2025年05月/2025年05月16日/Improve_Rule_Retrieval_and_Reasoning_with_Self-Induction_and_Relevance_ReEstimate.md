# 提升规则检索与推理能力：自我归纳与相关性重评估方法
本研究旨在探讨如何利用自我归纳与相关性重评估技术，优化规则检索过程，并提升推理能力。

发布时间：2025年05月16日

`LLM应用` `规则检索`

> Improve Rule Retrieval and Reasoning with Self-Induction and Relevance ReEstimate

# 摘要

> 本文系统性地探讨了规则检索这一重要但尚未充分研究的领域所面临的挑战。传统检索方法通过稀疏或密集检索器直接搜索相关规则以支持下游推理，但通常面临准确性低的问题。这主要是因为查询中实例化的事实与规则的抽象表示之间存在显著的语义鸿沟。这种不匹配导致检索质量欠佳，进而对推理性能产生负面影响。

为克服这些挑战，我们提出了自诱导增强检索（SIAR），这是一种利用大型语言模型（LLMs）通过抽象查询中的潜在知识和逻辑结构来推导可能有助于推理的潜在推理规则的新型方法。这些推导出的规则随后用于查询增强以提升检索效果。此外，我们还引入了规则相关性再估计（R³），这是一种通过评估检索到的规则中所包含的抽象知识是否能够实例化以与查询中的事实对齐以及对推理的有用性来重新评估规则相关性的方法。

在多种设置下的大量实验充分证明了我们提出方法的有效性和 versatility。

> This paper systematically addresses the challenges of rule retrieval, a crucial yet underexplored area. Vanilla retrieval methods using sparse or dense retrievers to directly search for relevant rules to support downstream reasoning, often suffer from low accuracy. This is primarily due to a significant semantic gap between the instantiated facts in the queries and the abstract representations of the rules. Such misalignment results in suboptimal retrieval quality, which in turn negatively impacts reasoning performance. To overcome these challenges, we propose Self-Induction Augmented Retrieval (SIAR), a novel approach that utilizes Large Language Models (LLMs) to induce potential inferential rules that might offer benefits for reasoning by abstracting the underlying knowledge and logical structure in queries. These induced rules are then used for query augmentation to improve retrieval effectiveness. Additionally, we introduce Rule Relevance ReEstimate (R$^3$), a method that re-estimates the relevance of retrieved rules by assessing whether the abstract knowledge they contain can be instantiated to align with the facts in the queries and the helpfulness for reasoning. Extensive experiments across various settings demonstrate the effectiveness and versatility of our proposed methods.

[Arxiv](https://arxiv.org/abs/2505.10870)