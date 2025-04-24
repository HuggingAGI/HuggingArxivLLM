# 高效GEMM加速器——传递数组：利用结果复用提升性能

发布时间：2025年04月22日

`LLM应用` `硬件优化` `计算加速`

> Transitive Array: An Efficient GEMM Accelerator with Result Reuse

# 摘要

> 深度神经网络 (DNNs) 和大型语言模型 (LLMs) 彻底改变了人工智能领域，但它们的部署在内存和计算资源方面面临巨大挑战，尤其是在资源受限的环境中。量化技术通过降低数据精度缓解了部分问题，主要集中在通用矩阵乘法 (GEMM) 上。本研究提出了一种新颖的稀疏性范式——传递稀疏性，它利用先前计算结果的复用来大幅减少 GEMM 运算中的计算开销。通过使用有向无环图表示传递关系，我们开发出一种高效策略来确定最优执行顺序，从而克服了与执行依赖和并行性相关的固有挑战。在此基础上，我们提出了 Transitive Array，这是一种无需乘法运算的加速器，专为在 GEMM 中利用传递稀疏性而设计。我们的架构在多个并行通道间实现了计算负载的有效平衡，确保了高效运行和资源的最优利用。全面评估表明，与最先进的加速器 Olive 和 BitVert 相比，Transitive Array 在保持与 LLaMA 模型相当的模型精度的同时，实现了约 7.46 倍和 3.97 倍的加速，以及 2.31 倍和 1.65 倍的能效提升。


> Deep Neural Networks (DNNs) and Large Language Models (LLMs) have revolutionized artificial intelligence, yet their deployment faces significant memory and computational challenges, especially in resource-constrained environments. Quantization techniques have mitigated some of these issues by reducing data precision, primarily focusing on General Matrix Multiplication (GEMM). This study introduces a novel sparsity paradigm, transitive sparsity, which leverages the reuse of previously computed results to substantially minimize computational overhead in GEMM operations. By representing transitive relations using a directed acyclic graph, we develop an efficient strategy for determining optimal execution orders, thereby overcoming inherent challenges related to execution dependencies and parallelism. Building on this foundation, we present the Transitive Array, a multiplication-free accelerator designed to exploit transitive sparsity in GEMM. Our architecture effectively balances computational workloads across multiple parallel lanes, ensuring high efficiency and optimal resource utilization. Comprehensive evaluations demonstrate that the Transitive Array achieves approximately 7.46$\times$ and 3.97$\times$ speedup and 2.31$\times$ and 1.65$\times$ energy reduction compared to state-of-the-art accelerators such as Olive and BitVert while maintaining comparable model accuracy on LLaMA models.

[Arxiv](https://arxiv.org/abs/2504.16339)