# # ASMA-Tune：通过结构语义指令微调解锁 LLMs 的汇编代码理解

发布时间：2025年03月14日

`LLM应用

摘要讨论了将大型语言模型（LLMs）应用于汇编代码分析的挑战，并提出了一种新的方法来提升LLMs在该领域的性能。这属于LLM的应用领域。` `软件工程` `逆向工程`

> ASMA-Tune: Unlocking LLMs' Assembly Code Comprehension via Structural-Semantic Instruction Tuning

# 摘要

> 汇编代码的分析与理解在逆向工程等场景中至关重要，但其信息密度低且缺乏显式句法结构，带来了重大挑战。基于遮蔽语言模型（MLM）的方法在促进自然语言交互方面存在局限，而近期基于解码器的大型语言模型（LLMs）虽提升了语义表示，仍难以捕捉汇编代码中细微且稀疏的语义。本文提出Assembly Augmented Tuning（ASMA-Tune），一个端到端的结构-语义指令微调框架。通过投影模块结合编码器架构与基于解码器的LLMs，ASMA-Tune实现了全面的代码理解。实验表明，ASMA-Tune显著超越现有基准，提升了汇编代码理解能力和指令遵循能力。我们的模型和数据集已在GitHub公开，地址为https://github.com/wxy3596/ASMA-Tune。

> Analysis and comprehension of assembly code are crucial in various applications, such as reverse engineering. However, the low information density and lack of explicit syntactic structures in assembly code pose significant challenges. Pioneering approaches with masked language modeling (MLM)-based methods have been limited by facilitating natural language interaction. While recent methods based on decoder-focused large language models (LLMs) have significantly enhanced semantic representation, they still struggle to capture the nuanced and sparse semantics in assembly code. In this paper, we propose Assembly Augmented Tuning (ASMA-Tune), an end-to-end structural-semantic instruction-tuning framework. Our approach synergizes encoder architectures with decoder-based LLMs through projector modules to enable comprehensive code understanding. Experiments show that ASMA-Tune outperforms existing benchmarks, significantly enhancing assembly code comprehension and instruction-following abilities. Our model and dataset are public at https://github.com/wxy3596/ASMA-Tune.

[Arxiv](https://arxiv.org/abs/2503.11617)