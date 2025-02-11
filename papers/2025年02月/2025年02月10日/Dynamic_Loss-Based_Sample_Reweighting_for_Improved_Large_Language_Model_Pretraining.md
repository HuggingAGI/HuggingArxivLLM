# 基于动态损失的样本重加权方法，优化大规模语言模型的预训练过程。

发布时间：2025年02月10日

`LLM理论` `人工智能` `机器学习`

> Dynamic Loss-Based Sample Reweighting for Improved Large Language Model Pretraining

# 摘要

> 大规模异质数据集的预训练是实现LLMs在多样化下游任务中达到最先进性能的关键。然而，现有训练范式忽视了单个样本的重要性和相关性，将所有样本同等对待。现有的重新加权策略主要关注数据组层面的重要性，未能利用细粒度的实例级信息，也未能随着训练的进行动态适应单个样本的重要性。在本文中，我们提出了新的动态实例级数据重新加权算法，旨在提高LLM预训练的效率和效果。我们的方法根据每个训练样本的损失值在线调整其权重，使模型能够动态聚焦于当前训练阶段更具信息量或更重要的样本。特别地，我们的框架使我们能够系统地设计重新加权策略，优先考虑冗余或无信息的数据，我们发现这些策略往往效果最佳。此外，我们开发了一种新的理论框架，用于分析基于损失的重新加权对基于梯度优化收敛的影响，首次正式描述了这些策略如何影响收敛界限。通过从预训练70亿和14亿参数的LLMs到小型语言模型和线性回归问题的实证验证，结果表明，我们的基于损失的重新加权方法能够实现更快的收敛和显著提升的性能。

> Pretraining large language models (LLMs) on vast and heterogeneous datasets is crucial for achieving state-of-the-art performance across diverse downstream tasks. However, current training paradigms treat all samples equally, overlooking the importance or relevance of individual samples throughout the training process. Existing reweighting strategies, which primarily focus on group-level data importance, fail to leverage fine-grained instance-level information and do not adapt dynamically to individual sample importance as training progresses. In this paper, we introduce novel algorithms for dynamic, instance-level data reweighting aimed at improving both the efficiency and effectiveness of LLM pretraining. Our methods adjust the weight of each training sample based on its loss value in an online fashion, allowing the model to dynamically focus on more informative or important samples at the current training stage. In particular, our framework allows us to systematically devise reweighting strategies deprioritizing redundant or uninformative data, which we find tend to work best. Furthermore, we develop a new theoretical framework for analyzing the impact of loss-based reweighting on the convergence of gradient-based optimization, providing the first formal characterization of how these strategies affect convergence bounds. We empirically validate our approach across a spectrum of tasks, from pretraining 7B and 1.4B parameter LLMs to smaller-scale language models and linear regression problems, demonstrating that our loss-based reweighting approach can lead to faster convergence and significantly improved performance.

[Arxiv](https://arxiv.org/abs/2502.06733)