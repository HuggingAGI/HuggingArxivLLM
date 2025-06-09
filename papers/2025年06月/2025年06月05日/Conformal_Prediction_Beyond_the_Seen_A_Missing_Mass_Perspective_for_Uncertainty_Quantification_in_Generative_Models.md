# 超越已见的符合性预测：从缺失质量视角看生成模型的不确定性量化

发布时间：2025年06月05日

`LLM理论` `人工智能` `生成模型`

> Conformal Prediction Beyond the Seen: A Missing Mass Perspective for Uncertainty Quantification in Generative Models

# 摘要

> 生成式AI模型（如大型语言模型（LLMs））的安全部署离不开不确定性量化（UQ），尤其在高风险应用中。符合性预测（CP）提供了一个基于原理的不确定性量化框架，但传统方法主要关注回归和分类任务，依赖于几何距离或softmax分数：这些工具假设了结构化的输出。我们突破这一范式，研究仅基于查询的设置下的符合性预测，其中预测集必须仅通过有限的查询到一个黑箱生成模型来构建，从而引入了覆盖范围、测试时间查询预算和信息量之间的新权衡。

我们引入了带查询预言的符合性预测（CPQ），这是一个框架，用于表征这些目标之间的最优交互。我们的有限样本算法建立在两个核心原则之上：一个原则规定了最优查询策略，另一个原则定义了从查询样本到预测集的最优映射。值得注意的是，这两个原则都植根于统计学中的经典缺失质量问题。具体而言，最优查询策略取决于缺失质量的衰减率，或其导数，为此我们开发了一种新型估计器。与此同时，最优映射依赖于缺失质量本身，我们使用Good-Turing估计器对其进行估计。

然后，我们将注意力转向在语言模型上的实现，其中输出是庞大、多变且经常未明确的。在三个真实世界开放任务和两个LLM上的精细实验表明，CPQ适用于任何黑箱LLM，并突显了：（1）每个原则对CPQ性能的个体贡献，以及（2）CPQ生成显著更具有信息量的预测集的能力，相较于现有用于语言不确定性量化的符合性方法。


> Uncertainty quantification (UQ) is essential for safe deployment of generative AI models such as large language models (LLMs), especially in high stakes applications. Conformal prediction (CP) offers a principled uncertainty quantification framework, but classical methods focus on regression and classification, relying on geometric distances or softmax scores: tools that presuppose structured outputs. We depart from this paradigm by studying CP in a query only setting, where prediction sets must be constructed solely from finite queries to a black box generative model, introducing a new trade off between coverage, test time query budget, and informativeness. We introduce Conformal Prediction with Query Oracle (CPQ), a framework characterizing the optimal interplay between these objectives. Our finite sample algorithm is built on two core principles: one governs the optimal query policy, and the other defines the optimal mapping from queried samples to prediction sets. Remarkably, both are rooted in the classical missing mass problem in statistics. Specifically, the optimal query policy depends on the rate of decay, or the derivative, of the missing mass, for which we develop a novel estimator. Meanwhile, the optimal mapping hinges on the missing mass itself, which we estimate using Good Turing estimators. We then turn our focus to implementing our method for language models, where outputs are vast, variable, and often under specified. Fine grained experiments on three real world open ended tasks and two LLMs, show CPQ applicability to any black box LLM and highlight: (1) individual contribution of each principle to CPQ performance, and (2) CPQ ability to yield significantly more informative prediction sets than existing conformal methods for language uncertainty quantification.

[Arxiv](https://arxiv.org/abs/2506.05497)