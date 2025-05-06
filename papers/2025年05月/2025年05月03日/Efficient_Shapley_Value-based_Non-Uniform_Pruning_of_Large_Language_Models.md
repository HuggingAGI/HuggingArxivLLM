# 基于夏普利值的高效非均匀剪枝方法在大型语言模型中的应用

发布时间：2025年05月03日

`LLM应用` `人工智能` `模型优化`

> Efficient Shapley Value-based Non-Uniform Pruning of Large Language Models

# 摘要

> 剪枝大型语言模型（LLMs）是减小模型规模和计算复杂度同时保留性能的有力手段。传统逐层剪枝方法往往采用全模型统一稀疏度策略，忽视了不同Transformer层的重要性差异，导致性能欠佳。为此，我们提出了基于Shapley值的非均匀剪枝方法（SVNUP），该方法量化各层对整体性能的贡献，为不同层分配定制化剪枝预算，保留关键参数。为提升效率，我们设计了基于滑动窗口的Shapley值近似方法，较精确计算方法大幅降低了计算开销。在LLaMA-v1、LLaMA-v2和OPT等多种模型上的实验验证了方法的有效性。结果表明，非均匀剪枝显著提升了剪枝后模型性能。值得注意的是，与SparseGPT在70%稀疏度下相比，SVNUP在LLaMA-7B和LLaMA-13B上分别实现了18.01%和19.55%的困惑度（PPL）降低。

> Pruning large language models (LLMs) is a promising solution for reducing model sizes and computational complexity while preserving performance. Traditional layer-wise pruning methods often adopt a uniform sparsity approach across all layers, which leads to suboptimal performance due to the varying significance of individual transformer layers within the model not being accounted for. To this end, we propose the \underline{S}hapley \underline{V}alue-based \underline{N}on-\underline{U}niform \underline{P}runing (\methodname{}) method for LLMs. This approach quantifies the contribution of each transformer layer to the overall model performance, enabling the assignment of tailored pruning budgets to different layers to retain critical parameters. To further improve efficiency, we design the Sliding Window-based Shapley Value approximation method. It substantially reduces computational overhead compared to exact SV calculation methods. Extensive experiments on various LLMs including LLaMA-v1, LLaMA-v2 and OPT demonstrate the effectiveness of the proposed approach. The results reveal that non-uniform pruning significantly enhances the performance of pruned models. Notably, \methodname{} achieves a reduction in perplexity (PPL) of 18.01\% and 19.55\% on LLaMA-7B and LLaMA-13B, respectively, compared to SparseGPT at 70\% sparsity.

[Arxiv](https://arxiv.org/abs/2505.01731)