# LayerIF：基于影响函数评估大型语言模型的层质量

发布时间：2025年05月27日

`LLM理论` `机器学习`

> LayerIF: Estimating Layer Quality for Large Language Models using Influence Functions

# 摘要

> 预训练大型语言模型（LLMs）在各类任务中表现优异，但针对特定下游应用时，各层训练质量的显著差异却限制了其性能。因此，我们需要一种综合考虑模型架构和训练数据的层训练质量评估方法。现有方法主要依赖模型中心的启发式策略（如谱统计、异常检测或均匀分配），却忽视了数据的影响。为了解决这一问题，我们提出了LayerIF，这是一个基于影响函数的数据驱动框架，旨在以一种原理化且任务敏感的方式量化各层的训练质量。通过隔离每层的梯度，并通过计算层间影响来衡量验证损失对训练样本的敏感性，我们得出了数据驱动的层重要性估计。值得注意的是，我们的方法为同一LLM生成任务特定的层重要性评估，揭示了不同测试时评估任务中各层的专门化方式。我们通过将其应用于两个下游应用展示了其实用性：(a) LoRA-MoE架构中的专家分配，以及(b) LLM剪枝中的层间稀疏分布。在多个LLM架构上的实验表明，我们的模型不可知、影响引导的分配方法在任务性能上带来了持续的提升。

> Pretrained Large Language Models (LLMs) achieve strong performance across a wide range of tasks, yet exhibit substantial variability in the various layers' training quality with respect to specific downstream applications, limiting their downstream performance.It is therefore critical to estimate layer-wise training quality in a manner that accounts for both model architecture and training data. However, existing approaches predominantly rely on model-centric heuristics (such as spectral statistics, outlier detection, or uniform allocation) while overlooking the influence of data. To address these limitations, we propose LayerIF, a data-driven framework that leverages Influence Functions to quantify the training quality of individual layers in a principled and task-sensitive manner. By isolating each layer's gradients and measuring the sensitivity of the validation loss to training examples by computing layer-wise influences, we derive data-driven estimates of layer importance. Notably, our method produces task-specific layer importance estimates for the same LLM, revealing how layers specialize for different test-time evaluation tasks. We demonstrate the utility of our scores by leveraging them for two downstream applications: (a) expert allocation in LoRA-MoE architectures and (b) layer-wise sparsity distribution for LLM pruning. Experiments across multiple LLM architectures demonstrate that our model-agnostic, influence-guided allocation leads to consistent gains in task performance.

[Arxiv](https://arxiv.org/abs/2505.23811)