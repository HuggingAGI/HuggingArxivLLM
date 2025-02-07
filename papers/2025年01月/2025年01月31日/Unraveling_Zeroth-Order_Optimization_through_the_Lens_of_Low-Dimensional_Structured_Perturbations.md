# 从低维结构化扰动的视角解析零阶优化

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要讨论了零阶（ZO）优化方法在大型语言模型（LLM）微调中的应用，并提出了一个统一的理论框架来分析结构化扰动下的收敛性和泛化性。论文的核心内容集中在理论分析和优化方法的改进上，属于对LLM的理论研究范畴，因此应归类为LLM理论。` `优化算法` `机器学习`

> Unraveling Zeroth-Order Optimization through the Lens of Low-Dimensional Structured Perturbations

# 摘要

> # 摘要
零阶（ZO）优化在替代基于梯度的反向传播方法方面展现出巨大潜力，尤其是在黑箱优化和大型语言模型（LLM）微调中。然而，ZO方法因高方差的随机梯度估计器而收敛缓慢。尽管稀疏性和低秩约束等结构化扰动已被用于缓解这些问题，但其效果仍未被充分挖掘。本研究提出了一个统一的理论框架，分析了结构化扰动下ZO优化的收敛性和泛化性。我们发现高维度是主要瓶颈，并引入	extit{稳定秩}和	extit{有效重叠}的概念，解释结构化扰动如何减少梯度噪声并加速收敛。基于框架下的均匀稳定性，我们首次从理论上证明了这些扰动如何增强泛化性。此外，实证分析表明，	extbf{块坐标下降}（BCD）是一种有效的结构化扰动方法。大量实验证明，与现有方法相比，结合BCD的内存高效ZO（MeZO-BCD）在每次迭代的墙上时间上可提速高达$	imes	extbf{2.09}$，同时保持相似或更高的准确性。

> Zeroth-order (ZO) optimization has emerged as a promising alternative to gradient-based backpropagation methods, particularly for black-box optimization and large language model (LLM) fine-tuning. However, ZO methods suffer from slow convergence due to high-variance stochastic gradient estimators. While structured perturbations, such as sparsity and low-rank constraints, have been explored to mitigate these issues, their effectiveness remains highly under-explored. In this work, we develop a unified theoretical framework that analyzes both the convergence and generalization properties of ZO optimization under structured perturbations. We show that high dimensionality is the primary bottleneck and introduce the notions of \textit{stable rank} and \textit{effective overlap} to explain how structured perturbations reduce gradient noise and accelerate convergence. Using the uniform stability under our framework, we then provide the first theoretical justification for why these perturbations enhance generalization. Additionally, through empirical analysis, we identify that \textbf{block coordinate descent} (BCD) to be an effective structured perturbation method. Extensive experiments show that, compared to existing alternatives, memory-efficient ZO (MeZO) with BCD (\textit{MeZO-BCD}) can provide improved converge with a faster wall-clock time/iteration by up to $\times\textbf{2.09}$ while yielding similar or better accuracy.

[Arxiv](https://arxiv.org/abs/2501.19099)