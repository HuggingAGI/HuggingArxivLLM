# # 神经不兼容性：大型语言模型中跨尺度参数化知识迁移的不可逾越的鸿沟

发布时间：2025年05月20日

`LLM理论`

> Neural Incompatibility: The Unbridgeable Gap of Cross-Scale Parametric Knowledge Transfer in Large Language Models

# 摘要

> 大型语言模型（LLMs）提供了一个透明的思维结构，其可访问的参数编码了丰富的知识，这些知识可以被分析、定位和迁移。因此，一个关键的研究挑战是超越基于符号语言的传统知识转移范式，实现真正意义上的参数化知识转移（PKT）。特别值得注意的是，探索通过参数在不同规模的LLMs之间有效转移知识的方法，是一个既有趣又有价值的研究方向。本文首先证明在参数空间中实现$	extbf{对齐}$是成功实现跨规模PKT的基本前提。我们将之前探索的知识转移重新定义为Post-Align PKT（PostPKT），该方法利用提取的参数进行LoRA初始化，并需要后续的微调以实现对齐。因此，为了降低进一步微调的成本，我们引入了一种全新的Pre-Align PKT（PrePKT）范式，并提出了一种名为$	extbf{LaTen}$（$	extbf{L}$oc$	extbf{a}$te-$	extbf{T}$h$	extbf{e}$n-Alig$	extbf{n}$）的解决方案，该方案仅通过几个训练步骤即可对齐不同规模LLMs的参数空间，而无需后续训练。在四个基准上的综合实验表明，PostPKT和PrePKT在实现一致稳定的迁移方面都面临挑战。通过深入分析，我们发现$	extbf{神经不兼容性}$是不同规模LLMs之间的生态和参数结构差异，这为实现有效的PKT带来了根本性的挑战。这些发现为LLMs的参数架构提供了新的见解，并为未来高效PKT的研究指明了有前途的方向。我们的代码可在https://github.com/Trae1ounG/Neural_Incompatibility获取。

> Large Language Models (LLMs) offer a transparent brain with accessible parameters that encode extensive knowledge, which can be analyzed, located and transferred. Consequently, a key research challenge is to transcend traditional knowledge transfer paradigms rooted in symbolic language and achieve genuine Parametric Knowledge Transfer (PKT). Significantly, exploring effective methods for transferring knowledge across LLMs of different scales through parameters presents an intriguing and valuable research direction. In this paper, we first demonstrate $\textbf{Alignment}$ in parametric space is the fundamental prerequisite to achieve successful cross-scale PKT. We redefine the previously explored knowledge transfer as Post-Align PKT (PostPKT), which utilizes extracted parameters for LoRA initialization and requires subsequent fine-tune for alignment. Hence, to reduce cost for further fine-tuning, we introduce a novel Pre-Align PKT (PrePKT) paradigm and propose a solution called $\textbf{LaTen}$ ($\textbf{L}$oc$\textbf{a}$te-$\textbf{T}$h$\textbf{e}$n-Alig$\textbf{n}$) that aligns the parametric spaces of LLMs across scales only using several training steps without following training. Comprehensive experiments on four benchmarks demonstrate that both PostPKT and PrePKT face challenges in achieving consistently stable transfer. Through in-depth analysis, we identify $\textbf{Neural Incompatibility}$ as the ethological and parametric structural differences between LLMs of varying scales, presenting fundamental challenges to achieving effective PKT. These findings provide fresh insights into the parametric architectures of LLMs and highlight promising directions for future research on efficient PKT. Our code is available at https://github.com/Trae1ounG/Neural_Incompatibility.

[Arxiv](https://arxiv.org/abs/2505.14436)