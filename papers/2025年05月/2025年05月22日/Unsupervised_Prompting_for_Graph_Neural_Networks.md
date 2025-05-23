# 无监督提示在图神经网络中的应用

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）的上下文学习方法应用于图神经网络（GNNs）的提示调优中，提出了一种无监督的提示方法，以提升预训练GNN在目标数据集上的泛化能力。该研究属于将LLM技术应用于其他模型的范畴，因此归类为LLM应用。` `机器学习` `人工智能`

> Unsupervised Prompting for Graph Neural Networks

# 摘要

> 针对图神经网络（GNNs）的提示调优方法已成为解决预训练与微调之间语义差距的热门方案。然而，现有的GNN提示方法依赖于标注数据，并且需要轻量级的下游任务微调。与此同时，大型语言模型（LLMs）的上下文学习方法展现出令人鼓舞的性能，无需参数更新，且几乎不依赖标注数据。受这些方法启发，本研究首先提出一个具有挑战性的问题设定，用于评估GNN提示方法。该设定鼓励一种提示函数，在不更新GNN参数且无标注数据的情况下，提升预训练GNN在目标数据集上的泛化能力。接下来，我们提出了一种基于伪标签一致性正则化的完全无监督提示方法。通过两种正则化技术，我们使提示图的分布与原始数据对齐，并减少预测偏差。在我们设定的问题背景下，通过大量实验，我们证明了我们的无监督方法优于现有依赖标注数据的最先进提示方法。

> Prompt tuning methods for Graph Neural Networks (GNNs) have become popular to address the semantic gap between pre-training and fine-tuning steps. However, existing GNN prompting methods rely on labeled data and involve lightweight fine-tuning for downstream tasks. Meanwhile, in-context learning methods for Large Language Models (LLMs) have shown promising performance with no parameter updating and no or minimal labeled data. Inspired by these approaches, in this work, we first introduce a challenging problem setup to evaluate GNN prompting methods. This setup encourages a prompting function to enhance a pre-trained GNN's generalization to a target dataset under covariate shift without updating the GNN's parameters and with no labeled data. Next, we propose a fully unsupervised prompting method based on consistency regularization through pseudo-labeling. We use two regularization techniques to align the prompted graphs' distribution with the original data and reduce biased predictions. Through extensive experiments under our problem setting, we demonstrate that our unsupervised approach outperforms the state-of-the-art prompting methods that have access to labels.

[Arxiv](https://arxiv.org/abs/2505.16903)