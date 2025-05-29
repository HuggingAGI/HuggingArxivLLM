# 评估大型语言模型样本训练顺序的影响：无需重新训练

发布时间：2025年05月28日

`LLM理论` `机器学习`

> Estimating the Effects of Sample Training Orders for Large Language Models without Retraining

# 摘要

> 训练样本的顺序对大型语言模型（LLMs）至关重要，不仅影响模型的外部表现，还深刻影响其内部学习动态。然而，传统研究方法通常需要通过改变样本顺序重新训练模型，这对于LLMs而言计算成本过高。在本研究中，我们提出了一种无需重新训练的框架，有效改进了传统方法。该框架通过一阶和二阶泰勒展开近似Adam优化器的更新，并结合随机投影方法存储中间检查点，从而高效估计任意训练样本顺序下的模型参数。我们还将这一框架应用于两个关键研究问题：首先，在LLMs的训练课程设计中，我们提出了一种新型课程学习策略，通过结合估计的模型性能来优化课程提案，实现更智能的样本调度；其次，在分析LLMs的 memorization 和 generalization 效应时，我们利用该框架评估训练样本位置对其 memorization 和 generalization 能力的影响。大量实验结果验证了该框架在还原真实模型性能方面的有效性，同时展示了其在优化 LLM 训练课程和分析 LLMs 的 memorization 与 generalization 效应方面的巨大潜力。

> The order of training samples plays a crucial role in large language models (LLMs), significantly impacting both their external performance and internal learning dynamics. Traditional methods for investigating this effect generally require retraining the model with various sample orders, which is computationally infeasible for LLMs. In this work, we improve traditional methods by designing a retraining-free framework. By approximating Adam optimizer updates with first- and second-order Taylor expansions and utilizing random projection methods to store intermediate checkpoints, our framework can efficiently estimate model parameters for arbitrary training sample orders. Next, we apply our framework to two downstream research problems: (1) Training curriculum design for LLMs -- we base our retraining-free framework to propose a novel curriculum learning strategy that augments curriculum proposals with estimated model performances, enabling more informed sample scheduling. (2) LLMs' memorization and generalization effect analysis -- we use our retraining-free framework to estimate how the positions of training samples influence LLMs' capacity for memorization and generalization. We conduct extensive experiments to validate the effectiveness of our retraining-free framework in reproducing the true model performances, and further demonstrate its potential in optimizing LLM training curricula and analyzing the memorization and generalization effects of LLMs.

[Arxiv](https://arxiv.org/abs/2505.22042)