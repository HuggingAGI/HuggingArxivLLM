# Solid-SQL：基于增强模式链接的上下文学习，打造鲁棒的文本到SQL

发布时间：2024年12月16日

`LLM应用

理由：该论文主要讨论了如何利用大型语言模型（LLMs）来提升文本到SQL系统的性能，并提出了一个名为Solid-SQL的解决方案。该方案通过预处理阶段和上下文学习策略来提高系统的鲁棒性。这属于将LLM应用于特定任务（文本到SQL转换）的范畴，因此归类为“LLM应用”。` `数据库`

> Solid-SQL: Enhanced Schema-linking based In-context Learning for Robust Text-to-SQL

# 摘要

> 最近，大型语言模型（LLMs）大幅提升了文本到SQL系统的性能。然而，许多顶尖方法忽视了系统鲁棒性这一关键因素。实验显示，尽管LLM驱动的方法在标准数据集上表现优异，但在面对对抗性扰动时，其准确性大打折扣。为此，我们提出了Solid-SQL，一种鲁棒的文本到SQL解决方案，可与多种LLMs无缝集成。我们专注于预处理阶段，训练了一个由LLM增强的鲁棒模式链接模型，并设计了一种基于结构相似性的两轮示例检索策略，用于上下文学习。在通用的Spider和Bird基准测试中，Solid-SQL分别达到了82.1%和58.9%的SOTA SQL执行准确率。此外，实验结果显示，Solid-SQL在扰动的Spider-Syn、Spider-Realistic和Dr. Spider基准测试中，相比基线平均提升了11.6%。

> Recently, large language models (LLMs) have significantly improved the performance of text-to-SQL systems. Nevertheless, many state-of-the-art (SOTA) approaches have overlooked the critical aspect of system robustness. Our experiments reveal that while LLM-driven methods excel on standard datasets, their accuracy is notably compromised when faced with adversarial perturbations. To address this challenge, we propose a robust text-to-SQL solution, called Solid-SQL, designed to integrate with various LLMs. We focus on the pre-processing stage, training a robust schema-linking model enhanced by LLM-based data augmentation. Additionally, we design a two-round, structural similarity-based example retrieval strategy for in-context learning. Our method achieves SOTA SQL execution accuracy levels of 82.1% and 58.9% on the general Spider and Bird benchmarks, respectively. Furthermore, experimental results show that Solid-SQL delivers an average improvement of 11.6% compared to baselines on the perturbed Spider-Syn, Spider-Realistic, and Dr. Spider benchmarks.

[Arxiv](https://arxiv.org/abs/2412.12522)