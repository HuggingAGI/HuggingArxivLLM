# # 学习替换组件，实现组合泛化能力

发布时间：2025年02月28日

`LLM理论` `机器学习`

> Learning to Substitute Components for Compositional Generalization

# 摘要

> 尽管神经语言模型的应用日益广泛，近期研究发现它们在组合式泛化方面存在明显短板。当前解决这一问题的实际方案之一是组合式数据增强，其核心目标是引入额外的组合归纳偏置。然而，现有的手工设计数据增强策略在面对神经语言模型需要多粒度组合偏置（不仅限于词汇或结构偏置）或训练句子难度分布失衡的情况时，改进效果十分有限。为应对这些挑战，我们提出了一种名为组件替换（CompSub）的新型组合增强策略，能够在整个训练集中实现大规模子结构的多粒度组合。此外，我们引入了学习组件替换（LCS）框架。该框架通过最大化神经语言模型的损失，以端到端的方式学习组件替换的概率，从而优先处理那些涉及难以捉摸的概念和新颖上下文的复杂组合。我们将CompSub和LCS的核心思想扩展到了预训练大型语言模型（LLMs）的上下文学习场景中，提出了LCS-ICL算法，以提升当前最先进的（SOTA）LLMs在少量样本情况下的组合式泛化能力。从理论上，我们揭示了将我们的算法应用于语言模型为何能显著提升组合式泛化性能。实证结果方面，我们在四个标准的组合式泛化基准测试（SCAN、COGS、GeoQuery和COGS-QL）上的实验结果表明，CompSub、LCS和LCS-ICL均表现出色，分别带来了高达66.5%、10.3%、1.4%和8.8%的性能提升。

> Despite the rising prevalence of neural language models, recent empirical evidence suggests their deficiency in compositional generalization. One of the current de-facto solutions to this problem is compositional data augmentation, which aims to introduce additional compositional inductive bias. However, existing handcrafted augmentation strategies offer limited improvement when systematic generalization of neural language models requires multi-grained compositional bias (i.e., not limited to either lexical or structural biases alone) or when training sentences have an imbalanced difficulty distribution. To address these challenges, we first propose a novel compositional augmentation strategy called Component Substitution (CompSub), which enables multi-grained composition of substantial substructures across the entire training set. Furthermore, we introduce the Learning Component Substitution (LCS) framework. This framework empowers the learning of component substitution probabilities in CompSub in an end-to-end manner by maximizing the loss of neural language models, thereby prioritizing challenging compositions with elusive concepts and novel contexts. We extend the key ideas of CompSub and LCS to the recently emerging in-context learning scenarios of pre-trained large language models (LLMs), proposing the LCS-ICL algorithm to enhance the few-shot compositional generalization of state-of-the-art (SOTA) LLMs. Theoretically, we provide insights into why applying our algorithms to language models can improve compositional generalization performance. Empirically, our results on four standard compositional generalization benchmarks(SCAN, COGS, GeoQuery, and COGS-QL) demonstrate the superiority of CompSub, LCS, and LCS-ICL, with improvements of up to 66.5%, 10.3%, 1.4%, and 8.8%, respectively.

[Arxiv](https://arxiv.org/abs/2502.20834)