# OSVBench：用于操作系统验证的规范生成任务中大型语言模型的基准测试

发布时间：2025年04月29日

`LLM应用` `操作系统` `软件工程`

> OSVBench: Benchmarking LLMs on Specification Generation Tasks for Operating System Verification

# 摘要

> 我们推出 OSVBench，这是一个全新的基准测试，专注于评估大型语言模型（LLMs）在生成操作系统内核验证任务相关完整规范代码方面的能力。该基准测试通过为 LLMs 提供编程模型，将规范生成问题转化为一个限定语法和语义范围内的程序合成问题。模型需要理解提供的验证假设及搜索空间，最终根据操作系统的功能描述，为可能存在缺陷的操作系统代码生成完整规范。该基准测试基于真实世界操作系统内核 Hyperkernel 构建，包含 245 个复杂规范生成任务，每个任务涉及约 20k-30k 个令牌的长上下文。对 12 个 LLM 的全面评估显示，当前模型在规范生成任务上的表现有限。显著的性能差异反映了它们在处理长上下文代码生成任务上的能力差异。评估工具包及基准测试已开源，访问 https://github.com/lishangyu-hkust/OSVBench 了解详情。

> We introduce OSVBench, a new benchmark for evaluating Large Language Models (LLMs) in generating complete specification code pertaining to operating system kernel verification tasks. The benchmark first defines the specification generation problem into a program synthesis problem within a confined scope of syntax and semantics by providing LLMs with the programming model. The LLMs are required to understand the provided verification assumption and the potential syntax and semantics space to search for, then generate the complete specification for the potentially buggy operating system code implementation under the guidance of the high-level functional description of the operating system. This benchmark is built upon a real-world operating system kernel, Hyperkernel, and consists of 245 complex specification generation tasks in total, each is a long context task of about 20k-30k tokens. Our comprehensive evaluation of 12 LLMs exhibits the limited performance of the current LLMs on the specification generation tasks for operating system verification. Significant disparities in their performance on the benchmark highlight differences in their ability to handle long-context code generation tasks. The evaluation toolkit and benchmark are available at https://github.com/lishangyu-hkust/OSVBench.

[Arxiv](https://arxiv.org/abs/2504.20964)