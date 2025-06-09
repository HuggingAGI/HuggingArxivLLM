# BAQ：针对大型语言模型的高效位分配量化方法

发布时间：2025年06月05日

`LLM理论

摘要讨论了后训练模型量化技术，提出了一种新的量化位宽分配框架，通过海森矩阵和凸优化来优化位宽分配，从而减少量化带来的损失。这涉及到模型优化和理论分析，属于LLM理论的范畴。` `模型压缩`

> BAQ: Efficient Bit Allocation Quantization for Large Language Models

# 摘要

> 后训练模型量化是降低大型语言模型（LLMs）内存与计算成本的常用技术。然而，现有方法多依赖均匀或启发式位宽分配，未能充分考虑权重对量化噪声的非均匀敏感性。本文提出了一种基于海森矩阵代理敏感性指标的量化位宽分配新框架。通过关键假设，我们使得层/组件损失函数可表示为位宽的显式函数，从而将位分配问题转化为凸优化任务，其闭式解能够根据权重调整精度以最小化层量化损失。对这一解的分析揭示了若干关键见解（如等损失结构），并以此设计了	extbf{BAQ}（位分配量化）算法。BAQ在损失最小化与复杂度之间实现了良好平衡，可极小开销地集成到标准量化流水线中。实验结果表明，与GPTQ相比，BAQ在参数规模从125M到30B的大型语言模型上表现更优，相同位宽下困惑度降低了56倍。通过分析最优位分配问题的解，我们还为观察到的性能提升提供了理论解释。本文所有代码均可在https://github.com/CSU-ModelCompression/BAQ上获取。

> Post-training model quantization is a widely adopted technique for reducing the memory and computational costs of large language models (LLMs). However, most existing methods rely on uniform or heuristic bitwidth assignments, failing to account for the nonuniform sensitivity of weights to quantization noise. In this paper, we propose a novel framework for allocating quantization bitwidths based on sensitivity metrics derived from a Hessian proxy. We make key assumptions, which allow the layer/component-wise loss function to be expressed as an explicit function of the bitwidths. This enables a neat formulation of the bit allocation problem as a convex optimization task, whose closed-form solution adapts precision across weights to minimize the layer-wise quantization loss. Inspecting the solution provides several insights (such as the equal-loss structure), which are then exploited to design the proposed \textbf{BAQ} (Bit Allocation Quantization) algorithm. The proposed algorithm achieves a good trade-off between loss minimization and complexity and allows BAQ to be integrated into standard quantization pipelines with minimal overhead. Experimental results show that BAQ consistently outperforms GPTQ, achieving up to 56$\times$ lower perplexity at the same bitwidth on large language models ranging from 125M to 30B parameters. Leveraging our analytical results derived from solving the optimal bit allocation problem, we also provide a theoretical explanation for the observed gains. All codes of this paper are available at https://github.com/CSU-ModelCompression/BAQ.

[Arxiv](https://arxiv.org/abs/2506.05664)