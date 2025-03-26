# VecTrans：高性能 CPU 上自动向量化优化的 LLM 转换框架

发布时间：2025年03月25日

`LLM应用` `编译器优化` `编译器`

> VecTrans: LLM Transformation Framework for Better Auto-vectorization on High-performance CPU

# 摘要

> 大型语言模型（LLMs）在代码生成方面展现出了强大的能力，但在编译器优化中的实际应用仍面临挑战，主要源于幻觉现象和领域特定推理能力的不足。向量化作为提升代码性能的关键优化手段，常因编译器无法识别复杂代码模式而受挫，这通常需要丰富的经验知识。而LLMs凭借其捕捉复杂模式的能力，为这一难题提供了一个有潜力的解决方案。本文提出VecTrans，一个创新性框架，旨在利用LLMs提升编译器的代码向量化能力。VecTrans首先通过编译器分析定位潜在可向量化代码区域，随后借助LLMs将这些区域重构为更易于编译器自动向化的模式。为确保语义正确性，VecTrans在中间表示（IR）级别集成了混合验证机制。通过以上努力，VecTrans成功融合了LLMs的适应性与编译器向量化的精准性，从而有效拓展了向量化的机会。实验结果表明，在Clang、GCC和BiShengCompiler均无法向量化的50个TSVC函数中，VecTrans成功向量化了23个案例（占比46%），实现了平均2.02倍的加速效果，远超当前最优性能。

> Large language models (LLMs) have demonstrated great capabilities in code generation, yet their effective application in compiler optimizations remains an open challenge due to issues such as hallucinations and a lack of domain-specific reasoning. Vectorization, a crucial optimization for enhancing code performance, often fails because of the compiler's inability to recognize complex code patterns, which commonly require extensive empirical expertise. LLMs, with their ability to capture intricate patterns, thus providing a promising solution to this challenge. This paper presents VecTrans, a novel framework that leverages LLMs to enhance compiler-based code vectorization. VecTrans first employs compiler analysis to identify potentially vectorizable code regions. It then utilizes an LLM to refactor these regions into patterns that are more amenable to the compiler's auto-vectorization. To ensure semantic correctness, VecTrans further integrates a hybrid validation mechanism at the intermediate representation (IR) level. With the above efforts, VecTrans combines the adaptability of LLMs with the precision of compiler vectorization, thereby effectively opening up the vectorization opportunities. Experimental results show that among all 50 TSVC functions unvectorizable by Clang, GCC, and BiShengCompiler, VecTrans successfully vectorizes 23 cases (46%) and achieves an average speedup of 2.02x, greatly surpassing state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2503.19449)