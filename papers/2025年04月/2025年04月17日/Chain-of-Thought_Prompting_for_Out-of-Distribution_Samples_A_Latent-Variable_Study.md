# # 链式思维提示针对分布外样本的潜在变量视角研究

发布时间：2025年04月17日

`LLM理论

理由：这篇论文探讨了Chain-of-Thought (CoT) 提示方法在分布变化下的泛化能力，分析了其在出分布 (OOD) 场景下的表现。研究集中在理解 CoT 提示的内在机制及其在不同条件下的有效性，属于对大型语言模型理论的深入探讨，因此归类为LLM理论。` `人工智能` `机器学习`

> Chain-of-Thought Prompting for Out-of-Distribution Samples: A Latent-Variable Study

# 摘要

> Chain-of-Thought (CoT) 提示方法作为一种强大的技术，已被证明可以有效提升大型语言模型 (LLMs) 中的 in-context learning (ICL) 能力。然而，关于 CoT 在分布变化下的泛化能力，目前仍缺乏深入理解。在这项研究中，我们扩展了一个用于 CoT 提示的潜在变量框架，并考察了其在两种典型出分布 (OOD) 场景下的表现：(i) 将 CoT 步骤的潜在变量重新排列组合成新的组合，以及 (ii) 将潜在变量均匀缩放一个因子。实验结果表明，当 OOD 样本的潜在变量与训练过程中观察到的潜在变量相似时，CoT 推理能够有效地泛化，但随着这种相似性的降低，其性能会逐渐下降。这些发现为理解 CoT 提示在 OOD 条件下的优势与局限性提供了基础性的见解，并为未来开发更具韧性的推理策略指明了方向。

> Chain-of-Thought (CoT) prompting has emerged as a powerful technique to improve in-context learning (ICL) in large language models (LLMs) by breaking complex reasoning into intermediate steps. However, the ability of CoT to generalize under distribution shift remains poorly understood. In this work, we extend a latent-variable framework for CoT prompting and study its behavior on two prototypical out-of-distribution (OOD) scenarios: (i) the latent variables for CoT steps are permuted into novel combinations, and (ii) the latent variables uniformly scaled by a factor. Our experiments demonstrate that CoT inference generalizes effectively to OOD samples whose latent variables closely resemble those seen during training, but its performance degrades as this similarity decreases. These findings provide foundational insights into the strengths and limitations of CoT prompting under OOD conditions and suggest directions for developing more resilient reasoning strategies in future LLMs.

[Arxiv](https://arxiv.org/abs/2504.12991)