# **UNDO: 理解蒸馏为优化**

模型蒸馏是一项强大而实用的技术，它能够将大型模型压缩为更紧凑的小型模型，同时保留其性能优势。然而，关于蒸馏过程中的优化机制以及不同蒸馏策略如何影响最终模型质量，目前的研究仍存在诸多未解之谜。本研究通过将蒸馏过程建模为优化问题，深入探究了蒸馏的内在工作原理。我们提出了一种统一的框架，能够将多种蒸馏方法纳入其中，并通过理论分析与实证研究，揭示了蒸馏过程中关键因素对模型性能的影响规律。实验结果表明，我们的框架不仅为蒸馏策略的选择提供了有力指导，还显著提升了蒸馏后模型的性能表现。

发布时间：2025年04月03日

`LLM应用` `人工智能`

> UNDO: Understanding Distillation as Optimization

# 摘要

> 知识蒸馏作为一种有效的策略，用于将大型语言模型（LLMs）的知识压缩到更小、更高效的student模型中。然而，标准的一次性蒸馏方法常常由于教师生成的解释与student模型特定的学习需求之间存在不匹配，导致效果欠佳。本文中，我们引入了UNDO：理解蒸馏作为优化框架，旨在通过迭代识别student模型的错误，并相应地促使教师优化其解释来弥补这一差距。每一次迭代都直接针对student模型的学习缺陷，激励教师提供量身定制且增强的解释，特别针对这些弱点。在各种具有挑战性的数学和常识推理任务上的实证评估表明，我们的迭代蒸馏方法UNDO显著优于标准的一次性蒸馏方法，性能提升高达20%。此外，我们还展示了通过我们的迭代过程优化的教师生成数据，即使应用于不同的student模型，仍然保持有效性，突显了我们方法的广泛应用前景。我们的研究从根本上重新定义了知识蒸馏为一种迭代的师生互动过程，通过教师的动态优化，显著提升了知识蒸馏的效果。

> Knowledge distillation has emerged as an effective strategy for compressing large language models' (LLMs) knowledge into smaller, more efficient student models. However, standard one-shot distillation methods often produce suboptimal results due to a mismatch between teacher-generated rationales and the student's specific learning requirements. In this paper, we introduce the UNDO: UNderstanding Distillation as Optimization framework, designed to bridge this gap by iteratively identifying the student's errors and prompting the teacher to refine its explanations accordingly. Each iteration directly targets the student's learning deficiencies, motivating the teacher to provide tailored and enhanced rationales that specifically address these weaknesses. Empirical evaluations on various challenging mathematical and commonsense reasoning tasks demonstrate that our iterative distillation method, UNDO, significantly outperforms standard one-step distillation methods, achieving performance gains of up to 20%. Additionally, we show that teacher-generated data refined through our iterative process remains effective even when applied to different student models, underscoring the broad applicability of our approach. Our work fundamentally reframes knowledge distillation as an iterative teacher-student interaction, effectively leveraging dynamic refinement by the teacher for better knowledge distillation.

[Arxiv](https://arxiv.org/abs/2504.02521)