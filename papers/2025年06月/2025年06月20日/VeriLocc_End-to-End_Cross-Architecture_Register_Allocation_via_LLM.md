# VeriLocc：通过LLM实现跨架构寄存器分配的端到端解决方案

发布时间：2025年06月20日

`LLM应用

摘要中详细介绍了VeriLocc框架，该框架结合了大型语言模型（LLMs）与正式编译器技术，用于优化GPU架构中的寄存器分配。这项工作展示了LLMs在编译器优化中的具体应用，属于将LLM技术应用于实际任务的范畴，因此归类为LLM应用。` `计算机体系结构` `编译器优化`

> VeriLocc: End-to-End Cross-Architecture Register Allocation via LLM

# 摘要

> 现代GPU发展日新月异，但生产编译器仍依赖于每次硬件更新都需要重新调整的手工寄存器分配启发式方法。我们提出了VeriLocc，一个结合大型语言模型（LLMs）与正式编译器技术的框架，旨在实现跨GPU架构的可推广且可验证的寄存器分配。VeriLocc通过静态分析辅助的跨架构规范化和推广，以及确保正确性的验证器引导再生循环，微调LLM将中间表示（MIRs）转换为目标特定的寄存器分配。在矩阵乘法（GEMM）和多头注意力（MHA）任务中，VeriLocc实现了85-99%的单次命中准确率和接近100%的pass@100。案例研究表明，VeriLocc发现的寄存器分配比专家优化的库更高效，运行时间比rocBLAS快10%以上。

> Modern GPUs evolve rapidly, yet production compilers still rely on hand-crafted register allocation heuristics that require substantial re-tuning for each hardware generation. We introduce VeriLocc, a framework that combines large language models (LLMs) with formal compiler techniques to enable generalizable and verifiable register allocation across GPU architectures. VeriLocc fine-tunes an LLM to translate intermediate representations (MIRs) into target-specific register assignments, aided by static analysis for cross-architecture normalization and generalization and a verifier-guided regeneration loop to ensure correctness. Evaluated on matrix multiplication (GEMM) and multi-head attention (MHA), VeriLocc achieves 85-99% single-shot accuracy and near-100% pass@100. Case study shows that VeriLocc discovers more performant assignments than expert-tuned libraries, outperforming rocBLAS by over 10% in runtime.

[Arxiv](https://arxiv.org/abs/2506.17506)