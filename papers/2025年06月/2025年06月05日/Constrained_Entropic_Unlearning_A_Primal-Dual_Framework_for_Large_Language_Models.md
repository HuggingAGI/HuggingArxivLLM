# 约束熵学习遗忘：大型语言模型的原对偶框架方法

发布时间：2025年06月05日

`LLM理论` `人工智能`

> Constrained Entropic Unlearning: A Primal-Dual Framework for Large Language Models

# 摘要

> 大语言模型（LLMs）在实际应用中日益面临遗忘敏感、过时或专有信息的需求。现有遗忘方法通常将遗忘与保留建模为正则化权衡，将两者目标整合为单一标量损失函数。这通常导致优化不稳定，并在激进遗忘下显著降低保留数据的性能表现。

我们提出了一种全新的LLM遗忘框架，将其视为约束优化问题：通过创新的对数几率边界展平损失强制执行遗忘，该损失明确引导遗忘集上的输出分布趋向均匀性，同时通过独立保留集上的硬约束来保持保留能力。与基于熵的目标相比，我们的损失函数无需Softmax运算，数值稳定且保持非消失梯度，从而实现更高效和稳健的优化。我们采用可扩展的原-对偶算法求解该约束问题，通过原-对偶变量的动态揭示遗忘与保留之间的权衡关系。

在TOFU和MUSE基准测试中，针对多种LLM架构的评估表明，我们的方法始终达到或超越现有最优基线，有效去除目标信息同时保持下游实用性。

> Large Language Models (LLMs) deployed in real-world settings increasingly face the need to unlearn sensitive, outdated, or proprietary information. Existing unlearning methods typically formulate forgetting and retention as a regularized trade-off, combining both objectives into a single scalarized loss. This often leads to unstable optimization and degraded performance on retained data, especially under aggressive forgetting. We propose a new formulation of LLM unlearning as a constrained optimization problem: forgetting is enforced via a novel logit-margin flattening loss that explicitly drives the output distribution toward uniformity on a designated forget set, while retention is preserved through a hard constraint on a separate retain set. Compared to entropy-based objectives, our loss is softmax-free, numerically stable, and maintains non-vanishing gradients, enabling more efficient and robust optimization. We solve the constrained problem using a scalable primal-dual algorithm that exposes the trade-off between forgetting and retention through the dynamics of the dual variable. Evaluations on the TOFU and MUSE benchmarks across diverse LLM architectures demonstrate that our approach consistently matches or exceeds state-of-the-art baselines, effectively removing targeted information while preserving downstream utility.

[Arxiv](https://arxiv.org/abs/2506.05314)