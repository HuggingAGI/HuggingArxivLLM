# AltFS：深度推荐系统中借助大型语言模型的轻代理特征选择

发布时间：2024年12月11日

`LLM应用` `推荐系统` `特征选择`

> AltFS: Agency-light Feature Selection with Large Language Models in Deep Recommender Systems

# 摘要

> 特征选择在推荐系统中对提升模型效率和预测性能极为关键。传统方法依靠诸如决策树或神经网络之类的代理模型来评估特征重要性。然而，此方法存在固有局限，因为代理模型可能因欠佳的训练条件（比如特征共线性、高维稀疏性和数据不足）而无法在所有场景中有效学习。在本文中，我们提出了 AltFS，这是一种用于深度推荐系统的轻代理特征选择方法。AltFS 把来自大型语言模型（LLMs）的语义推理与代理模型的特定任务学习相融合。起初，LLMs 会生成特征重要性的语义排序，随后由代理模型加以细化，将世界知识与特定任务的见解相结合。在来自真实推荐平台的三个公共数据集上开展的大量实验证实了 AltFS 的有效性。我们的代码公开可用，以保证可重复性。

> Feature selection is crucial in recommender systems for improving model efficiency and predictive performance. Traditional methods rely on agency models, such as decision trees or neural networks, to estimate feature importance. However, this approach is inherently limited, as the agency models may fail to learn effectively in all scenarios due to suboptimal training conditions (e.g., feature collinearity, high-dimensional sparsity, and data insufficiency). In this paper, we propose AltFS, an Agency-light Feature Selection method for deep recommender systems. AltFS integrates semantic reasoning from Large Language Models (LLMs) with task-specific learning from agency models. Initially, LLMs will generate a semantic ranking of feature importance, which is then refined by an agency model, combining world knowledge with task-specific insights. Extensive experiments on three public datasets from real-world recommender platforms demonstrate the effectiveness of AltFS. Our code is publicly available for reproducibility.

[Arxiv](https://arxiv.org/abs/2412.08516)