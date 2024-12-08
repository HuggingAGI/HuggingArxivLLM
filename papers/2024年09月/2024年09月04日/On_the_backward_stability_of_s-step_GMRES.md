# 论 s 步 GMRES 的后向稳定性

发布时间：2024年09月04日

`其他` `计算机架构`

> On the backward stability of s-step GMRES

# 摘要

> 摘要：通信，也就是数据移动，是经典 Krylov 子空间方法求解器在现代计算机架构中性能的关键瓶颈。那些能避免通信的方法变体已被引入，它们在精确运算中虽等效，但在有限精度下可能不稳定。在本研究中，我们探讨了 s 步 GMRES（又称避免通信的 GMRES）的反向稳定性。我们给出了一个简化 s 步 GMRES 分析的框架，通过分离 QR 分解和最小二乘问题求解中的舍入误差影响，该框架涵盖标准 GMRES（s = 1）这一特殊情形。运用此框架，我们对采用流行块正交化方法（如块修改 Gram--Schmidt 和重新正交化块经典 Gram--Schmidt 算法）的 s 步 GMRES 进行了分析。一个实例展示了与经典 s 步 Arnoldi 过程相结合时 s 步 GMRES 所产生的不稳定性，并揭示了常见解决策略的局限性。为应对此问题，我们提出了一种改进的 Arnoldi 过程，它能在保证满意精度的同时允许更大的块大小 s，这一点已被我们的数值实验所证实。

> 
Abstract:Communication, i.e., data movement, is a critical bottleneck for the performance of classical Krylov subspace method solvers on modern computer architectures. Variants of these methods which avoid communication have been introduced, which, while equivalent in exact arithmetic, can be unstable in finite precision. In this work, we address the backward stability of s-step GMRES, also known as communication-avoiding GMRES. We present a framework for simplifying the analysis of s-step GMRES, which includes standard GMRES (s=1) as a special case, by isolating the effects of rounding errors in the QR factorization and the solution of the least squares problem. Using this framework, we analyze s-step GMRES with popular block orthogonalization methods: block modified Gram--Schmidt and reorthogonalized block classical Gram--Schmidt algorithms. An example illustrates the resulting instability of s-step GMRES when paired with the classical s-step Arnoldi process and shows the limitations of popular strategies for resolving this instability. To address this issue, we propose a modified Arnoldi process that allows for much larger block size s while maintaining satisfactory accuracy, as confirmed by our numerical experiments.
    

[Arxiv](https://arxiv.org/pdf/2409.03079)