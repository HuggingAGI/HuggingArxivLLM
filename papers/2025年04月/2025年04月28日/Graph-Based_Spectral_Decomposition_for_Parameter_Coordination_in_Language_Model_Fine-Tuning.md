# 基于图谱分解的语言模型微调参数协调方法

发布时间：2025年04月28日

`LLM理论

理由：这篇论文提出了一种新的参数协作优化算法，专注于提升大型语言模型的微调效率和结构感知能力。该方法通过图谱分析和拉普拉斯谱分解，设计了联合损失函数和谱过滤机制，属于对大型语言模型优化的理论研究，因此归类为LLM理论。` `人工智能`

> Graph-Based Spectral Decomposition for Parameter Coordination in Language Model Fine-Tuning

# 摘要

> 本文提出了一种结合图谱分析的参数协作优化算法，旨在提升大型语言模型的微调效率与结构感知能力。在该方法中，预训练语言模型的参数被视为图中的节点。通过构建加权图并应用拉普拉斯谱分解，实现参数空间的频域建模与结构表征。基于此结构，设计了一种联合损失函数，将任务损失与谱正则化项相结合，以促进参数间的协作更新。此外，在优化阶段引入了谱过滤机制，通过结构感知的方式调整梯度，从而提升模型的训练稳定性和收敛行为。该方法在多种任务上进行了评估，包括传统微调对比、少样本泛化测试及收敛速度分析。在所有设置下，所提出的方法均表现出优越性能。实验结果证实，谱协作优化框架有效降低了参数扰动，提升了微调质量，同时保持了整体模型性能。这项研究通过推进大规模模型的参数高效训练方法，强化了深度学习优化中结构信号处理的重要性，并为提升语言模型的适应性和性能提供了一个稳健且通用的框架，为人工智能领域做出了重要贡献。

> This paper proposes a parameter collaborative optimization algorithm for large language models, enhanced with graph spectral analysis. The goal is to improve both fine-tuning efficiency and structural awareness during training. In the proposed method, the parameters of a pre-trained language model are treated as nodes in a graph. A weighted graph is constructed, and Laplacian spectral decomposition is applied to enable frequency-domain modeling and structural representation of the parameter space. Based on this structure, a joint loss function is designed. It combines the task loss with a spectral regularization term to facilitate collaborative updates among parameters. In addition, a spectral filtering mechanism is introduced during the optimization phase. This mechanism adjusts gradients in a structure-aware manner, enhancing the model's training stability and convergence behavior. The method is evaluated on multiple tasks, including traditional fine-tuning comparisons, few-shot generalization tests, and convergence speed analysis. In all settings, the proposed approach demonstrates superior performance. The experimental results confirm that the spectral collaborative optimization framework effectively reduces parameter perturbations and improves fine-tuning quality while preserving overall model performance. This work contributes significantly to the field of artificial intelligence by advancing parameter-efficient training methodologies for large-scale models, reinforcing the importance of structural signal processing in deep learning optimization, and offering a robust, generalizable framework for enhancing language model adaptability and performance.

[Arxiv](https://arxiv.org/abs/2504.19583)