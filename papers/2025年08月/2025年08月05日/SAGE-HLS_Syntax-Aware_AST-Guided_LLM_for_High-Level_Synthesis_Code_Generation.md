# SAGE-HLS: 语法感知、AST 引导的 LLM 用于高层次综合代码生成

发布时间：2025年08月05日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在硬件设计自动化中的应用，特别是高级综合（HLS）中的代码生成。研究者们提出了一个微调的LLM（SAGE-HLS），并详细描述了其创新点和实验结果。这属于LLM在特定领域中的应用，因此归类为LLM应用。` `EDA` `HLS`

> SAGE-HLS: Syntax-Aware AST-Guided LLM for High-Level Synthesis Code Generation

# 摘要

> 在快速发展的电子设计自动化（EDA）领域，硬件设计的复杂性不断增加，对更高级的自动化解决方案提出了更高要求。高级综合（HLS）作为一种关键解决方案，能够从高层次抽象（如C/C++）自动化硬件设计。然而，HLS在设计空间探索和优化方面面临重大挑战。尽管大型语言模型（LLMs）在代码生成方面展现出显著能力，但受限于公开可用的HLS代码数据集的匮乏，其在HLS中的应用受到限制。因此，该领域的研究主要集中在提示工程和增强生成（RAG）等技术上。

为克服这一限制，本文引入了SAGE-HLS，这是首个专门针对HLS代码生成的微调LLM。我们的方法包含三个关键创新：(i) 我们实现了Verilog到C/C++的端口转换，将经过验证且可综合的Verilog代码转换为相应的C代码，创建了一个包含16.7K HLS代码的数据集；(ii) 我们实施了一种基于指令提示的微调策略，通过抽象语法树（AST）指导代码生成；(iii) 我们开发了一个半自动评估框架，利用VerilogEval评估生成的HLS代码的功能性。

实验表明，基于QwenCoder (2.5) 7B模型微调的SAGE-HLS，在代码可综合性方面达到了近100%的成功率，并在功能性正确性方面达到了75%的成功率。

> In today's rapidly evolving field of electronic design automation (EDA), the complexity of hardware designs is increasing, necessitating more sophisticated automation solutions. High-level synthesis (HLS), as a pivotal solution, automates hardware designs from high-level abstractions (e.g., C/C++). However, it faces significant challenges, particularly in design space exploration and optimization. While large language models (LLMs) have shown notable capabilities in code generation, their application to HLS has been limited due to the scarcity of (publicly) available HLS code datasets. Hence, research in this domain has primarily focused on techniques such as prompt engineering and retrieval-augmented generation (RAG). To overcome this limitation, this paper introduces SAGE-HLS, the first-of-its-kind fine-tuned LLM specifically for HLS code generation. Our method includes three key advancements: (i) We implement Verilog-to-C/C++ porting, converting verified and synthesizable Verilog codes into corresponding C, creating a dataset of 16.7K HLS codes; (ii) We implement a fine-tuning strategy, which is based on instruction prompting to code generation guided by abstract syntax tree (AST); (iii) We develop a semi-automated evaluation framework using VerilogEval to assess the functionality of the generated HLS code. Our experiments show that SAGE-HLS, fined-tuned on the QwenCoder (2.5) 7B model, achieves a near 100% success rate in code synthesizability and a 75% success rate in functional correctness.

[Arxiv](https://arxiv.org/abs/2508.03558)