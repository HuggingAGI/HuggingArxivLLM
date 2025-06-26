# VeriLocc：全流程跨架构寄存器分配，基于大型语言模型

发布时间：2025年06月20日

`LLM应用` `编译器` `GPU`

> VeriLocc: End-to-End Cross-Architecture Register Allocation via LLM

# 摘要

> 现代GPU技术日新月异，但现有编译器仍依赖于需要不断调整的手工启发式寄存器分配策略。我们推出VeriLocc框架，融合大型语言模型与形式化编译技术，实现跨GPU架构的通用化、可验证寄存器分配。VeriLocc通过微调大型语言模型，将中间表示（MIRs）转化为针对特定架构的寄存器分配方案。借助静态分析进行跨架构的规范化和泛化，并通过验证器引导的再生循环确保分配的正确性。在矩阵乘法（GEMM）和多头注意力（MHA）任务上的评估显示，VeriLocc的单次分配准确率达到85-99%，并通过100次尝试几乎达到100%的通过率。案例研究显示，VeriLocc发现的分配方案比专家优化的库更高效，在运行时性能上比rocBLAS提升了10%以上。


> Modern GPUs evolve rapidly, yet production compilers still rely on hand-crafted register allocation heuristics that require substantial re-tuning for each hardware generation. We introduce VeriLocc, a framework that combines large language models (LLMs) with formal compiler techniques to enable generalizable and verifiable register allocation across GPU architectures. VeriLocc fine-tunes an LLM to translate intermediate representations (MIRs) into target-specific register assignments, aided by static analysis for cross-architecture normalization and generalization and a verifier-guided regeneration loop to ensure correctness. Evaluated on matrix multiplication (GEMM) and multi-head attention (MHA), VeriLocc achieves 85-99% single-shot accuracy and near-100% pass@100. Case study shows that VeriLocc discovers more performant assignments than expert-tuned libraries, outperforming rocBLAS by over 10% in runtime.

[Arxiv](https://arxiv.org/abs/2506.17506)