# PolarGrad：从统一预处理视角看一类矩阵梯度优化器

发布时间：2025年05月27日

`LLM理论` `优化算法`

> PolarGrad: A Class of Matrix-Gradient Optimizers from a Unifying Preconditioning Perspective

# 摘要

> 随着深度学习模型和数据集规模的持续增长，高效优化方法的重要性日益凸显。虽然Adam和AdamW等预条件梯度方法已成为训练神经网络和大型语言模型的标准选择，但Shampoo和Muon等利用梯度矩阵结构的结构感知预条件优化器已展现出更快收敛的显著优势。本文提出了一种分析“矩阵感知”预条件方法的统一框架，不仅揭示了Muon及相关优化器的有效性，还催生了一类新的结构感知预条件方法。该框架的关键贡献在于明确区分了将神经网络权重视为向量的预条件策略（解决曲率各向异性）与考虑其矩阵结构的策略（解决梯度各向异性）。这一视角为语言模型预训练中的若干经验现象提供了新见解，包括Adam的训练不稳定性、Muon的加速收敛以及Adam学习率预热的必要性。基于此框架，我们引入了PolarGrad，一种基于矩阵值梯度极分解的新型预条件优化方法。作为特殊实例，PolarGrad包含梯度核范数缩放的Muon更新。我们提供了这些方法的数值实现，借助高效的数值极分解算法提升收敛速度。在多种矩阵优化问题和语言模型预训练任务的广泛评估中，PolarGrad的表现优于Adam和Muon。

> The ever-growing scale of deep learning models and datasets underscores the critical importance of efficient optimization methods. While preconditioned gradient methods such as Adam and AdamW are the de facto optimizers for training neural networks and large language models, structure-aware preconditioned optimizers like Shampoo and Muon, which utilize the matrix structure of gradients, have demonstrated promising evidence of faster convergence. In this paper, we introduce a unifying framework for analyzing "matrix-aware" preconditioned methods, which not only sheds light on the effectiveness of Muon and related optimizers but also leads to a class of new structure-aware preconditioned methods. A key contribution of this framework is its precise distinction between preconditioning strategies that treat neural network weights as vectors (addressing curvature anisotropy) versus those that consider their matrix structure (addressing gradient anisotropy). This perspective provides new insights into several empirical phenomena in language model pre-training, including Adam's training instabilities, Muon's accelerated convergence, and the necessity of learning rate warmup for Adam. Building upon this framework, we introduce PolarGrad, a new class of preconditioned optimization methods based on the polar decomposition of matrix-valued gradients. As a special instance, PolarGrad includes Muon with updates scaled by the nuclear norm of the gradients. We provide numerical implementations of these methods, leveraging efficient numerical polar decomposition algorithms for enhanced convergence. Our extensive evaluations across diverse matrix optimization problems and language model pre-training tasks demonstrate that PolarGrad outperforms both Adam and Muon.

[Arxiv](https://arxiv.org/abs/2505.21799)