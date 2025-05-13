# AKD：基于对抗性知识蒸馏的大型语言模型编码任务对齐方法

发布时间：2025年05月05日

`LLM应用` `软件开发` `代码生成`

> AKD : Adversarial Knowledge Distillation For Large Language Models Alignment on Coding tasks

# 摘要

> 大型语言模型（LLMs）在代码生成领域的广泛应用，以GitHub Copilotootnote{一款基于代码-LLM的编码扩展工具，用于协助代码补全任务}用户数突破百万为例，凸显了这些工具在提升开发者生产力方面的巨大潜力。然而，这种快速普及也引发了对生成代码质量、安全性和可靠性的深刻担忧。随着代码-LLMs的发展，模型扩展收益递减和新高质量训练数据匮乏等问题日益凸显。为应对这些挑战，本文提出了一种名为对抗性知识蒸馏（AKD）的创新方法。通过利用对抗生成的合成数据集，AKD能够将大型模型的能力高效地迁移到更小、更高效的模型中。通过系统性地对代码-LLMs的推理能力进行压力测试和优化，AKD不仅提升了模型的参数效率，还显著增强了其稳健性、可靠性和安全性。我们相信，这项工作代表了在现有数据和模型执行成本效益约束下，实现可靠自动化代码生成的关键一步。

> The widespread adoption of Large Language Models (LLMs) for code generation, exemplified by GitHub Copilot\footnote{A coding extension powered by a Code-LLM to assist in code completion tasks} surpassing a million users, highlights the transformative potential of these tools in improving developer productivity. However, this rapid growth also underscores critical concerns regarding the quality, safety, and reliability of the code they generate. As Code-LLMs evolve, they face significant challenges, including the diminishing returns of model scaling and the scarcity of new, high-quality training data. To address these issues, this paper introduces Adversarial Knowledge Distillation (AKD), a novel approach that leverages adversarially generated synthetic datasets to distill the capabilities of larger models into smaller, more efficient ones. By systematically stress-testing and refining the reasoning capabilities of Code-LLMs, AKD provides a framework for enhancing model robustness, reliability, and security while improving their parameter-efficiency. We believe this work represents a critical step toward ensuring dependable automated code generation within the constraints of existing data and the cost-efficiency of model execution.

[Arxiv](https://arxiv.org/abs/2505.06267)