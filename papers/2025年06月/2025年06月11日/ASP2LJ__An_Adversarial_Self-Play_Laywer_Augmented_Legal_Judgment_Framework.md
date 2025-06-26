# ASP2LJ：一种基于对抗性自博弈的增强法律判决框架

发布时间：2025年06月11日

`LLM应用`

> ASP2LJ : An Adversarial Self-Play Laywer Augmented Legal Judgment Framework

# 摘要

> 法律判决预测（LJP）是大型语言模型（LLM）中的关键环节，旨在预测司法结果，包括法律条款、刑期及罚款。然而，LJP面临两大核心挑战：(1)长尾分布：现有数据集源自真实案例，但人工标注成本高昂且数据分布不均衡，导致模型性能下降；(2)律师改进：现有系统专注于提升法官的决策能力，却忽视了律师在优化论辩中的关键作用，这限制了整体司法准确性。为应对这些问题，我们提出了一种名为ASP2LJ的对抗性自博弈律师增强法律判决框架。该框架集成了案例生成模块以应对长尾数据分布，并采用对抗性自博弈机制以提升律师的论辩技巧。我们的框架使法官能够参考进化的律师论辩，从而提高司法决策的客观性、公平性和合理性。此外，我们还引入了RareCases，一个针对中国罕见法律案件的数据集，其中包含120个尾部案例。我们在SimuCourt数据集和我们的RareCases数据集上展示了我们方法的有效性。实验结果表明，我们的框架带来了性能提升，证明了其应用价值。我们的贡献包括一个集成化的框架、一个罕见案例数据集，以及公开发布的数据集和代码，以支持自动司法系统的进一步研究。

> Legal Judgment Prediction (LJP) aims to predict judicial outcomes, including relevant legal charge, terms, and fines, which is a crucial process in Large Language Model(LLM). However, LJP faces two key challenges: (1)Long Tail Distribution: Current datasets, derived from authentic cases, suffer from high human annotation costs and imbalanced distributions, leading to model performance degradation. (2)Lawyer's Improvement: Existing systems focus on enhancing judges' decision-making but neglect the critical role of lawyers in refining arguments, which limits overall judicial accuracy. To address these issues, we propose an Adversarial Self-Play Lawyer Augmented Legal Judgment Framework, called ASP2LJ, which integrates a case generation module to tackle long-tailed data distributions and an adversarial self-play mechanism to enhance lawyers' argumentation skills. Our framework enables a judge to reference evolved lawyers' arguments, improving the objectivity, fairness, and rationality of judicial decisions. Besides, We also introduce RareCases, a dataset for rare legal cases in China, which contains 120 tail-end cases. We demonstrate the effectiveness of our approach on the SimuCourt dataset and our RareCases dataset. Experimental results show our framework brings improvements, indicating its utilization. Our contributions include an integrated framework, a rare-case dataset, and publicly releasing datasets and code to support further research in automated judicial systems.

[Arxiv](https://arxiv.org/abs/2506.18768)