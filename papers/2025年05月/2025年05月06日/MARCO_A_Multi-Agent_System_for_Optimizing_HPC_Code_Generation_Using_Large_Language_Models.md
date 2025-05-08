# MARCO: 基于大型语言模型的高性能计算代码生成优化多智能体系统

发布时间：2025年05月06日

`Agent` `软件开发` `高性能计算`

> MARCO: A Multi-Agent System for Optimizing HPC Code Generation Using Large Language Models

# 摘要

> 大型语言模型（LLMs）通过代码生成能力彻底改变了软件开发，然而它们在高性能计算（HPC）领域的效果仍然有限。HPC代码需要针对并行性、内存效率和特定架构进行专门优化，而通用型LLMs常常忽视这些方面。我们提出了MARCO（多智能体反应式代码优化框架），一个通过专用多智能体架构增强LLM生成代码的全新框架。MARCO采用了独立的生成器和评估器智能体，并通过反馈循环逐步优化。一个关键创新是MARCO的网络搜索组件，它从近期会议论文和研究报告中检索实时优化技术，弥补了预训练LLMs的知识缺口。我们在LeetCode 75问题集上的广泛评估表明，与仅使用Claude 3.5 Sonnet相比，MARCO实现了14.6%的平均运行时间减少，而网络搜索组件的集成则使性能比基础MARCO系统提升了30.9%。这些结果突显了多智能体系统在满足高性能代码生成特殊需求方面的潜力，为领域特定模型的微调提供了一种更具成本效益的替代方案。


> Large language models (LLMs) have transformed software development through code generation capabilities, yet their effectiveness for high-performance computing (HPC) remains limited. HPC code requires specialized optimizations for parallelism, memory efficiency, and architecture-specific considerations that general-purpose LLMs often overlook. We present MARCO (Multi-Agent Reactive Code Optimizer), a novel framework that enhances LLM-generated code for HPC through a specialized multi-agent architecture. MARCO employs separate agents for code generation and performance evaluation, connected by a feedback loop that progressively refines optimizations. A key innovation is MARCO's web-search component that retrieves real-time optimization techniques from recent conference proceedings and research publications, bridging the knowledge gap in pre-trained LLMs. Our extensive evaluation on the LeetCode 75 problem set demonstrates that MARCO achieves a 14.6% average runtime reduction compared to Claude 3.5 Sonnet alone, while the integration of the web-search component yields a 30.9% performance improvement over the base MARCO system. These results highlight the potential of multi-agent systems to address the specialized requirements of high-performance code generation, offering a cost-effective alternative to domain-specific model fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.03906)