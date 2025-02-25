# COSMOS：一款结合内存高效训练的混合自适应优化器，专为大型语言模型设计。

发布时间：2025年02月24日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）训练中的优化问题，提出了一种新的优化器COSMOS，属于理论层面的改进和创新。` `机器学习`

> COSMOS: A Hybrid Adaptive Optimizer for Memory-Efficient Training of LLMs

# 摘要

> 大型语言模型（LLMs）在各领域表现卓越，但复杂的高维损失函数使其优化极具挑战性。尽管自适应优化器如AdamW被广泛应用，但它们存在无法捕捉坐标间依赖关系及高内存消耗的局限。后续研究如SOAP虽改进了坐标依赖捕捉，却因内存占用过高而限制了大规模LLMs的应用。另一种通过低维投影降维的方法虽能减少内存，却因显著近似误差而影响优化效果。本文提出COSMOS——一种创新性混合优化器，它基于梯度矩阵中特征子空间的重要性差异，在不降低优化效果的前提下实现内存优化。COSMOS的设计源于我们的实践经验：它将SOAP应用于主要特征子空间以捕捉核心优化动态，而将MUON用于次要特征子空间以降低计算开销。这种策略显著降低了内存需求，同时保持了稳健的优化性能，特别适用于大规模LLMs。我们在多种数据集和Transformer架构上的实验验证了COSMOS的优越性。我们的代码可在https://github.com/lliu606/COSMOS获取。

> Large Language Models (LLMs) have demonstrated remarkable success across various domains, yet their optimization remains a significant challenge due to the complex and high-dimensional loss landscapes they inhabit. While adaptive optimizers such as AdamW are widely used, they suffer from critical limitations, including an inability to capture interdependencies between coordinates and high memory consumption. Subsequent research, exemplified by SOAP, attempts to better capture coordinate interdependence but incurs greater memory overhead, limiting scalability for massive LLMs. An alternative approach aims to reduce memory consumption through low-dimensional projection, but this leads to substantial approximation errors, resulting in less effective optimization (e.g., in terms of per-token efficiency). In this paper, we propose COSMOS, a novel hybrid optimizer that leverages the varying importance of eigensubspaces in the gradient matrix to achieve memory efficiency without compromising optimization performance. The design of COSMOS is motivated by our empirical insights and practical considerations. Specifically, COSMOS applies SOAP to the leading eigensubspace, which captures the primary optimization dynamics, and MUON to the remaining eigensubspace, which is less critical but computationally expensive to handle with SOAP. This hybrid strategy significantly reduces memory consumption while maintaining robust optimization performance, making it particularly suitable for massive LLMs. Numerical experiments on various datasets and transformer architectures are provided to demonstrate the effectiveness of COSMOS. Our code is available at https://github.com/lliu606/COSMOS.

[Arxiv](https://arxiv.org/abs/2502.17410)