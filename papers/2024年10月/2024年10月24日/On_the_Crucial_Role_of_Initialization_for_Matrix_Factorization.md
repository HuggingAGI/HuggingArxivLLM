# 初始化在矩阵分解中的关键作用

发布时间：2024年10月24日

`LLM理论

解释：这篇论文主要探讨了低秩矩阵分解问题及其在优化中的初始化方法，特别是如何通过Nystrom初始化提升ScaledGD的收敛性，并将其应用于大型语言模型的微调中。这些内容属于对大型语言模型（LLM）的理论研究和优化方法的改进，因此分类为LLM理论。` `机器学习` `优化算法`

> On the Crucial Role of Initialization for Matrix Factorization

# 摘要

> 本研究重新探讨了经典的低秩矩阵分解问题，揭示了初始化在非凸非光滑优化中的关键作用。我们提出的Nystrom初始化显著提升了ScaledGD在对称和非对称矩阵分解中的全局收敛性。特别地，我们证明了在以往仅知线性收敛的情况下，Nystrom初始化的ScaledGD实现了二次收敛。此外，我们将这一初始化方法应用于基础模型微调中常用的低秩适配器（LoRA），提出了NoRA方法。NoRA在1B到7B参数的大型语言和扩散模型中，在多种下游任务和模型规模上均展现出卓越性能。

> This work revisits the classical low-rank matrix factorization problem and unveils the critical role of initialization in shaping convergence rates for such nonconvex and nonsmooth optimization. We introduce Nystrom initialization, which significantly improves the global convergence of Scaled Gradient Descent (ScaledGD) in both symmetric and asymmetric matrix factorization tasks. Specifically, we prove that ScaledGD with Nystrom initialization achieves quadratic convergence in cases where only linear rates were previously known. Furthermore, we extend this initialization to low-rank adapters (LoRA) commonly used for finetuning foundation models. Our approach, NoRA, i.e., LoRA with Nystrom initialization, demonstrates superior performance across various downstream tasks and model scales, from 1B to 7B parameters, in large language and diffusion models.

[Arxiv](https://arxiv.org/abs/2410.18965)