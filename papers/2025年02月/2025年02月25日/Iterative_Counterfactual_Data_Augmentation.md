# 迭代反事实数据扩增

发布时间：2025年02月25日

`LLM应用` `数据增强` `机器学习`

> Iterative Counterfactual Data Augmentation

# 摘要

> 反事实数据增强（CDA）是一种通过生成具有相反偏见的互补数据集来控制训练数据信息或偏见的方法。以往研究多依赖手工规则或算法化CDA方法，这些方法可能在增强数据中遗留干扰信息。本研究提出迭代CDA（ICDA），通过初始高噪声干预，可收敛至噪声显著降低的状态。我们的ICDA生成的数据集使训练中的目标信号与标签保持高互信息，同时减少无关信号干扰。实验表明，基于增强数据集的训练能生成更符合人类标注的文档解释。实验涵盖六个人工数据集及两个大语言模型生成数据集。

> Counterfactual data augmentation (CDA) is a method for controlling information or biases in training datasets by generating a complementary dataset with typically opposing biases. Prior work often either relies on hand-crafted rules or algorithmic CDA methods which can leave unwanted information in the augmented dataset. In this work, we show iterative CDA (ICDA) with initial, high-noise interventions can converge to a state with significantly lower noise. Our ICDA procedure produces a dataset where one target signal in the training dataset maintains high mutual information with a corresponding label and the information of spurious signals are reduced. We show training on the augmented datasets produces rationales on documents that better align with human annotation. Our experiments include six human produced datasets and two large-language model generated datasets.

[Arxiv](https://arxiv.org/abs/2502.18249)