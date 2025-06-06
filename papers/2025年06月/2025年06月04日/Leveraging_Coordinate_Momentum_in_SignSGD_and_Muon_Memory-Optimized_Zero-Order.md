# SignSGD与Muon算法中的坐标动量：内存优化零阶方法

发布时间：2025年06月04日

`LLM理论

论文摘要讨论了零阶优化方法在微调大型语言模型中的应用，提出了新的优化算法，并提供了理论上的收敛保证。这属于优化和训练方法的理论研究，因此归类为LLM理论。` `人工智能` `机器学习`

> Leveraging Coordinate Momentum in SignSGD and Muon: Memory-Optimized Zero-Order

# 摘要

> 微调大型语言模型（LLMs）是将其应用于下游任务的关键。然而，传统的一阶优化器如SGD和Adam在内存和计算成本上过于高昂，且随模型规模增加而显著增加。本文研究了零阶（ZO）优化方法作为一种高效替代方案，特别是在参数高效的微调技术（如LoRA）中。我们提出了$	exttt{JAGUAR SignSGD}$，一种基于动量的ZO算法，扩展了ZO SignSGD，参数需求与标准ZO SGD相同，且每迭代仅需$\mathcal{O}(1)$次函数评估。这是首个为随机ZO情况下的SignSGD建立严格收敛保证的研究。我们还提出了$	exttt{JAGUAR Muon}$，一种基于Muon优化器的新型ZO扩展，利用模型参数的矩阵结构，并提供了在任意随机噪声下的收敛速率。通过在具有挑战性的LLM微调基准测试上的广泛实验，我们证明了所提出的算法在收敛质量上达到了或超越了标准一阶方法，同时实现了显著的内存减少。我们的理论和实证结果确立了新的ZO优化方法作为资源受限的LLM适应的实用且理论坚实的方法。代码可在https://github.com/brain-mmo-lab/ZO_LLM获取。

> Fine-tuning Large Language Models (LLMs) is essential for adapting pre-trained models to downstream tasks. Yet traditional first-order optimizers such as Stochastic Gradient Descent (SGD) and Adam incur prohibitive memory and computational costs that scale poorly with model size. In this paper, we investigate zero-order (ZO) optimization methods as a memory- and compute-efficient alternative, particularly in the context of parameter-efficient fine-tuning techniques like LoRA. We propose $\texttt{JAGUAR SignSGD}$, a ZO momentum-based algorithm that extends ZO SignSGD, requiring the same number of parameters as the standard ZO SGD and only $\mathcal{O}(1)$ function evaluations per iteration. To the best of our knowledge, this is the first study to establish rigorous convergence guarantees for SignSGD in the stochastic ZO case. We further propose $\texttt{JAGUAR Muon}$, a novel ZO extension of the Muon optimizer that leverages the matrix structure of model parameters, and we provide its convergence rate under arbitrary stochastic noise. Through extensive experiments on challenging LLM fine-tuning benchmarks, we demonstrate that the proposed algorithms meet or exceed the convergence quality of standard first-order methods, achieving significant memory reduction. Our theoretical and empirical results establish new ZO optimization methods as a practical and theoretically grounded approach for resource-constrained LLM adaptation. Our code is available at https://github.com/brain-mmo-lab/ZO_LLM

[Arxiv](https://arxiv.org/abs/2506.04430)