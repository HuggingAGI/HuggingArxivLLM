# 通过预处理对角化改进自适应矩优化

发布时间：2025年02月11日

`LLM理论`

> Improving Adaptive Moment Optimization via Preconditioner Diagonalization

# 摘要

> 现代自适应优化方法，如Adam及其变体，已成为深度学习领域最广泛使用的工具。这些算法通过动态调整更新步长，基于对梯度统计的估计，提供了自动化的优化机制。与传统随机梯度下降相比，这些自适应方法通常展现出更强的鲁棒性，能够更好地适应模型规模和超参数调节。然而，现有方法所依赖的梯度统计量往往未能充分利用梯度协方差信息，这可能导致参数空间某些方向上的更新效果不佳，从而减缓收敛速度。在本研究中，我们以结构化预条件矩阵的形式追踪此类协方差统计量。与其它研究不同，我们的方法并未直接对矩阵进行近似估计。相反，我们采用了一种可逆变换，将预条件矩阵映射至一个新的空间，在其中该矩阵近似呈现对角化特性。这一创新使得在变换空间中对预条件矩阵进行对角近似成为可能，从而带来多个计算优势。实证结果表明，我们的方法能够显著提升现代自适应优化器的收敛速度。特别地，针对像LLaMA这样的大型语言模型，与基线Adam相比，我们的方法可实现2倍的速度提升。此外，我们的方法还可与内存高效的优化器如Adafactor无缝结合，以有效管理计算开销。

> Modern adaptive optimization methods, such as Adam and its variants, have emerged as the most widely used tools in deep learning over recent years. These algorithms offer automatic mechanisms for dynamically adjusting the update step based on estimates of gradient statistics. Compared to traditional algorithms like Stochastic Gradient Descent, these adaptive methods are typically more robust to model scale and hyperparameter tuning. However, the gradient statistics employed by these methods often do not leverage sufficient gradient covariance information, leading to suboptimal updates in certain directions of the parameter space and potentially slower convergence. In this work, we keep track of such covariance statistics in the form of a structured preconditioner matrix. Unlike other works, our approach does not apply direct approximations to estimate this matrix. We instead implement an invertible transformation that maps the preconditioner matrix into a new space where it becomes approximately diagonal. This enables a diagonal approximation of the preconditioner matrix in the transformed space, offering several computational advantages. Empirical results show that our approach can substantially enhance the convergence speed of modern adaptive optimizers. Notably, for large language models like LLaMA, we can achieve a speedup of 2x compared to the baseline Adam. Additionally, our method can be integrated with memory-efficient optimizers like Adafactor to manage computational overhead.

[Arxiv](https://arxiv.org/abs/2502.07488)