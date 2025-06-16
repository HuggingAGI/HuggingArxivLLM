# # 在上下文中酿造知识：从知识蒸馏的视角解读In-Context Learning

发布时间：2025年06月13日

`LLM理论

摘要中讨论了上下文学习（ICL）的内在机制，并提出了一个全新的理论视角，将其解释为隐式的知识蒸馏（KD）形式。论文推导了基于Rademacher复杂度的泛化界限，并分析了蒸馏权重的偏差与提示分布和目标分布之间的关系。这些内容属于对大型语言模型理论机制的深入研究，因此归类为LLM理论。` `机器学习`

> Brewing Knowledge in Context: Distillation Perspectives on In-Context Learning

# 摘要

> 上下文学习 (ICL) 让大型语言模型 (LLMs) 能在不更新权重的情况下解决新任务。尽管 ICL 在实际应用中表现优异，但其内在机制仍是个谜，限制了我们对其的解释、优化和可靠应用。本文提出了一种全新理论视角，将 ICL 解释为一种隐式的知识蒸馏 (KD) 形式，其中提示演示引导模型在推理过程中构建特定任务的参考模型。基于此视角，我们推导出一个基于 Rademacher 复杂度的泛化界限，并证明蒸馏权重的偏差与提示分布和目标分布之间的最大均值差异 (MMD) 成线性增长。这一理论框架不仅解释了多个经验现象，还统一了此前基于梯度和分布的分析方法。值得注意的是，我们首次将推理时的注意力机制正式化为蒸馏过程，这为未来的提示工程和自动化演示选择提供了宝贵的理论洞见。

> In-context learning (ICL) allows large language models (LLMs) to solve novel tasks without weight updates. Despite its empirical success, the mechanism behind ICL remains poorly understood, limiting our ability to interpret, improve, and reliably apply it. In this paper, we propose a new theoretical perspective that interprets ICL as an implicit form of knowledge distillation (KD), where prompt demonstrations guide the model to form a task-specific reference model during inference. Under this view, we derive a Rademacher complexity-based generalization bound and prove that the bias of the distilled weights grows linearly with the Maximum Mean Discrepancy (MMD) between the prompt and target distributions. This theoretical framework explains several empirical phenomena and unifies prior gradient-based and distributional analyses. To the best of our knowledge, this is the first to formalize inference-time attention as a distillation process, which provides theoretical insights for future prompt engineering and automated demonstration selection.

[Arxiv](https://arxiv.org/abs/2506.11516)