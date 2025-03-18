# 代码驱动归纳合成：通过序列增强大型语言模型的推理能力

发布时间：2025年03月17日

`LLM应用

摘要中提到论文探讨了如何通过特定的数据和方法提升大型语言模型在归纳推理任务中的表现，属于模型的应用层面。因此，分类为LLM应用。`

> Code-Driven Inductive Synthesis: Enhancing Reasoning Abilities of Large Language Models with Sequences

# 摘要

> 大型语言模型的推理能力取得了显著进步。然而，现有研究主要聚焦于演绎推理任务（如代码和数学），而另一种更符合人类学习模式的归纳推理方式却未得到充分探索。这主要是因为获取高质量的过程监督数据对归纳推理来说颇具挑战性。为此，我们创新性地采用数字序列作为归纳推理的数据来源。我们将这些序列转化为算法问题，通过编写代码解决方案找出每个序列的通项。这样不仅能够验证代码解决方案是否适用于序列中的任意项，还能通过代码单元测试注入基于案例的监督信号。我们构建了一个序列合成数据管道，并形成了训练数据集CodeSeq。实验结果表明，经过CodeSeq微调的模型在代码和综合推理基准测试中均表现更佳。

> Large language models make remarkable progress in reasoning capabilities. Existing works focus mainly on deductive reasoning tasks (e.g., code and math), while another type of reasoning mode that better aligns with human learning, inductive reasoning, is not well studied. We attribute the reason to the fact that obtaining high-quality process supervision data is challenging for inductive reasoning. Towards this end, we novelly employ number sequences as the source of inductive reasoning data. We package sequences into algorithmic problems to find the general term of each sequence through a code solution. In this way, we can verify whether the code solution holds for any term in the current sequence, and inject case-based supervision signals by using code unit tests. We build a sequence synthetic data pipeline and form a training dataset CodeSeq. Experimental results show that the models tuned with CodeSeq improve on both code and comprehensive reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2503.13109)