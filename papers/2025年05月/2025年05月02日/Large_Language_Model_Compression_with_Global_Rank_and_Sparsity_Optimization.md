# # 基于全局秩与稀疏性优化的大型语言模型压缩

发布时间：2025年05月02日

`LLM理论` `人工智能` `机器学习`

> Large Language Model Compression with Global Rank and Sparsity Optimization

# 摘要

> 低秩与稀疏复合逼近是压缩大型语言模型（LLMs）的天然思路。然而，这一方法面临两大挑战：一是低秩矩阵与稀疏矩阵的交互协作，二是如何在不同层级间合理分配权重（因各层级冗余程度差异显著）。为应对这些挑战，我们提出了一种具备全局秩与稀疏性优化能力的两阶段LLM压缩方法。

值得注意的是，整体优化空间极为庞大，全面优化在计算上难以承受。因此，我们采用鲁棒主成分分析作为第一阶段，将LLMs的权重矩阵分解为低秩和稀疏两部分，分别覆盖包含结果低秩和稀疏矩阵的低维和稀疏空间。在第二阶段，我们提出了一种概率全局优化技术，旨在联合识别上述两个空间内的低秩与稀疏结构。

我们的方法亮点在于能够自动检测不同层级间的冗余，并管理稀疏与低秩组件之间的交互。大量实验结果表明，我们的方法在稀疏化和复合逼近方面显著超越了现有最优技术。

> Low-rank and sparse composite approximation is a natural idea to compress Large Language Models (LLMs). However, such an idea faces two primary challenges that adversely affect the performance of existing methods. The first challenge relates to the interaction and cooperation between low-rank and sparse matrices, while the second involves determining weight allocation across different layers, as redundancy varies considerably among them. To address these challenges, we propose a novel two-stage LLM compression method with the capability of global rank and sparsity optimization. It is noteworthy that the overall optimization space is vast, making comprehensive optimization computationally prohibitive. Therefore, to reduce the optimization space, our first stage utilizes robust principal component analysis to decompose the weight matrices of LLMs into low-rank and sparse components, which span the low dimensional and sparse spaces containing the resultant low-rank and sparse matrices, respectively. In the second stage, we propose a probabilistic global optimization technique to jointly identify the low-rank and sparse structures within the above two spaces. The appealing feature of our approach is its ability to automatically detect the redundancy across different layers and to manage the interaction between the sparse and low-rank components. Extensive experimental results indicate that our method significantly surpasses state-of-the-art techniques for sparsification and composite approximation.

[Arxiv](https://arxiv.org/abs/2505.03801)