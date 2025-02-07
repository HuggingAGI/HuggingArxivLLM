# PGB: 基于权重分组与排列的BERT一次性剪枝

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要讨论了如何通过一种新颖的半结构化一次性剪枝方法（PGB）来压缩大型预训练语言模型（如BERT），以提高推理速度和减少内存占用。这涉及到对模型结构和权重的优化，属于对大型语言模型的理论研究和改进，因此应归类为“LLM理论”。` `模型压缩`

> PGB: One-Shot Pruning for BERT via Weight Grouping and Permutation

# 摘要

> 大型预训练语言模型（如BERT）因体积庞大，常面临推理速度慢和内存占用高的问题。现有压缩方法多依赖迭代剪枝和知识蒸馏，但往往复杂且计算密集。本文提出了一种新颖的半结构化一次性剪枝方法——$	extit{Permutation and Grouping for BERT}$（PGB），在保持高准确性的同时，实现了高效的压缩和稀疏性。PGB通过排列识别重要权重组，并在多头注意力和前馈层中剪除其他权重组。若某层无重要组，PGB会直接丢弃该层，生成更紧凑的模型。实验表明，PGB在BERT$_{	ext{BASE}}$上的表现优于现有结构化剪枝方法，尤其在计算成本和准确性保持方面。

> Large pretrained language models such as BERT suffer from slow inference and high memory usage, due to their huge size. Recent approaches to compressing BERT rely on iterative pruning and knowledge distillation, which, however, are often too complicated and computationally intensive. This paper proposes a novel semi-structured one-shot pruning method for BERT, called $\textit{Permutation and Grouping for BERT}$ (PGB), which achieves high compression efficiency and sparsity while preserving accuracy. To this end, PGB identifies important groups of individual weights by permutation and prunes all other weights as a structure in both multi-head attention and feed-forward layers. Furthermore, if no important group is formed in a particular layer, PGB drops the entire layer to produce an even more compact model. Our experimental results on BERT$_{\text{BASE}}$ demonstrate that PGB outperforms the state-of-the-art structured pruning methods in terms of computational cost and accuracy preservation.

[Arxiv](https://arxiv.org/abs/2502.03984)