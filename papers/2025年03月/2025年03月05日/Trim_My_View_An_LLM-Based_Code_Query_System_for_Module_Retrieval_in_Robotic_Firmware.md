# Trim My View：基于LLM的代码查询系统，专为机器人固件模块检索而设计。

发布时间：2025年03月05日

`LLM应用` `软件工程` `逆向工程`

> Trim My View: An LLM-Based Code Query System for Module Retrieval in Robotic Firmware

# 摘要

> 软件编译过程往往会模糊系统的原始设计，让识别单个组件及其功能变得困难，仅凭二进制代码难以辨识。反编译技术虽然试图从机器码中恢复更高层次的源代码，但无法完全还原原始函数的语义。此外，二进制文件通常会剥离元数据，这使得逆向工程复杂的二进制软件更具挑战性。

本文中，我们展示了如何结合二进制分解技术、反编译过程以及由LLM驱动的功能总结，构建一个经济高效的引擎，用于识别剥离元数据的二进制文件中的模块，并将它们与高级自然语言描述关联起来。我们使用三种开源LLM——CodeQwen、DeepSeek-Coder 和 CodeStral——实现了这一技术，并在机器人固件中评估了其识别模块的有效性。实验评估涵盖了来自ArduPilot软件套件的四台设备的467个模块，结果显示，表现最佳的后端LLM CodeStral在仅需数秒在线运行时间的情况下，平均F1分数达到了0.68。

> The software compilation process has a tendency to obscure the original design of the system and makes it difficult both to identify individual components and discern their purpose simply by examining the resulting binary code. Although decompilation techniques attempt to recover higher-level source code from the machine code in question, they are not fully able to restore the semantics of the original functions. Furthermore, binaries are often stripped of metadata, and this makes it challenging to reverse engineer complex binary software.
  In this paper we show how a combination of binary decomposition techniques, decompilation passes, and LLM-powered function summarization can be used to build an economical engine to identify modules in stripped binaries and associate them with high-level natural language descriptions. We instantiated this technique with three underlying open-source LLMs -- CodeQwen, DeepSeek-Coder and CodeStral -- and measured its effectiveness in identifying modules in robotics firmware. This experimental evaluation involved 467 modules from four devices from the ArduPilot software suite, and showed that CodeStral, the best-performing backend LLM, achieves an average F1-score of 0.68 with an online running time of just a handful of seconds.

[Arxiv](https://arxiv.org/abs/2503.03969)