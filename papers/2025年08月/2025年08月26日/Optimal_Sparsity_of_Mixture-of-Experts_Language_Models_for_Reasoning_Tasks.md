# # 面向推理任务的混合专家语言模型最优稀疏度

发布时间：2025年08月26日

`LLM理论` `基础理论`

> Optimal Sparsity of Mixture-of-Experts Language Models for Reasoning Tasks

# 摘要

> 经验性缩放定律驱动了大型语言模型（LLMs）的演进，但模型架构或数据流水线一旦改变，这些定律的系数便会随之偏移。混合专家（MoE）模型现已成为最先进系统的标配，它们带来了当前密集型模型前沿尚未触及的新稀疏性维度。我们研究了MoE稀疏性对两种核心能力的影响：记忆与推理。我们训练了多组MoE Transformer模型，在计算预算固定的前提下，系统调整总参数、激活参数及top-【数学公式】路由机制。我们记录了每个模型的预训练损失、下游任务损失及任务准确率，从而能够将训练-测试泛化差距与损失-准确率差距区分开。记忆基准测试的性能随总参数增加而单调提升，与训练损失的变化趋势相吻合。相比之下，尽管总参数和训练损失不断优化，推理性能却会趋于饱和，甚至出现倒退。若激活参数保持不变，仅调整top-【数学公式】几乎不会产生影响；而学习率、初始化等经典超参数对泛化差距的调节方向则与稀疏性一致。无论是训练后强化学习（GRPO）还是额外的测试时计算资源，都无法弥补过度稀疏模型的推理短板。我们的模型检查点、代码及日志已开源，具体地址为https://github.com/rioyokotalab/optimal-sparsity。

> Empirical scaling laws have driven the evolution of large language models (LLMs), yet their coefficients shift whenever the model architecture or data pipeline changes. Mixture-of-Experts (MoE) models, now standard in state-of-the-art systems, introduce a new sparsity dimension that current dense-model frontiers overlook. We investigate how MoE sparsity influences two distinct capability regimes: memorization and reasoning. We train families of MoE Transformers that systematically vary total parameters, active parameters, and top-$k$ routing while holding the compute budget fixed. For every model we record pre-training loss, downstream task loss, and task accuracy, allowing us to separate the train-test generalization gap from the loss-accuracy gap. Memorization benchmarks improve monotonically with total parameters, mirroring training loss. By contrast, reasoning performance saturates and can even regress despite continued gains in both total parameters and training loss. Altering top-$k$ alone has little effect when active parameters are constant, and classic hyperparameters such as learning rate and initialization modulate the generalization gap in the same direction as sparsity. Neither post-training reinforcement learning (GRPO) nor extra test-time compute rescues the reasoning deficit of overly sparse models. Our model checkpoints, code and logs are open-source at https://github.com/rioyokotalab/optimal-sparsity.

[Arxiv](https://arxiv.org/abs/2508.18672)