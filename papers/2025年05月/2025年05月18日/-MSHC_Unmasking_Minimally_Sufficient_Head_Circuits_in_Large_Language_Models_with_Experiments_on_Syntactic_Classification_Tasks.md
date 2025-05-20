# MSHC：揭示大型语言模型中的最小必要头部电路——基于句法分类任务的实验研究

发布时间：2025年05月18日

`LLM理论

理由：这篇论文探讨了中型语言模型内部的神经组件，特别是注意力机制在不同任务中的作用，属于对模型理论和机制的深入分析。` `语言模型` `注意力机制`

> -MSHC: Unmasking Minimally Sufficient Head Circuits in Large Language Models with Experiments on Syntactic Classification Tasks

# 摘要

> 理解中型语言模型（【数学公式】）中驱动特定能力的神经组件依然是关键挑战。我们提出了$(\bm{K}, ε)$-最小必要注意力头回路（$K$-MSHC），一种识别分类任务关键注意力头集合的方法，以及高效算法Search-K-MSHC用于发现这些回路。将Search-K-MSHC应用于Gemma-9B模型，我们分析了三个句法任务家族：语法可接受性、算术验证和算术 word 问题。研究发现，不同任务具有特定的注意力头回路，语法任务主要利用早期层，word 问题在浅层和深层区域活动显著，算术验证则在网络中呈现分散模式。我们发现非线性回路重叠模式，不同任务对共享组件重要性各不相同。语法和算术共享许多“弱”注意力头，而算术和 word 问题共享更多关键“强”注意力头。重要的是，每个任务都有专用“超级注意力头”，跨任务重叠极少，表明句法和数值能力源自专用且部分可重用的注意力头回路。

> Understanding which neural components drive specific capabilities in mid-sized language models ($\leq$10B parameters) remains a key challenge. We introduce the $(\bm{K}, ε)$-Minimum Sufficient Head Circuit ($K$-MSHC), a methodology to identify minimal sets of attention heads crucial for classification tasks as well as Search-K-MSHC, an efficient algorithm for discovering these circuits. Applying our Search-K-MSHC algorithm to Gemma-9B, we analyze three syntactic task families: grammar acceptability, arithmetic verification, and arithmetic word problems. Our findings reveal distinct task-specific head circuits, with grammar tasks predominantly utilizing early layers, word problems showing pronounced activity in both shallow and deep regions, and arithmetic verification demonstrating a more distributed pattern across the network. We discover non-linear circuit overlap patterns, where different task pairs share computational components at varying levels of importance. While grammar and arithmetic share many "weak" heads, arithmetic and word problems share more consistently critical "strong" heads. Importantly, we find that each task maintains dedicated "super-heads" with minimal cross-task overlap, suggesting that syntactic and numerical competencies emerge from specialized yet partially reusable head circuits.

[Arxiv](https://arxiv.org/abs/2505.12268)