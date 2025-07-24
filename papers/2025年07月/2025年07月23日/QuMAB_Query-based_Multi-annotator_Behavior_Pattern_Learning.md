# QuMAB：基于查询的多标注者行为模式学习

发布时间：2025年07月23日

`其他` `机器学习` `数据科学`

> QuMAB: Query-based Multi-annotator Behavior Pattern Learning

# 摘要

> 传统多标注者学习通过聚合多样化的标注结果来逼近单一真实标签，将标注者分歧视为噪声。然而，这一方法面临两大挑战：主观任务缺乏绝对真实标签，且标注覆盖率稀疏导致聚合结果统计不可靠。我们提出从样本聚合转向标注者行为建模的全新范式。通过将标注者分歧视为有价值的信息，建模标注者特定行为模式可重构未标注数据，从而降低标注成本、增强聚合可靠性并解释标注者决策行为。为此，我们提出了QuMATL（基于查询的多标注者行为模式学习），它利用轻量级查询建模个体标注者，同时捕捉标注者间相关性作为隐式正则化，防止过度拟合稀疏数据，保持个性化并提升泛化能力。通过可视化标注者关注区域，提供可解释的行为理解分析。我们贡献了两个大规模数据集：STREET（4,300个标签/标注者）和AMER（平均每标注者3,118个标签），这是首个多模态多标注者数据集。

> Multi-annotator learning traditionally aggregates diverse annotations to approximate a single ground truth, treating disagreements as noise. However, this paradigm faces fundamental challenges: subjective tasks often lack absolute ground truth, and sparse annotation coverage makes aggregation statistically unreliable. We introduce a paradigm shift from sample-wise aggregation to annotator-wise behavior modeling. By treating annotator disagreements as valuable information rather than noise, modeling annotator-specific behavior patterns can reconstruct unlabeled data to reduce annotation cost, enhance aggregation reliability, and explain annotator decision behavior. To this end, we propose QuMATL (Query-based Multi-Annotator Behavior Pattern Learning), which uses light-weight queries to model individual annotators while capturing inter-annotator correlations as implicit regularization, preventing overfitting to sparse individual data while maintaining individualization and improving generalization, with a visualization of annotator focus regions offering an explainable analysis of behavior understanding. We contribute two large-scale datasets with dense per-annotator labels: STREET (4,300 labels/annotator) and AMER (average 3,118 labels/annotator), the first multimodal multi-annotator dataset.

[Arxiv](https://arxiv.org/abs/2507.17653)