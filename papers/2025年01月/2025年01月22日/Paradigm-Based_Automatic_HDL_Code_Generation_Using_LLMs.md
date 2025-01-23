# 利用LLMs实现基于范式的自动HDL代码生成

发布时间：2025年01月22日

`LLM应用

理由：该论文主要讨论了如何通过构建专门的范式块和设计多轮生成工作流程来减少LLMs在生成HDL代码时的幻觉问题，并提升生成代码的性能。这属于将LLMs应用于特定领域（数字电路设计）的实际问题解决，因此归类为“LLM应用”。` `电子设计自动化` `硬件描述语言`

> Paradigm-Based Automatic HDL Code Generation Using LLMs

# 摘要

> 尽管LLMs在生成数字电路的HDL代码方面表现出色，但它们仍受幻觉问题困扰，可能导致生成错误代码或误解规范。为此，我们提出了一种受人类专家启发的方法，旨在减少LLMs的幻觉并提升HDL代码生成性能。我们首先构建了专门的范式块，这些块通过分步骤处理生成任务，模仿人类专家的设计流程，包括信息提取、设计流程模拟和外部工具集成。接着，我们指导LLMs对电路类型进行分类，匹配相应的范式块并生成HDL代码。此外，我们设计了一个两阶段的多轮生成工作流程，旨在有限轮次内提高生成的HDL代码的测试通过率。实验证明，该方法显著提升了生成的Verilog代码的功能正确性。

> While large language models (LLMs) have demonstrated the ability to generate hardware description language (HDL) code for digital circuits, they still face the hallucination problem, which can result in the generation of incorrect HDL code or misinterpretation of specifications. In this work, we introduce a human-expert-inspired method to mitigate the hallucination of LLMs and enhance their performance in HDL code generation. We begin by constructing specialized paradigm blocks that consist of several steps designed to divide and conquer generation tasks, mirroring the design methodology of human experts. These steps include information extraction, human-like design flows, and the integration of external tools. LLMs are then instructed to classify the type of circuit in order to match it with the appropriate paradigm block and execute the block to generate the HDL codes. Additionally, we propose a two-phase workflow for multi-round generation, aimed at effectively improving the testbench pass rate of the generated HDL codes within a limited number of generation and verification rounds. Experimental results demonstrate that our method significantly enhances the functional correctness of the generated Verilog code

[Arxiv](https://arxiv.org/abs/2501.12702)