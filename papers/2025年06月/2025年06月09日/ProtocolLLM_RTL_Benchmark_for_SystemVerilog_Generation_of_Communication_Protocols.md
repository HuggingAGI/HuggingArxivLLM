# ProtocolLLM：通信协议SystemVerilog生成的RTL基准测试

发布时间：2025年06月09日

`LLM应用` `硬件设计` `嵌入式系统`

> ProtocolLLM: RTL Benchmark for SystemVerilog Generation of Communication Protocols

# 摘要

> 大型语言模型（LLMs）在生成通用编程语言代码方面表现优异，但其在硬件描述语言（HDLs）领域的应用，尤其是生成可综合且功能正确的设计方面，仍有待深入探索。SystemVerilog等HDL语言具有鲜明的逻辑导向性，要求严格遵循时序语义、并发性和可综合性约束。此外，基于HDL的设计流程不仅涉及结构化代码生成，还包括测试台开发、基于断言的验证、时序收敛以及片上通信的协议级集成等广泛任务。本文旨在分析当前最先进的LLMs在生成标准通信协议的SystemVerilog实现方面的能力，这是嵌入式和片上系统（SoC）架构的核心组成部分。本文提出了首个针对四种广泛使用的协议（SPI、I2C、UART和AXI）的基准测试套件。我们定义了不同设计抽象层次和提示具体性的代码生成任务。通过波形仿真和测试台，对生成的设计进行语法正确性、可综合性和功能保真度的评估。

> Recent advances in Large Language Models (LLMs) have shown promising capabilities in generating code for general-purpose programming languages. In contrast, their applicability for hardware description languages, particularly for generating synthesizable and functionally correct designs, remains significantly underexplored. HDLs such as SystemVerilog are logic-oriented and demand strict adherence to timing semantics, concurrency, and synthesizability constraints. Moreover, HDL-based design flows encompass a broad set of tasks beyond structural code generation, including testbench development, assertion-based verification, timing closure, and protocol-level integration for on-chip communication. The objective of our paper is to analyze the capabilities of state-of-the-art LLMs in generating SystemVerilog implementations of standard communication protocols, a core component of embedded and System-on-Chip (SoC) architectures. This paper introduces the first benchmark suite targeting four widely used protocols: SPI, I2C, UART, and AXI. We define code generation tasks that capture varying levels of design abstraction and prompt specificity. The generated designs are assessed for syntactic correctness, synthesizability, and functional fidelity via waveform simulation and test benches.

[Arxiv](https://arxiv.org/abs/2506.07945)