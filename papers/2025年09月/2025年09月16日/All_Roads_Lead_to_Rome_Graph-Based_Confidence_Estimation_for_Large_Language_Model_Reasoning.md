# 条条大路通罗马：基于图的大型语言模型推理置信度估计

发布时间：2025年09月16日

`LLM应用` `基础理论`

> All Roads Lead to Rome: Graph-Based Confidence Estimation for Large Language Model Reasoning

# 摘要

> 置信度估计是大型语言模型（LLMs）可靠部署的关键。现有方法多针对事实性问答任务设计，在推理任务上的泛化能力较差。为解决这一问题，我们提出一套无需训练、基于图的置信度估计方法，专门适配推理任务。该方法将推理路径建模为有向图，通过挖掘中心性、路径收敛和路径加权等图属性来估计置信度。在两个大型语言模型和三个推理数据集上的实验显示，新方法不仅提升了置信度估计效果，还增强了两个下游任务的性能表现。

> Confidence estimation is essential for the reliable deployment of large language models (LLMs). Existing methods are primarily designed for factual QA tasks and often fail to generalize to reasoning tasks. To address this gap, we propose a set of training-free, graph-based confidence estimation methods tailored to reasoning tasks. Our approach models reasoning paths as directed graphs and estimates confidence by exploiting graph properties such as centrality, path convergence, and path weighting. Experiments with two LLMs on three reasoning datasets demonstrate improved confidence estimation and enhanced performance on two downstream tasks.

[Arxiv](https://arxiv.org/abs/2509.12908)