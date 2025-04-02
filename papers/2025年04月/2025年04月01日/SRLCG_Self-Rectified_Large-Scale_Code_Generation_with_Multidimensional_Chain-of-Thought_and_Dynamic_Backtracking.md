# SRLCG：自我修正的大规模代码生成，融合多维思维链路与动态回溯

发布时间：2025年04月01日

`LLM应用` `代码生成`

> SRLCG: Self-Rectified Large-Scale Code Generation with Multidimensional Chain-of-Thought and Dynamic Backtracking

# 摘要

> 大型语言模型（LLMs）彻底改变了代码生成领域，极大提升了开发者的生产力。然而，对于广大缺乏编程知识的用户群体来说，LLMs的支持微乎其微，因为它们主要生成孤立的代码片段，而非完整的大型项目代码。由于缺乏编程经验，这些用户难以解读、修改并迭代优化LLMs的输出结果，导致无法完成一个完整项目的组装。为了解决这一问题，我们提出了自校正大规模代码生成器（SRLCG），一个能够从单一提示生成完整多文件项目代码的框架。SRLCG采用了一种创新的多维链式思维（CoT）和自我校正机制，引导LLMs生成正确且健壮的代码文件，随后通过我们提出的动态回溯算法将这些文件整合成一个完整且连贯的项目。实验结果显示，与DeepSeek-V3相比，SRLCG生成的代码长度是其15倍，是GPT-4的16倍，比其他领先的基于CoT的基线模型至少长10倍。此外，实验结果还证实了在大规模代码生成方面，SRLCG在正确性、健壮性和性能上均优于基线模型。

> Large language models (LLMs) have revolutionized code generation, significantly enhancing developer productivity. However, for a vast number of users with minimal coding knowledge, LLMs provide little support, as they primarily generate isolated code snippets rather than complete, large-scale project code. Without coding expertise, these users struggle to interpret, modify, and iteratively refine the outputs of LLMs, making it impossible to assemble a complete project. To address this issue, we propose Self-Rectified Large-Scale Code Generator (SRLCG), a framework that generates complete multi-file project code from a single prompt. SRLCG employs a novel multidimensional chain-of-thought (CoT) and self-rectification to guide LLMs in generating correct and robust code files, then integrates them into a complete and coherent project using our proposed dynamic backtracking algorithm. Experimental results show that SRLCG generates code 15x longer than DeepSeek-V3, 16x longer than GPT-4, and at least 10x longer than other leading CoT-based baselines. Furthermore, they confirm its improved correctness, robustness, and performance compared to baselines in large-scale code generation.

[Arxiv](https://arxiv.org/abs/2504.00532)